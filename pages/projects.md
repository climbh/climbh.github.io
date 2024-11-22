---
title: Projects - ClimbH
display: Projects
description: 我的一些开源项目
wrapperClass: 'text-center'
art: dots
projects:
  Current Focus:
    - name: 'ClimbH.me'
      link: 'https://github.com/climbh/climbh.github.io'
      desc: 'My personal website'
      icon: 'i-tabler:brand-blogger'

  VS Code:
    - name: 'Srttings Json Config'
      link: 'https://github.com/climbh/vscode-setting-json-config'
      desc: '自定义.vscode/settings.json文件配置预设，一键合并'
      icon: 'i-ion:code-working'
  Favorite Project:
    - name: 'Rough Notation'
      link: 'https://github.com/rough-stuff/rough-notation'
      desc: 'Create and animate hand-drawn annotations on a web page'
      icon: 'i-la:brush'

    - name: 'eslint-config'
      link: 'https://github.com/antfu/eslint-config'
      desc: 'My ESLint config presets'
      icon: 'af'

    - name: 'vscode-file-nesting-config'
      link: 'https://github.com/antfu/vscode-file-nesting-config'
      desc: 'Config of File Nesting for VS Code'
      icon: 'i-carbon:tree-view-alt'

---

<!-- @layout-full-width -->

<ListProjects :projects="frontmatter.projects" />
