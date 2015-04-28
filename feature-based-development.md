Feature based development pitfalls and possibilities
===
Speaker: Kai Kroker  
Twitter: @nohypeactivist  
Date of the talk: 2015-04-26

Kai and his team are using the extended gitflow plus naming conventions for their projects. This syntax is based on the standard syntax a `master` and a `development` branch. When starting a feature, a `feature/feature-name` branch is created and later merged back to `development`. For bugfixing rounds, a `bugfix/bug-name` branch can be created based on `development`.

The `support` branch is used for outdated major packages, which at one point of the project got updated. If these packages for some reasons still need to be supported, the `support/supported-version` branch can be used. This branch will never be merged back to develop or even production. If ever, compatible patches can be merged in to the support brach or hotfixes for this branch can be created.

Looking at the toolstack, they are using the Jira Git Essentials: Jira + Agile, Stash and Bamboo. For bigger teams this is an expensive investment, but Kai says it's worth it. For open source projects it's free. Alternatives are numerous, here are a few: Trello, Mantis, Redmine, Gitlab, Github, Jenkins CI and Travis CI.

Some tips and pitfalls:
- Merge regularly
- Merge `development` into `feature/x` before integration
- Slice big stories in small chunks
- Push all branches to remote (for home office, sick leave, ...)