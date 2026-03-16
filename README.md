# ~ startpage

> 🇧🇷 [Português](#português) · 🇺🇸 [English](#english)

---

## Português

Startpage pessoal para navegador, feita com HTML, CSS e JS puro — sem frameworks, sem dependências, arquivo único.

### Funcionalidades

**Links & categorias**
- Organize links em categorias personalizadas
- Cada link tem nome, URL e um ícone SVG monocromático escolhido de uma biblioteca com 74 ícones
- Adicione, renomeie ou remova categorias e links a qualquer momento pelo painel de configurações

**Temas**
- 9 temas prontos: Custom, Dark, Light, Nord, Rosé Pine, Catppuccin, Gruvbox, Everforest e Dracula
- O tema Custom permite personalizar a cor de fundo via color picker ou valor hex
- A cor do texto dos botões se adapta automaticamente com base na luminosidade do acento

**Aparência**
- Tamanho dos links ajustável por slider (0.70rem – 1.20rem, padrão 0.88rem)
- Todas as configurações são salvas no `localStorage`

**Sincronização**
- Exporte todas as configurações (links, categorias, tema, tamanho de fonte) para um arquivo `.json`
- Importe um `.json` exportado anteriormente para restaurar tudo instantaneamente
- Ideal para manter múltiplos dispositivos sincronizados

### Como usar

Abra o `startpage.html` diretamente no navegador, ou hospede no GitHub Pages e aponte a nova aba para ele usando a extensão **New Tab Override**.

**Configurar como nova aba (Firefox / Zen Browser)**

1. Instale o [New Tab Override](https://addons.mozilla.org/en-US/firefox/addon/new-tab-override/)
2. Abra as configurações da extensão
3. Insira a URL do GitHub Pages:
   ```
   https://seuusuario.github.io/startpage
   ```

**Sincronizar entre dispositivos**

1. Abra as configurações (ícone ⚙ no canto superior esquerdo)
2. Vá até a aba **sincronizar**
3. No primeiro dispositivo: clique em **exportar JSON** para baixar suas configs
4. No segundo dispositivo: clique em **importar JSON** e selecione o arquivo baixado

### Tecnologias

- HTML / CSS / JS puro — sem build, sem dependências
- Fontes: [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) + [Syne](https://fonts.google.com/specimen/Syne) via Google Fonts
- Ícones: paths SVG customizados baseados no [Lucide](https://lucide.dev)
- Persistência: `localStorage`

---

## English

Personal browser startpage built with vanilla HTML, CSS and JS — no frameworks, no dependencies, single file.

### Features

**Links & categories**
- Organize links into custom categories
- Each link has a name, URL and a monochromatic SVG icon chosen from a library of 74 icons
- Add, rename or remove categories and links at any time through the settings panel

**Themes**
- 9 built-in themes: Custom, Dark, Light, Nord, Rosé Pine, Catppuccin, Gruvbox, Everforest and Dracula
- Custom theme supports a fully personalized background color via color picker or hex input
- Button text color automatically adapts based on the accent color luminance

**Appearance**
- Adjustable link font size via slider (0.70rem – 1.20rem, default 0.88rem)
- All settings persist in `localStorage`

**Sync**
- Export all settings (links, categories, theme, font size) to a `.json` file
- Import a previously exported `.json` to restore everything instantly
- Useful for keeping multiple devices in sync

### Usage

Open `startpage.html` directly in any browser, or host it on GitHub Pages and point your new tab to it using the **New Tab Override** extension.

**Setting as new tab (Firefox / Zen Browser)**

1. Install [New Tab Override](https://addons.mozilla.org/en-US/firefox/addon/new-tab-override/)
2. Open the extension settings
3. Set the URL to your GitHub Pages address:
   ```
   https://yourusername.github.io/startpage
   ```

**Syncing between devices**

1. Open settings (⚙ gear icon, top-left corner)
2. Go to the **sincronizar** tab
3. On the first device: click **exportar JSON** to download your config
4. On the second device: click **importar JSON** and select the downloaded file

### Stack

- HTML / CSS / JS — no build step, no dependencies
- Fonts: [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) + [Syne](https://fonts.google.com/specimen/Syne) via Google Fonts
- Icons: custom SVG paths based on [Lucide](https://lucide.dev)
- Storage: `localStorage` for persistence
