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
     * shift + ctrl + p
     * install code
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
4. install zsh/ohmyzsh/sapceship.
   * theme dracula for terminal
   * https://blog.rocketseat.com.br/terminal-com-oh-my-zsh-spaceship-dracula-e-mais/
5. git
   * git config
     * $ git config --global user.name "John Doe"
     * $ git config --global user.email johndoe@example.com
   * cd ~
     * code .gitconfig
```
     [alias]
  ci = commit
  co = checkout
  cm = checkout master
  cb = checkout -b
  st = status -sb
  sf = show --name-only
  lg = log --pretty=format:'%Cred%h%Creset %C(bold)%cr%Creset %Cgreen<%an>%Creset %s' --max-count=30
  incoming = !(git fetch --quiet && git log --pretty=format:'%C(yellow)%h %C(white)- %C(red)%an %C(white)- %C(cyan)%d%Creset %s %C(white)- %ar%Creset' ..@{u})
  outgoing = !(git fetch --quiet && git log --pretty=format:'%C(yellow)%h %C(white)- %C(red)%an %C(white)- %C(cyan)%d%Creset %s %C(white)- %ar%Creset' @{u}..)
  unstage = reset HEAD --
  undo = checkout --
  rollback = reset --soft HEAD~1
```
  
     

