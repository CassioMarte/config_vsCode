# config_vsCode
reseta o vscode
//rd /s /q "%AppData%\Code" && rd /s /q "%UserProfile%\.vscode"

                                              //TS e JS 
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





TS, JS e Python 

{
  // =================== TEMA E APARÊNCIA ===================
  "workbench.colorTheme": "Dracula Theme",                    // Tema escuro que reduz o cansaço visual
  "workbench.iconTheme": "material-icon-theme",              // Pacote de ícones mais intuitivo
  "workbench.editor.enablePreview": false,                   // Impede preview de arquivos ao clicar
  
  // =================== PERFORMANCE ===================
  "editor.minimap.enabled": false,                           // Desativa minimap para economizar recursos
  "editor.renderWhitespace": "selection",                    // Mostra espaços em branco só na seleção
  "editor.smoothScrolling": true,                            // Rolagem mais suave
  "workbench.list.smoothScrolling": true,                    // Rolagem suave em listas também
  "editor.cursorSmoothCaretAnimation": "on",                // Cursor com animação suave
  
  // =================== FORMATAÇÃO GERAL ===================
  "editor.formatOnSave": true,                              // Formata arquivos ao salvar
  "editor.formatOnPaste": true,                             // Formata código colado
  "files.autoSave": "afterDelay",                           // Salva automaticamente
  "files.autoSaveDelay": 1000,                              // Delay de 1 segundo para autosave
  "editor.defaultFormatter": "esbenp.prettier-vscode",       // Prettier como formatador padrão
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit",                     // Corrige problemas do ESLint ao salvar
    "source.organizeImports": "explicit"                    // Organiza imports automaticamente
  },

  // =================== JAVASCRIPT/TYPESCRIPT ===================
  "javascript.updateImportsOnFileMove.enabled": "always",    // Atualiza imports ao mover arquivos JS
  "typescript.updateImportsOnFileMove.enabled": "always",    // Atualiza imports ao mover arquivos TS
  "javascript.suggest.autoImports": true,                    // Sugere imports JS automaticamente
  "typescript.suggest.autoImports": true,                    // Sugere imports TS automaticamente
  "typescript.preferences.importModuleSpecifier": "non-relative", // Prefere imports não relativos
  "typescript.suggest.completeFunctionCalls": true,          // Completa funções automaticamente
  "typescript.inlayHints.parameterNames.enabled": "all",     // Mostra nomes de parâmetros inline
  "typescript.inlayHints.functionLikeReturnTypes.enabled": true, // Mostra tipos de retorno

  // =================== PYTHON ===================
  "[python]": {
    "editor.defaultFormatter": "ms-python.python",          // Formatador Python padrão
    "editor.formatOnType": true,                           // Formata enquanto digita
    "editor.formatOnSave": true,                           // Formata ao salvar
    "editor.tabSize": 4,                                   // 4 espaços (PEP 8)
    "editor.rulers": [79, 88],                             // Guias de comprimento de linha
    "editor.wordWrapColumn": 88                            // Quebra de linha no Black
  },
  "python.languageServer": "Pylance",                      // Engine de análise Python
  "python.analysis.typeCheckingMode": "basic",             // Verificação básica de tipos
  "python.linting.enabled": true,                          // Ativa linting
  "python.linting.pylintEnabled": true,                    // Usa Pylint
  "python.linting.flake8Enabled": true,                    // Usa Flake8
  "python.formatting.provider": "black",                   // Black como formatador
  "python.testing.pytestEnabled": true,                    // Habilita Pytest
  "python.defaultInterpreterPath": "${workspaceFolder}/.venv/bin/python", // Caminho do virtualenv

  // =================== EDITOR E CÓDIGO ===================
  "editor.tabSize": 2,                                      // 2 espaços para linguagens não-Python
  "editor.wordWrap": "on",                                  // Quebra linhas longas
  "editor.bracketPairColorization.enabled": true,           // Colore pares de colchetes
  "editor.guides.bracketPairs": true,                       // Mostra guias de colchetes
  "editor.suggestSelection": "first",                       // Seleciona primeira sugestão
  "editor.snippetSuggestions": "top",                       // Prioriza snippets
  "editor.linkedEditing": true,                             // Edição vinculada de tags
  "editor.inlineSuggest.enabled": true,                     // Sugestões inline
  
  // =================== TERMINAL ===================
  "terminal.integrated.defaultProfile.windows": "Git Bash",  // Git Bash como padrão no Windows
  "terminal.integrated.fontFamily": "Fira Code",            // Fonte do terminal
  "terminal.integrated.fontSize": 14,                       // Tamanho da fonte do terminal
  "terminal.integrated.cursorStyle": "line",                // Estilo do cursor
  "npm.packageManager": "npm",                              // Define NPM como gerenciador de pacotes
  "npm.scriptExplorerAction": "run",                        // Ação padrão para scripts NPM
  
  // =================== GIT ===================
  "git.enableSmartCommit": true,                           // Commit inteligente
  "git.confirmSync": false,                                // Não pede confirmação para sync
  "git.autofetch": true,                                   // Busca alterações automaticamente
  "git.enableCommitSigning": true,                         // Assina commits com GPG
  
  // =================== FONTE E ESTILO ===================
  "editor.fontSize": 14,                                   // Tamanho da fonte
  "editor.lineHeight": 22,                                 // Altura da linha
  "editor.fontFamily": "Fira Code",                        // Fonte principal
  "editor.fontLigatures": true,                            // Ligaduras tipográficas
  
  // =================== INTELIGÊNCIA ARTIFICIAL ===================
  "editor.acceptSuggestionOnEnter": "smart",               // Aceita sugestões com Enter
  "editor.parameterHints.enabled": true,                   // Mostra dicas de parâmetros
  "editor.quickSuggestions": {
    "other": true,                                         // Sugestões para código
    "comments": true,                                      // Sugestões em comentários
    "strings": true                                        // Sugestões em strings
  },
  
  // =================== EXPLORADOR DE ARQUIVOS ===================
  "explorer.compactFolders": false,                        // Não compacta pastas vazias
  "explorer.confirmDelete": false,                         // Não confirma deleção
  "explorer.confirmDragAndDrop": false,                    // Não confirma drag and drop
  
  // =================== DEBUGGING ===================
  "debug.javascript.autoAttachFilter": "smart",            // Anexação automática do debugger
  "debug.javascript.terminalOptions": {
    "skipFiles": ["<node_internals>/**"]                   // Ignora arquivos internos do Node
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

# JS/TS
code --install-extension esbenp.prettier-vscode
code --install-extension dbaeumer.vscode-eslint
code --install-extension dracula-theme.theme-dracula
code --install-extension PKief.material-icon-theme

# Python
code --install-extension ms-python.python
code --install-extension ms-python.vscode-pylance

# Utilitários
code --install-extension eamodio.gitlens
code --install-extension usernamehw.errorlens
