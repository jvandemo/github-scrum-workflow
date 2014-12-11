# GitHub scrum workflow

This workflow allows you to turn any GitHub repository into a simple but powerful agile work environment.

## How it works

- items are reported as **issues**
- points and meta data are assigned to items as **labels**
- **milestones** are used to group issues in sprints

## Issues

To create a new backlog item, just create a new issue.

Once a new issue has been created, assign it the right labels and/or assign it to a sprint (milestone).

Issues allow you to have a conversation about the item and even allow you to create task lists inside the issue using [GitHub's markdown](https://guides.github.com/features/mastering-markdown/).

## Labels

Add the following labels to your repository:

### Priorities

`priority` labels allow you to prioritize items in your backlog:

- `priority: lowest`
- `priority: low`
- `priority: medium`
- `priority: high`
- `priority: highest`

### Points

`point` labels allow you to to assign velocity points to individual items (issues) e.g.:

- `point: 1`
- `point: 2`
- `point: 3`
- `point: 5`
- `point: 8`
- `point: 13`
- `point: 21`

### Types

`type` labels allow you to easily filter items (issues) in the dashboard:

- `type:bug`: bug
- `type:chore`: chore, maintenance work
- `type:feature`: new feature
- `type:infrastructure`: infrastructure related
- `type:performance`: performance related
- `type:refactor`: refactor
- `type:test`: test related

## Milestones

You can create a milestone for every sprint and add items (issues) from the backlog to a milestone.

This allows you to group items in sprints and track them by milestone in the issue dashboard.

Your backlog then consists of all items (issues) that have no `milestone` attached to it.
