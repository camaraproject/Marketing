# Process for creating, updating and deleting API descriptions at the CAMARA website

## Process for content creation:
Actor: Sub Project or Independent Sandbox team

- New API (name)
  - Trigger: Actor finalizes the decision about  API name
    - Action: Sub Project / Independent Sandbox creates API description (based on given Wiki template) and creates issue in Marketing repo (referencing Wiki page)
- New / update API public release
  - Trigger: Sub Project / Independent Sandbox creates a new/update public release of API YAML
    - Action: Sub Project / Independent Sandbox creates issue in Marketing repo to inform about the API description update (referencing updated Wiki page) and release (referencing release tracker)
- API public release becomes part of a meta-release
  - Trigger: Sub Project / Independent Sandbox applies for API being part of a meta-release (M3/M4)
    - Action: Sub Project / Independent Sandbox creates issue in Marketing repo to inform about the API description update (referencing updated Wiki page) and release (referencing release tracker)
- Change in API description requested
  - Trigger: Change request (by anybody, anywhere)
    - Action: Forward change request to Sub Project / Independent Sandbox with reminder to check/update API description
    - Action: Sub Project / Independent Sandbox creates issue in Marketing repo with updates to API description (referencing updated Wiki page)
- Delete API
  - Trigger: TSC archives API repository
    - Action: TSC creates issue in Marketing repo

## Process for website update:

- Website update
  - Trigger: Marketing team gets issue informing of API description update
  - Trigger: Marketing team performs cross-check with meta-release API list
    - Action: Marketing team updates API description / release information at website using updated information received
    - Action: Marketing team asks Sub Project / Independent Sandbox, API Backlog Working Group and OGW Product Workstream to review website content
    - Action: Marketing team includes review feedback (at website and Wiki page)
