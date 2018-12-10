
# Git提交规范

修改的摘要（50 个字符或更少） 如果必要的话，加入更详细的解释文字。在 大概 72 个字符的时候换行。在某些情形下， 第一行被当作一封电子邮件的标题，剩下的 文本作为正文。分隔摘要与正文的空行是 必须的（除非你完全省略正文）；如果你将 两者混在一起，那么类似变基等工具无法 正常工作。 空行接着更进一步的段落。   - 句号也是可以的。   - 项目符号可以使用典型的连字符或星号     前面一个空格，之间用空行隔开，     但是可以依据不同的惯例有所不同。 


```
[<Type>[(<Scope>)]: ]<Subject> #<Issue> !<MergeRequest>
[空行]
[Body]
```
### Type(目前本人用到的)
- feat：新功能（feature）
- fix：修补bug
- docs：文档（documentation）
- lint(style)： 格式（不影响代码运行的变动）
- refactor：重构（即不是新增功能，也不是修改bug的代码变动）
- test：增加测试
- chore：构建过程或辅助工具的变动
- revert: feat(pencil): add 'graphiteWidth' option (撤销之前的commit)

[以下代码引用自github/commitizen](https://github.com/commitizen/conventional-commit-types/blob/master/index.json)
```
{
  "types": {
    "feat": {
      "description": "A new feature",
      "title": "Features"
    },
    "fix": {
      "description": "A bug fix",
      "title": "Bug Fixes"
    },
    "docs": {
      "description": "Documentation only changes",
      "title": "Documentation"
    },
    "style": {
      "description": "Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)",
      "title": "Styles"
    },
    "refactor": {
      "description": "A code change that neither fixes a bug nor adds a feature",
      "title": "Code Refactoring"
    },
    "perf": {
      "description": "A code change that improves performance",
      "title": "Performance Improvements"
    },
    "test": {
      "description": "Adding missing tests or correcting existing tests",
      "title": "Tests"
    },
    "build": {
      "description": "Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)",
      "title": "Builds"
    },
    "ci": {
      "description": "Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs)",
      "title": "Continuous Integrations"
    },
    "chore": {
      "description": "Other changes that don't modify src or test files",
      "title": "Chores"
    },
    "revert": {
      "description": "Reverts a previous commit",
      "title": "Reverts"
    }
  }
}
```

### Scope
操作范围

### Issue
提交针对的问题

### MergeRequest
MR号

### Subject
你的commit主题

### Body
commit内容
