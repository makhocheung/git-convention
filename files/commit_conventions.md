```
<type>: <subject>
// 空一行
<body>
```
### type(目前本人用到的)
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

### subject
> 你的commit主题

### body
> commit内容