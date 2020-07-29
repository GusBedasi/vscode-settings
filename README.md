## Para quando for baixar vscode em uma nova máquina e quiser os estilos prontos:

{
    // Define o tema:
    "workbench.colorTheme": "Dracula",

    "terminal.integrated.shell.windows": "C:\\Windows\\System32\\WindowsPowerShell\\v1.0\\powershell.exe",
    "explorer.confirmDelete": false,

    "launch": {

    "eslint.autoFixSave": true,
    "eslint.validate": [
        "javascript",
        "javascriptreact",
        { "language": "typescript", "autofix": true },
        { "language": "typescriptreact", "autofix": true }
    ]
    },
    "vsicons.dontShowNewVersionMessage": true,
    // Configura tamanho e família da fonte
    "editor.fontSize":16,
    "editor.lineHeight":24,
     "editor.fontFamily":"Fira Code",
     "editor.fontLigatures":true,

    // Aplica linhas verticais para lembrar de quebrar linha em códigos muito grandes
    "editor.rulers": [
        80,
        120
    ],
    // Aplica um sinal visual na esquerda da linha selecionada
    "editor.renderLineHighlight":"gutter",
  
    // Aumenta a fonte do terminal
    "terminal.integrated.fontSize":14,

    // Define o tema dos ícones na sidebar
    "workbench.iconTheme":"material-icon-theme"
}