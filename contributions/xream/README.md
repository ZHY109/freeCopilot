# @xream

## 使用 Github Copilot 的经验或者建议

## 在面板中展示多条建议

`Ctrl + Enter`

### 配置在哪些文件类型使用

```JSON
{
  "github.copilot.enable": {
    "*": true,
    "yaml": true,
    "plaintext": true,
    "markdown": true,
    "javascript": true
  }
}
```


## 其他关于 Github 使用等等有意义的内容

### Github Action 中 matrix strategy 的使用示例

[实现编译不同系统/平台/Node.js 版本的产出](https://github.com/xream/Sub-Store/blob/feature/server/.github/workflows/backend.yaml)

### 一键下载 Github (子)文件夹文件

[Download github repo sub-folder](https://greasyfork.org/en/scripts/411834-download-github-repo-sub-folder)

## 有些相关的分享

### 自动根据代码生成注释

[Mintlify Doc Writer for Python, JavaScript, TypeScript, C++, PHP, Java, C#, Ruby & more](https://marketplace.visualstudio.com/items?itemName=mintlify.document)