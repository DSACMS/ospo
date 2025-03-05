---
name: "Request New Repository"
description: "Request the creation of a new repository under DSACMS."
labels: ["help-desk", "repo-request", "repo-management"]
assignees: []
---

## Request a New Repository

If you are looking to migrate an existing repository hosted in a different organization into a new repository under DSACMS, the new repository will be created as private by default. In order for your repository to be released as public, please follow our [outbound review checklist](https://github.com/DSACMS/ospo-guide/blob/main/outbound/outbound-checklists.md) for your project’s maturity tier.

If you are looking to create a completely new repository, your repository can be created as private or public. Based on the maturity model tier selected, a collection of markdown [templates](https://github.com/DSACMS/ospo-guide/blob/main/outbound/repository-templates-and-linters.md) will be included as part of our repository hygiene standards. GitHub security features such as Dependabot and secret scanning will be enabled.

Teams to be added to the repository are the maintainer team, committer team, and any other child teams. Maintainer teams are granted **MAINTAIN** access. Committer teams are granted **WRITE** access. If you or other members want to be promoted to **MAINTAIN** access, please indicate this in the form. **ADMIN** access is only available to DSACMS organization owners for now. `MAINTAINERS.md` will be updated accordingly.

### Required Information

Repository Name: <!-- Provide the desired repository name -->

Repository Description: <!-- Provide a short description of the repository -->

Project’s Maturity Model Tier: <!-- Specify the maturity tier -->

Repository Topics: <!-- List relevant topics for discoverability -->

Project Teams to Add to Repository:

- Maintainer Team: `<projectName>_maintainers`
- Committer Team: `<projectName>_committers`
- Any Other Teams/Child Teams: <!-- List additional teams if needed -->

Repository Visibility: `Private` or `Public`

<!-- For public repositories, please provide assessment of benefits and risks of selecting this visibility.-->

**Resources to assist with request**

- Maturity Model Tiers: https://github.com/DSACMS/ospo-guide/blob/main/outbound/maturity-models.md
- Repository Templates: https://github.com/DSACMS/ospo-guide/blob/main/outbound/repository-templates-and-linters.md
- Outbound Review Checklist: https://github.com/DSACMS/ospo-guide/blob/main/outbound/outbound-checklists.md

### Additional Notes (Optional)

<!-- Provide any additional context or requests -->
