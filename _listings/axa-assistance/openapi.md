---
swagger: "2.0"
x-collection-name: AXA Assistance
x-complete: 1
info:
  title: AXA Assistance
  description: axa-assistance-is-a-worldwide-specialist-for-car-insurance-travel-health-and-home-services--trust-in-axa-assistance-for-your-insurance
  version: 1.0.0
host: sandbox.api.axa-assistance.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /assistance/v1/home/electric_damage/declarations/{declaration_id}/policy_holders:
    get:
      summary: Gets the policy holders details for the electric damage
      description: Gets the policy holders details for the electric damage
      operationId: getAssistanceV1HomeElectric_damageDeclarationsDeclaration_idPolicy_holders
      x-api-path-slug: assistancev1homeelectric-damagedeclarationsdeclaration-idpolicy-holders-get
      parameters:
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - policy
      - holderAssistance
      - detailsthe
      - electric
      - damage
  /assistance/v1/home/electric_damage/declarations:
    post:
      summary: Create a declaration for an electric damage
      description: Create a declaration for an electric damage
      operationId: postAssistanceV1HomeElectric_damageDeclarations
      x-api-path-slug: assistancev1homeelectric-damagedeclarations-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - CreateDeclarationsan
      - electric
      - damage
  /assistance/v1/home/electric_damage/declarations/{declaration_id}/confirm:
    post:
      summary: Electric declaration confirmation
      description: Electric declaration confirmation
      operationId: postAssistanceV1HomeElectric_damageDeclarationsDeclaration_idConfirm
      x-api-path-slug: assistancev1homeelectric-damagedeclarationsdeclaration-idconfirm-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Electric
      - Declarations
      - confirmation
  /assistance/v1/home/electric_damage/declarations/{declaration_id}/contacts:
    post:
      summary: Adds contact information of the electric damage declaration
      description: Adds contact information of the electric damage declaration
      operationId: postAssistanceV1HomeElectric_damageDeclarationsDeclaration_idContacts
      x-api-path-slug: assistancev1homeelectric-damagedeclarationsdeclaration-idcontacts-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - contact
      - information
      - of
      - the
      - electric
      - damage
      - Declarations
  /assistance/v1/home/electric_damage/declarations/{declaration_id}/close:
    post:
      summary: Electric declaration closure
      description: Electric declaration closure
      operationId: postAssistanceV1HomeElectric_damageDeclarationsDeclaration_idClose
      x-api-path-slug: assistancev1homeelectric-damagedeclarationsdeclaration-idclose-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Electric
      - Declarations
      - closure
  /assistance/v1/home/electric_damage/declarations/{declaration_id}:
    patch:
      summary: Updates information related to the electric damage declaration
      description: Updates information related to the electric damage declaration
      operationId: patchAssistanceV1HomeElectric_damageDeclarationsDeclaration_id
      x-api-path-slug: assistancev1homeelectric-damagedeclarationsdeclaration-id-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - information
      - related
      - to
      - the
      - electric
      - damage
      - Declarations
  /assistance/v1/home/electric_damage/declarations/{declaration_id}/policy_holders/{policy_holder_id}:
    patch:
      summary: Updates the policy holder information of the electric damage declaration
      description: Updates the policy holder information of the electric damage declaration
      operationId: patchAssistanceV1HomeElectric_damageDeclarationsDeclaration_idPolicy_holdersPolicy_holder_id
      x-api-path-slug: assistancev1homeelectric-damagedeclarationsdeclaration-idpolicy-holderspolicy-holder-id-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      - in: path
        name: policy_holder_id
        description: ID of the policy holder
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - policy
      - holder
      - information
      - of
      - the
      - electric
      - damage
      - Declarations
---