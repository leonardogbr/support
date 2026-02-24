# Support & FAQ

Support and FAQ pages for LLabs Corp apps. Hosted on GitHub Pages.

## URLs (após ativar GitHub Pages)

- **Índice (todos os apps):** `https://[USUARIO].github.io/support/`
- **One Tap Dodge:** `https://[USUARIO].github.io/support/onetapdodge/`

Use a URL do app específico (ex.: `/support/onetapdodge/`) no **Support URL** do App Store Connect.

## Configuração

Se seu usuário GitHub for diferente, atualize as URLs da Privacy Policy em `onetapdodge/index.html`.

## Adicionar um novo app

1. Crie a pasta `[nome-do-app]/` (ex.: `meu-app/`)
2. Adicione `index.html` dentro dela com a FAQ e informações de contato (siga o template do `onetapdodge/`)
3. Adicione o link na `index.html` da raiz:

   ```html
   <li><a href="./meu-app/">Meu App</a></li>
   ```

4. Commit e push

## Ativar GitHub Pages

1. Settings → Pages
2. Source: **Deploy from a branch**
3. Branch: **main** (ou **master**), Folder: **/ (root)**
4. Save

## Estrutura

```
support/
├── .nojekyll
├── index.html          # Lista de apps
├── README.md
└── onetapdodge/
    └── index.html      # FAQ + contato do One Tap Dodge
```
