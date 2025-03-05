---
name: "Request New Team"
description: "Request the creation of new teams for a project."
labels: ["help-desk", "team-request", "team-management"]
assignees: []
---

## Request New Teams for a Project

### Step 1: Creating a Maintainers Team

Project maintainers will be placed in their own separate team and serve as the main point of contact for coordinating team & repository management with the OSPO.

#### Required Information

Project Name: <!-- Provide the name of the project -->

Team Name: `<projectName>_maintainers`

GitHub Usernames to be Added:

- <!-- List all GitHub usernames -->

Team Visibility: `visible` or `secret`

---

### Step 2: Creating a Parent Team with All Project Members - Committers Team

All project members will be under the member role where they have no administrative permissions on the team. Team visibility and notifications are enabled unless specified otherwise.

#### Required Information

Team Name: `<projectName>_committers`

GitHub Usernames to be Added:

- <!-- List all GitHub usernames -->

Team Visibility: `visible` or `secret`

---

### (Optional) Step 3: Creating Child Teams

Child teams can be granted additional and more granular access to certain repositories. Examples of child teams can include code reviewers, developers under a repo domain, and project leads.

#### Required Information for each team

Team Name: `<projectName>_<teamType>`

Team type: <!-- Examples of Team Types include Frontend team, Backend team, Reviewers -->

GitHub Usernames to be Added:

- <!-- List all GitHub usernames -->

### Additional Notes (Optional)

<!-- Provide any additional context or requests -->
