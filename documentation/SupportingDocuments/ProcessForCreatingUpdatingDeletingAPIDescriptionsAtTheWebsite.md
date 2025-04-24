# Process for creating, updating and deleting API descriptions at the CAMARA website

## Process for content creation:
Actor: Sub Project or Independent Sandbox team

- New API (name)
  - Trigger: Actor finalizes the decision about the API name
    - Action: Actor creates API description (based on given [Wiki template](https://lf-camaraproject.atlassian.net/wiki/spaces/CAM/pages/110854523/API+NAME+API+description)) and creates issue in Marketing repo (referencing Wiki page)
- New / update API public release
  - Trigger: Actor creates a new/update public release of API YAML
    - Action: Actor creates issue in Marketing repo to inform about the API description update (referencing updated Wiki page) and release (referencing release tracker)
- API public release becomes part of a meta-release
  - Trigger: Actor applies for API being part of a meta-release (M3/M4)
    - Action: Actor creates issue in Marketing repo to inform about the API description update (referencing updated Wiki page) and release (referencing release tracker)
- Change in API description requested
  - Trigger: Change request (by anybody, anywhere)
    - Action: Forward change request to Actor with reminder to check/update API description
    - Action: Actor creates issue in Marketing repo with updates to API description (referencing updated Wiki page)
- Delete API
  - Trigger: TSC archives API repository
    - Action: TSC creates issue in Marketing repo

## Process for website update:
Actor: Marketing team

- Website update
  - Trigger: Actor gets issue informing of API description update
  - Trigger: Actor performs cross-check with meta-release API list
    - Action: Actor updates API description / release information at website using updated information received
    - Action: Actor asks Sub Project / Independent Sandbox, API Backlog Working Group and OGW Product Workstream to review website content
    - Action: Actor includes review feedback (at website and Wiki page)
