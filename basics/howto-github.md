# How to work with Github

## Bootstrap
We put an extensive README.MD file with a brief project description and how to start working with the current project guide. It makes sense to outline possible OS-dependent nuances (Mac vs Linux vs Windows instructions), time-consuming processes, etc.
A newcomer should be able to launch a local development environment easily with just a few commands.

## Branching
We stick to standard development workflow inspired by Gitflow [Link 1](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow), [Link 2](https://nvie.com/posts/a-successful-git-branching-model/)
Teams are responsible to follow best practices but able to slightly modify rules having a vague reason for that.

## Code Review
As part of GitFlow we do code review. Short lsit of best practices:
 - put a JIRA ticket reference into PR title to help find a corresponded JIRA ticket;
 - put meangful description of what changed, and why it is implemented like that if that is not obvious;
 - if that GUI change - please put screenshots of how it looked before and after the change;
 - the author of PR should keep changes small and relevant to the ticket to help reviewers to run fast throught changes;
    - If there are changes that are not related to the ticket's goal, then reviewer might request to create a separate PR to simplify review and to avoid extra risk merging that PR;
    - If there are plenty of changes, for instance after mass rename action, author should mention what changes can be skipped and what should gain more attention from reviewers. Github has comments feature for this.

https://docs.google.com/presentation/d/1rJuyPNr3zpqy08R70jItQYCcLfIKpEottUp7bILMp2g/edit#slide=id.p

## Dealing with credentials or sensitive data
Global practice is not to put credentials to repo. However we split credentials in 2 types: production ones and development ones. For operational simplicity reason,  if that didn't conflict with GDPR or data security, development credentials can be put into repository. In that way it could be easier to onboard newscomers and switch between projects.
Projection credentials should never be put into code repository or JIRA. Use private slack channels or LastPass for that.
# How to work with Github

## Bootstrap
We put an extensive README.MD file with a brief project description and how to start working with the current project guide. It makes sense to outline possible OS-dependent nuances (Mac vs Linux vs Windows instructions), time-consuming processes, etc.
A newcomer should be able to launch a local development environment easily with just a few commands.

## Branching
We stick to standard development workflow inspired by Gitflow [Link 1](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow), [Link 2](https://nvie.com/posts/a-successful-git-branching-model/)
Teams are responsible to follow best practices but able to slightly modify rules having a vague reason for that.

## Code Review
As part of GitFlow we do code review. Short lsit of best practices:
 - put meangful description of what changed, and why it is implemented like that if that is not obvious;
 - if that GUI change - please put screenshots of how it looked before and after the change;
 - the author of PR should keep changes small and relevant to the ticket to help reviewers to run fast throught changes. 
    - If there are changes that are not related to the ticket's goal, then reviewer might request to create a separate PR to simplify review and to avoid extra risk merging that PR. 
    - If there are plenty of changes, for instance after mass rename action, author should mention what changes can be skipped and what should gain more attention from reviewers. Github has comments feature for this.
https://docs.google.com/presentation/d/1rJuyPNr3zpqy08R70jItQYCcLfIKpEottUp7bILMp2g/edit#slide=id.p

## Dealing with credentials or sensual data
The global practice is not to put credentials to the repo. However, we split credentials into 2 types: production ones and development ones. For operational simplicity reason,  if that didn't conflict with GDPR or data security, development credentials can be put into the repository. In that way, it could be easier to onboard newcomers and switch between projects. 
Production env credentials should never be put into code repository or JIRA. Use private slack channels or LastPass for that.
