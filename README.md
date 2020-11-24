# sandbox

```jsonc:.vscode/settings.jsonc
// .vscode/settings.jsonc
{
    // Unresolved import warnings
    // https://stackoverflow.com/a/57669739/9316234
    "python.autoComplete.extraPaths": [
        "${workspaceFolder}/src"
    ],
    "python.linting.lintOnSave": true,
    "python.linting.pylintEnabled": false,
    "python.linting.pycodestyleEnabled": false,
    "python.linting.flake8Enabled": true,
    "python.formatting.provider": "black",
    "[python]": {
        "editor.tabSize": 4,
        "editor.formatOnSave": true,
        "editor.codeActionsOnSave": {
            "source.organizeImports": true
        },
    },
}
```
