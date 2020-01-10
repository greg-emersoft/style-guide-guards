# style-guide-guards

#### Features:

1. Stylelint
2. Prettier for CSS, HTML and Typescript/JavaScript
3. Husky

## IDE CONFIGURATION

Project uses `Prettier` for code formatting.

#### SCSS configuration:

`.stylelintrc.yml` contains all rules used to format SCSS code.

##### Visual Studio Code:

Install following plugins:

- Prettier (https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- PostCSS Sorting (https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-postcss-sorting)

All the plugins configuration is already included to the repo and can be found in `.vscode/settings.json`

You can additionally add keyboard shortcut to your `keybindings.json` file:

```json
{
  "key": "ctrl+shift+c",
  "command": "postcssSorting.execute"
}
```

---

##### IntelliJ

Install `Prettier` plugin.

Add `'order/properties-order'` array from `.stylelintrc.yml` to:

```text
Settings / Editor / Code Style / Style sheets / SCSS / Arrangement / Custom order
```

You're ready to go!!
