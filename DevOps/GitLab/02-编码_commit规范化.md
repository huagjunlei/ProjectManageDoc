# 编码commit 提交规范

## 需求

## 候选方案

## 参考链接

* <https://www.jianshu.com/p/d264f88d13a4>
* <https://docs.gitlab.com/ee/administration/custom_hooks.html>
* <https://mritd.me/2018/05/11/add-commit-message-style-check-to-your-gitlab/>
* <https://cloud.tencent.com/developer/article/1328117>
* <https://github.com/angular/angular.js/blob/master/DEVELOPERS.md#commits>

## 附：Git Commit Guidelines

```md
We have very precise rules over how our git commit messages can be formatted. This leads to more readable messages that are easy to follow when looking through the project history. But also, we use the git commit messages to generate the AngularJS change log.

The commit message formatting can be added using a typical git workflow or through the use of a CLI wizard (Commitizen). To use the wizard, run yarn run commit in your terminal after staging your changes in git.

Commit Message Format
Each commit message consists of a header, a body and a footer. The header has a special format that includes a type, a scope and a subject:

<type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
The header is mandatory and the scope of the header is optional.

Any line of the commit message cannot be longer 100 characters! This allows the message to be easier to read on GitHub as well as in various git tools.

Revert
If the commit reverts a previous commit, it should begin with revert: , followed by the header of the reverted commit. In the body it should say: This reverts commit <hash>., where the hash is the SHA of the commit being reverted.

Type
Must be one of the following:

feat: A new feature
fix: A bug fix
docs: Documentation only changes
style: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
refactor: A code change that neither fixes a bug nor adds a feature
perf: A code change that improves performance
test: Adding missing or correcting existing tests
chore: Changes to the build process or auxiliary tools and libraries such as documentation generation
Scope
The scope could be anything specifying place of the commit change. For example $location, $browser, $compile, $rootScope, ngHref, ngClick, ngView, etc...

You can use * when the change affects more than a single scope.

Subject
The subject contains succinct description of the change:

use the imperative, present tense: "change" not "changed" nor "changes"
don't capitalize first letter
no dot (.) at the end
Body
Just as in the subject, use the imperative, present tense: "change" not "changed" nor "changes". The body should include the motivation for the change and contrast this with previous behavior.

Footer
The footer should contain any information about Breaking Changes and is also the place to reference GitHub issues that this commit closes.

Breaking Changes should start with the word BREAKING CHANGE: with a space or two newlines. The rest of the commit message is then used for this.

A detailed explanation can be found in this document.
```