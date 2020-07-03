# My shareable prettier config

## Install

- Create a `.npmrc` file and add this line:

```
registry=https://npm.pkg.github.com/OWNER
```

and replace `OWNER` with your Github's username.

- Run

```bash
npm i -D @lednhatkhanh/prettier-config
```

- Add a `.prettierrc` file and add:

```
"@lednhatkhanh/prettier-config"
```

- Create `.vscode/settings.json` file and add:

```json
{
  "editor.formatOnSave": true
}
```
