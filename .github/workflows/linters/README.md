## Linter actions
This folder contains the actions that can be used to lint files automatically.

### Lint commit message
This action lints commit name with [Conventional Commits](https://www.conventionalcommits.org) rules and fails if not following it.

#### Links
- [Action](./lint-commit-message.yml)

#### Source
- [wagoid/commitlint-github-action : OSS(MIT)](https://github.com/wagoid/commitlint-github-action)
- [conventional-changelog/commitlint : OSS(MIT)](https://github.com/conventional-changelog/commitlint)
- [@commitlint/config-conventional(default settings)](https://github.com/conventional-changelog/commitlint/tree/master/%40commitlint/config-conventional)
- [commitlint の紹介 : @ybiquitous / Qiita](https://qiita.com/ybiquitous/items/74225bc4bf0a9ddcd7dd)


### Lint pull request title
This action lints pull request title with [Conventional Commits](https://www.conventionalcommits.org) and fails if something is not valid.

#### Links
- [Action](./lint-pr-title.yml)

#### Source
- [amannn/action-semantic-pull-request : OSS(MIT)](https://github.com/amannn/action-semantic-pull-request)


### Lint target branch
This action lint the pull request target branch is not main. If the pull request target is main and not by moderator, it just fails.

#### Links
- [Action](./lint-target-branch.yml)

#### Source
- [superbrothers/close-pull-request : OSS(MIT)](https://github.com/superbrothers/close-pull-request)


### Scan with codeQL
This action scan the pull request with [codeQL](https://codeql.github.com/) and fails if something is not valid.

#### Links
- [Action](./scan-with-codeql.yml)

#### Source
- [CodeQL](https://codeql.github.com/)


### Reviewdog actions
Reviewdog is linter output tool. It posts lint result as a review at pull request. At reviewdog folder, there are many linters runs with this. But I'm sorry but they are too many and I put all sources at here.

#### Source
- [hadolint/hadolint-action : OSS(MIT)](https://github.com/hadolint/hadolint-action)
- [hadolint/hadolint : OSS(GPLv3)](https://github.com/hadolint/hadolint)
- [hadolintを利用して容易にベストプラクティスに基づいたDocker環境を構築する : @t_o_d / DevelopersIO](https://dev.classmethod.jp/articles/hadolint-docker/)
- [あなたのDockerfileはベストプラクティスに従っていますか？(ベストプラクティスとチェックツール) : @yoshii0110 / Qiita](https://qiita.com/yoshii0110/items/0accb7f21fa1c375e0d7)
- [DavidAnson/markdownlint : OSS(MIT)](https://github.com/DavidAnson/markdownlint)
- [nosborn/github-action-markdown-cli : OSS(MIT)](https://github.com/nosborn/github-action-markdown-cli)
- [TODO: Add more sources...](#)