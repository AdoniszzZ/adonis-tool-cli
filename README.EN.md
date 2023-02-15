English | [简体中文](./README.md)

<p align="center"><img width="100" src="https://vuejs.org/images/logo.png"></p>

<h2 align="center">adonis-demo-cli（A simple front-end CLI tool）</h2>
<p align="center"><b>Generate personal front-end scaffolding based on Node construction（vue）</b></p>
# 目录

- [feature](#feature)
- [QuickStart](#QuickStart)
  - [Install](#Install)
  - [Usage](#Usage)
- [Contribution](#Contribution)
- [Maintainers](#Maintainers)
- [License](#license)

### feature

- Easy to use
- Support custom template addition and deletion

### QuickStart

### Install

```bash
$ npm i adonis-demo-cli -g               # install cli
$ omi init my-app     # init project, you can also exec 'omi init' in an empty folder
$ cd my-app           # please ignore this command if you executed 'omi init' in an empty folder
$ tool init [templateName] [yourProjectName]
```

Install description:

The default scaffolding template name is vue-admin

> tool init vue-admin [yourProjectName]

### New template usage

```bash
tool add
# Select template and template address (github address)
```

![tool-add](./img/readme_add.png)

-Note: The template address is the git repository name. The master branch is pulled by default.
If you want to specify a branch, please use **owner / name # my-branch**
![tool-add](./img/readme_gitAddress.png)

### Remove template usage

```bash
tool delete
# 选择模板
```

![tool-add](./img/readme_delete.png)

### See all template usage

```bash
tool list
```

### Initialize project scaffolding usage

```bash
tool init 或者 tool init [templateName] [yourProjectName]
```

![tool-add](./img/readme_init.png)

## Contribution

- BigSharkLx

## Maintainers

- [BigSharkLx](https://github.com/BigSharkLx)

## License

- [MIT](https://opensource.org/licenses/MIT)
