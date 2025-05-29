# Python settings

```json
{
  // General settings
  "editor.fontSize": 15,
  "editor.cursorBlinking": "expand",
  "editor.cursorSmoothCaretAnimation": "on",
  "files.autoSave": "afterDelay",

  // Exact python settings
  "ruff.configuration": "",
  "editor.defaultFormatter": "charliermarsh.ruff",
  "python.analysis.typeCheckingMode": "basic",
  "git.autoRepositoryDetection": true,
  "breadcrumbs.enabled": true,
  "python.languageServer": "Pylance",
  "python.analysis.autoSearchPaths": true,
  "python.analysis.autoImportCompletions": true,
  "python.analysis.inlayHints.functionReturnTypes": true,
  "python.analysis.inlayHints.variableTypes": false,
  "python.analysis.packageIndexDepths": [
    {
      "name": "django",
      "depth": 3,
      "includeAllSymbols": true
    },
    {
      "name": "rest_framework",
      "depth": 2,
      "includeAllSymbols": true
    }
  ],
  "files.exclude": {
        "**/__pycache__/": true
  }
}
```

> ⭐ `settings.json`

<br>

``` toml
line-length = 88

[format]
quote-style = "single"

[per-file-ignores]
"__init__.py" = ["F401"]

```
> ⭐ `ruff.toml` | `Pyproject.toml`

## Extention list

- Jetbrains Keymap
- Ruff
- Python, Pylance ...
- Error Lens
- GitLens
- Django
- SqliteViewer (maybe)

  <br>

- Material icons
- Github / Gruvbox / Atom Themes
