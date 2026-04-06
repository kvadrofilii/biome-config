# Biome config

Личная конфигурация в npm-пакете.

## Установка

```sh
npm install --save-dev @michael-yakovlev/biome-config
```

## Настройка VSCode

Чтобы использовать "Biome" в VSCode нужно установить плагин [Biome Extension for VS Code](https://marketplace.visualstudio.com/items?itemName=biomejs.biome):

Откройте файл .vscode/settings.json и добавьте настройки:

```json
{
  "editor.codeActionsOnSave": {
    "source.fixAll.biome": "explicit",
    "source.organizeImports.biome": "explicit"
  },
  "editor.defaultFormatter": "biomejs.biome",
  "editor.formatOnSave": true
}
```
