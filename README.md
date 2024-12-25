# config_vsCode

{
  // Tema e Aparência
  "workbench.colorTheme": "Dracula Theme",                    // Tema escuro popular e agradável aos olhos
  "workbench.iconTheme": "material-icon-theme",              // Ícones mais intuitivos para diferentes tipos de arquivo
  
  // Performance e Otimização
  "editor.minimap.enabled": false,                           // Desativa minimap para melhor performance
  "editor.renderWhitespace": "selection",                    // Mostra espaços em branco apenas na seleção
  "editor.smoothScrolling": true,                            // Rolagem suave para melhor experiência
  "workbench.list.smoothScrolling": true,                    // Rolagem suave em listas
  "editor.cursorSmoothCaretAnimation": "on",                // Animação suave do cursor

  // Formatação e Salvamento
  "editor.defaultFormatter": "esbenp.prettier-vscode",       // Usa Prettier como formatador padrão
  "editor.formatOnSave": true,                              // Formata código automaticamente ao salvar
 // "files.autoSave": "afterDelay",                           // Salva automaticamente após um delay
 // "files.autoSaveDelay": 1000,                              // Define delay de 1 segundo para autosave
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit",                     // Corrige problemas do ESLint ao salvar
    "source.organizeImports": "explicit"                    // Organiza imports automaticamente
  },

  // JavaScript/TypeScript
  "javascript.updateImportsOnFileMove.enabled": "always",    // Atualiza imports ao mover arquivos JS
  "typescript.updateImportsOnFileMove.enabled": "always",    // Atualiza imports ao mover arquivos TS
  "javascript.suggest.autoImports": true,                    // Sugere imports automaticamente para JS
  "typescript.suggest.autoImports": true,                    // Sugere imports automaticamente para TS
  "typescript.preferences.importModuleSpecifier": "non-relative", // Prefere imports não relativos
  "typescript.suggest.completeFunctionCalls": true,          // Completa chamadas de função automaticamente
  "typescript.inlayHints.parameterNames.enabled": "all",     // Mostra nomes de parâmetros inline
  "typescript.inlayHints.functionLikeReturnTypes.enabled": true, // Mostra tipos de retorno inline

  // Editor e Código
  "editor.tabSize": 2,                                      // Indentação de 2 espaços
  "editor.wordWrap": "on",                                  // Quebra linhas automaticamente
  "editor.bracketPairColorization.enabled": true,           // Coloriza pares de colchetes/chaves
  "editor.guides.bracketPairs": true,                       // Mostra guias para pares de colchetes
  "editor.suggestSelection": "first",                       // Seleciona primeira sugestão
  "editor.snippetSuggestions": "top",                       // Prioriza snippets nas sugestões
  "editor.linkedEditing": true,                             // Edição vinculada de tags
  "editor.inlineSuggest.enabled": true,                     // Habilita sugestões inline

  // Terminal e NPM
  "terminal.integrated.defaultProfile.windows": "Git Bash",  // Usa Git Bash como terminal padrão
  "terminal.integrated.fontFamily": "Fira Code",            // Fonte para o terminal
  "terminal.integrated.fontSize": 14,                       // Tamanho da fonte do terminal
  "npm.packageManager": "npm",                              // Define NPM como gerenciador de pacotes
  "npm.scriptExplorerAction": "run",                        // Ação padrão para scripts NPM

  // Debug
  "debug.javascript.autoAttachFilter": "smart",             // Anexação automática inteligente do debugger
  "debug.javascript.terminalOptions": {
    "skipFiles": ["<node_internals>/**"]                    // Pula arquivos internos do Node no debug
  },

  // Git
  //"git.enableSmartCommit": true,                           // Habilita commit inteligente
  //"git.confirmSync": false,                                // Remove confirmação para sync
  //"git.autofetch": true,                                   // Busca alterações automaticamente

  // Fonte e Estilo
  "editor.fontSize": 14,                                   // Tamanho da fonte do editor
  "editor.lineHeight": 22,                                 // Altura da linha
  "editor.fontFamily": "Fira Code",                        // Fonte principal
  "editor.fontLigatures": true,                            // Habilita ligaduras da fonte

  // IntelliSense e Sugestões
  "editor.acceptSuggestionOnEnter": "smart",               // Aceita sugestões com Enter de forma inteligente
  "editor.parameterHints.enabled": true,                   // Mostra dicas de parâmetros
  "editor.quickSuggestions": {
    "other": true,                                         // Sugestões rápidas para código
    "comments": true,                                      // Sugestões em comentários
    "strings": true                                        // Sugestões em strings
  }
}


code --install-extension esbenp.prettier-vscode
code --install-extension dbaeumer.vscode-eslint
code --install-extension PKief.material-icon-theme
code --install-extension dracula-theme.theme-dracula
code --install-extension usernamehw.errorlens
code --install-extension eamodio.gitlens
code --install-extension rangav.vscode-thunder-client
code --install-extension wix.vscode-import-cost
