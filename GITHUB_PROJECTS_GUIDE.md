# GitHub Project's Guide
This guide is for any team member that needs guidance on understanding what a GitHub Project is, why it is so valuable to our team, and/or how to use it.

For quick navigation:

- [Overview](#overview)
- [Why we use GitHub Projects](#whygp)
- [GitHub Project Components](#gpcomponents)
- [Guidelines](#guidelines)

## <a name="overview"></a> Overview
GitHub Projects are a project management tool. The Projects are meant to keep the team transparent and on schedule. Projects are made up of project boards that have 3 columns:

1. **To do** column
2. **In progress** column
3. **Review in progress** column
4. **Review approved** column
5. **Done** column

These columns are how the tasks within each team will be organized, assigned, and collaborated on.

For more information on project boards, see this [documentation](https://help.github.com/en/github/managing-your-work-on-github/about-project-boards) from GitHub.

## <a name="whygp"></a> Why we use GitHub Projects
We want to become world-class and productive developers. So our team will be attempting to work in an [Agile mindset using the Kanban framework](https://www.atlassian.com/agile/kanban). Due to this attempt, it is important that every member has a basic understanding of GitHub Projects.

## <a name="gpcomponents"></a> GitHub Project Components
There are 4 main components of GitHub Projects that you should know about. Namely:

- [Project (or Kanban) Board Component](#gpcomponents-project-board)
- [**To do** Column Component](#gpcomponents-to-do-column)
- [**In progress** Column Component](#gpcomponents-in-progress-column)
- [**Review in progress** Column Component](#gpcomponents-review-in-progress-column)
- [**Review approved** Column Component](#gpcomponents-review-approved-column)
- [**Done** Column Component](#gpcomponents-done-column)

### <a name="gpcomponents-project-board"></a> Project Board Component
The Project board is basically just container for all columns.

### <a name="gpcomponents-to-do-column"></a> **To do** Column Component
The first column in the Project Board. This column is responsible for containing all cards (tasks) that a team would have to finish by a certain deadline.

These cards are under the **To do** column. This means that these would be cards (tasks) that haven't been assigned to anyone to work on yet.

### <a name="gpcomponents-in-progress-column"></a> **In progress** Column Component
The second column in the Project Board. This column is responsible for containing all cards (tasks) that a team is actively working on.

These cards are under the **In progress** column. This means that these would be cards (tasks) that have been assigned to one or more members of the team and the assignees are currently working on completing the card (task).

### <a name="gpcomponents-review-in-progress-column"></a> **Review in progress** Column Component
The third column in the Project Board. This column is responsible for containing all cards (tasks) that a team has completed.

These cards are under the **Review in progress** column. This means that these would be cards (tasks) that have been assigned to one or more members of the team, the assignees have completed the card (task), and currently awaiting the outcome of a review.

### <a name="gpcomponents-review-approved-column"></a> **Review approved** Column Component
The fourth column in the Project Board. This column is responsible for containing all cards (tasks) that a team is actively working on.

These cards are under the **Review approved** column. This means that these would be cards (tasks) that have been assigned to one or more members of the team, the assignees have completed the card (task), and the outcome of a review was successful.

### <a name="gpcomponents-done-column"></a> **Done** Column Component
The fifth, and final, column in the Project Board. This column is responsible for containing all cards (tasks) that a team reviewer has approved.

These cards are under the **Done** column. This means that these would be cards (tasks) that have been assigned to one or more members of the team and the assignees have completed the card (task) and a reviewer approved the task's implementation.

## <a name="guidelines"></a> Guidelines
There are 4 guidelines you should always follow. Namely:

- [Card Format (Team Without Repository) Guideline](#cf-guideline)
- [Card Format (Team With Repository) Guideline](#cfr-guideline)
- [Card Assignments Guideline](#ca-guideline)
- [Card Transfer Guideline](#ct-guideline)

### <a name="cf-guideline"></a> Card Format (Team Without Repository) Guideline
Each card should have a basic format that remains consistent. Here's how a template for a team without a repository should look like:

```
<Your Task Name>
Assigned To: @<assignees-github-username>, ..., ...

<Your-Brief-Description-Of-Task>

Requirements:
<Your-Checklist>
```

The <Your-Checklist> section should be in this format for each item:

```
- [ ] Item Not Done
- [x] Item Done
```

Here is an example of a card in the format shown above.

```markdown
Create GITHUB_PROJECTS_GUIDE file for .github repo
Assigned To: @theguy

The .github repo is the entry point for all team members.
As such, the GITHUB_PROJECTS_GUIDE.md file must be created to
ensure that all members know why and how to use Projects.

Requirements:
- [x] Add overview section
- [ ] Add why github projects section
- [ ] Add github project components section
- [ ] Add guidelines section
```

### <a name="cfr-guideline"></a> Card Format (Team With Repository) Guideline
Each card should have a basic format that remains consistent. The format shown in the *Card Format (Team Without Repository)* guideline above should be also used for teams that have one or more repositories.

In addition, the cards can be linked to issues and PRs created under that team's repositories.

### <a name="ca-guideline"></a> Card Assignments Guideline
Cards should be assigned to one or more team members before being transferred to the **In progress** column.

**NOTE:** Each member of a team should be assigned to a card. You cannot do any work in the team unless you have been assigned to a card. Each assignee should focus on completing the task assigned to them.

### <a name="ct-guideline"></a> Card Transfer Guideline
Card transfers to **To Do** should occur only if a new task is required.

Card transfers to **In progress** should occur only if a card has been assigned to one or more members of the team.

Card transfers to **Review in progress** should occur only if a card has been assigned to one or more members of the team and completed.

Card transfers to **Review approved** should occur only if a card has been assigned to one or more members of the team, completed, and the reviewer is satisfied with the implementation details.

Card transfers to **Done** should occur only if a card's checklist has been completed.
