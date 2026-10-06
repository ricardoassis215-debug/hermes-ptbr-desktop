# Hermes Desktop — Português (Brasil)

Pacote de idioma pt-BR para **todo** o Hermes Desktop (4.924 textos: configurações, menus, chat, voz, Kanban…).
Funciona com qualquer conexão — Hermes local **ou** remoto (VPS) — porque é registrado no próprio app.

## Instalar

Hermes Desktop → **Capabilities → Plugins → Install from Git**, cole:

```
https://github.com/ricardoassis215-debug/hermes-ptbr-desktop
```

marque a parte *Desktop UI* e confirme. Depois: **Settings → Appearance → Language → Português (Brasil)**.

Manual (Windows): copie `plugin.js` para `%LOCALAPPDATA%\hermes\desktop-plugins\hermes-ptbr-desktop\plugin.js`.

## Como funciona

`plugin.js` chama `ctx.i18n.registerAppLocale('pt', { translations })` (SDK oficial `@hermes/plugin-sdk`).
Textos que faltarem caem no inglês, nunca em chave crua. Só tradução, nenhum código de funcionalidade.

Licença MIT.
