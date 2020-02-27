## Introduction

These are the bus-stop organization issue templates.


## Usage

To use these templates within the bus-stop organization, do the following.

1. On your project directory create an empty `.github` directory
2. Create the following labels in you project label editor
   https://github.com/bus-stop/:project-name/labels

   Copy the complete label name and paste as new label name in your editor

   `bug report :bug:`<br>
   `feature request :heart_eyes:`<br>
   `inquiry :question:`<br>

You can pick any color you prefer but there are preset colors, see below:

### Issue labels available

We have new preset labels that will automatically be added to any newly created org repository.
These wont magically appear in existing repositories, though, so here is a key to add them:


| Label name                        | Description                                | Color   |
| :-------------------------------- | :----------------------------------------- | :-----: |
| `beta :sparkles:`                 | Something is beta in this issue            | #aa3322 |
| `bug fix :space_invader:`         | When something is being fixed              | #cccccc |
| `bug report :bug:`                | When something isn't working               | #bb0000 |
| `documentation :memo:`            | Improvements or additions to documentation | #0075ca |
| `duplicate :sheep::sheep:`        | This issue or pull request already exists  | #554444 |
| `enhancement :gear:`              | Improvements or feature being added        | #3d6fc6 |
| `external :outbox_tray:`          | This issue is external to the project      | #dd89c3 |
| `feature request :heart_eyes:`    | Some feature could be added                | #447733 |
| `good first issue :bee:`          | Good for newcomers                         | #770055 |
| `help-wanted :sos:`               | Extra attention or help is needed          | #eeaaaa |
| `question :question:`             | Further information is requested           | #bbbbcc |
| `invalid :no_entry_sign:`         | Invalid issue or pull request              | #e4e669 |
| `linux :penguin:`                 | A Linux issue is loose                     | #dbdbdb |
| `macOS :green_apple:`             | A macOS issue is loose                     | #dbdbdb |
| `waiting on user feedback :mega:` | When waiting for a reply from user         | #bbcc44 |
| `windows :door:`                  | A Windows issue is loose                   | #dbdbdb |
| `W.I.P. :construction:`           | In progress and not ready for merging      | #666666 |
| `wontfix :cry:`                   | This will not be worked on                 | #555555 |
| `unable to duplicate !!`          | When the issue cannot be duplicated        | #ffcc33 |
| `confirmed issue !!`              | When the issue is known or duplicated      | #335533 |

### Known GitHub issues:

1. When a external user to project posts an issue and you add a label,
the users automated label will be removed, please re-add it.

See issue talk at https://github.com/StylishThemes/.github/issues/4

2. Disallowing blank issues via `config.yml` -> `blank_issue_enabled: false` does not work,
either at org or local level.

### What are the Issue label prefixes and are they for
I mean we already use labels right?

These are fallbacks for the [known issue #1](#known-github-issues) above
In case people don't realize it and are not adding the labels removed by issue back. 


`[BR]` Bug report
`[FR]` Feature request
`[IR]` Information request (inquiry)
