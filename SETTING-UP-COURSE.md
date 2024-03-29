# Setting up the Bioinformatics course assignments

The following instructions inform trainers on how to set up the course environment using assignments from GitHub and GitHub classroom.

Note that we also invite students to a communications channel (e.g. Slack) where teaching assistents are available for any questions.

## Creating a GitHub organization

1. Follow the [GitHub instructions](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/creating-a-new-organization-from-scratch) to create an organization for your course

2. Fork five assignment repositories to your organization.
![](screenshots/fork-assignments.png)

3. Make sure they are set to PUBLIC TEMPLATE.
![](screenshots/public-tempate.png)

## Distributing assignments on GitHub Classroom

1. Create GitHub classroom account with your personal Github account.

2. Create a new classroom within your GitHub organization (and name it accordingly)
![](screenshots/create-classroom.png)

3. Create each assignment individually
![](screenshots/create-assignment.png)

4. Set assignment name, deadline and template accordingly.
![](screenshots/assignment-details.png)

## Distributing the assignment

1. Distribute the assignment link to trainees.
![](screenshots/distribute-assignments.png)


2. Trainees click on the link that creates a PRIVATE repository that is a copy of the template. Repositories are created in the organization of the assignment.
![](screenshots/accept-assignment.png)


3. Trainees only have to push their code and solutions to their repository

## Assignment grading

1. Trainers can fetch all private repositories in the organization using GitHub CLI.
```
gh classroom clone student-repos
```

Check [GitHub CLI instructions](https://docs.github.com/en/education/manage-coursework-with-github-classroom/teach-with-github-classroom/using-github-classroom-with-github-cli) for more information.