# @startlinks/prettier-config

[![npm](https://img.shields.io/npm/v/@startlinks/prettier-config?style=flat&color=f03e3e)](https://npmjs.com/package/@startlinks/prettier-config)
[![star](https://img.shields.io/github/stars/startlinks/prettier-config?style=flat&color=1c7ed6)](https://github.com/startlinks/prettier-config)
[![license](https://img.shields.io/npm/l/@startlinks/prettier-config?style=flat&color=37b24d)](https://github.com/startlinks/prettier-config/blob/main/LICENSE)
[![language](https://img.shields.io/badge/language-简体中文-f76707)](https://github.com/startlinks/prettier-config)

My personal Prettier config ( 我的 Prettier 配置 )

## Configs ( 配置 )

- No semi ( 不使用分号 )
- Use single quotes ( 使用单引号 )
- Ignore space around HTML tags ( 忽略 HTML 标签周围空格 )
- Ignore `pnpm-lock.yaml` file ( 忽略 `pnpm-lock.yaml` 文件 )

## Install ( 安装 )

```bash
pnpm i -D @startlinks/prettier-config
```

## Usage ( 使用 )

Edit `package.json` ( 编辑 `package.json` )

```jsonc
{
  "scripts": {
    "format": "prettier --cache --write .",
  },
  "prettier": "@startlinks/prettier-config",
}
```

Edit `Visual Studio Code` Setting ( 编辑 `Visual Studio Code` 设置 )

```json
{
  "[vue]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[markdown]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  }
}
```
