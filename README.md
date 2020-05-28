# iOs-MAC-Config

1. Install nvm (<https://github.com/nvm-sh/nvm>) 
- Node version module manager versions node.
   * curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
   * export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm
   * nvm install --lts
   * nvm use --lts
2. Install Yarn (<https://classic.yarnpkg.com/pt-BR/docs/install/#windows-stable>)
   * npm install -g yarn
4. Instal font Fire-Code
   * 
3. Install Visual Code (<https://code.visualstudio.com/download>)
   * install download
   * add varaible envoriment
     * 
   * Extensions
     * Dracula Theme ()
     * Material Icon Theme
   * Configs
   ```json
      {
          // Define o tema do VsCode 
          "workbench.colorTheme": "Dracula",
          
          // Aumenta a fonte do terminal
          "terminal.integrated.fontSize":14,
          
          // Define o tema dos icones na sidebar
          "workbench.iconTheme": "material-icon-theme",
          
          //Configura tamanho e familia da fonte
          "editor.fontFamily": "Fira Code",
          "editor.tabSize":2,
          "editor.fontSize":18,
          "editor.lineHeight":24,
          "editor.fontFamily":"Fira Code",
          "editor.fontLigatures": true,
          
          "explorer.compactFolders":false,
          "editor.renderLineHighlight":"gutter",
          "workbench.editor.labelFormat":"short",
          "extensions.ignoreRecommendations":true,
          
          "javascript.updateImportsOnFileMove.enable":"never",
          "typescript.updateImportsOnFileMove.enable":"never",
          
          "breadcrumbs.enabled":true,
          "explorer.confirmDragAndDrop":false,
          "explorer.confirmDelete":false,
          "eslint.packageManager": "yarn",
          "editor.rulers": [
              80,
              120
          ],
          "[javascript]":{
              "editor.codeActionsOnSave": {
                "source.fixAll.eslint": true,
              }
            },
            "[javascriptreact]":{
              "editor.codeActionsOnSave":{
                "source.fixAll.eslint":true,
              }
            },
            "[typescript]": {
                "editor.codeActionsOnSave": {
                    "source.fixAll.eslint":true
                }
            },
            "[typescriptreact]": {
              "editor.codeActionsOnSave": {
                  "source.fixAll.eslint":true
              }
          },
          "files.associations": {
              ".sequelizerc":"javscript",
              ".stylelintrc":"json",
              ".prettierrc":"json"
          },
          "editor.tabSize": 2,
          "editor.renderLineHighlight": "gutter",
          "terminal.integrated.fontSize": 14,
          "emmet.syntaxProfiles": {
              "javascript": "jsx"
          },
          "emmet.includeLanguages": {
              "javascript": "javascriptreact"
          },
          "material-icon-theme.folders.associations":{
              "infra":"app",
              "entities":"class",
              "schemas":"class",
              "typeorm":"database",
              "repositories":"mappings",
              "http":"container",
              "migrations":"tools",
              "modules":"components",
              "implementations":"core",
              "dtos":"typescript",
              "fakes":"mock"
          },
          "javascript.updateImportsOnFileMove.enabled": "never",
          "breadcrumbs.enabled": true,
          "workbench.editor.enablePreview": false,
          "workbench.editor.enablePreviewFromQuickOpen": false,
          "window.zoomLevel": 0,
          "editor.codeActionsOnSave": {
              "source.fixAll.eslint": true
          },
          "editor.minimap.enabled": true,
          "editor.renderWhitespace": "all",
          "editor.renderControlCharacters": false,
          "explorer.compactFolders": false,
          
      }
    ```
  *
 
