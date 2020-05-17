| [tools](../tools/tools.md) > [healthdomain](../healthdomain/healthdomain.md) > [bookmarks](../bookmarks/bookmarks.md) > [ds_algo_program](../ds_algo_program/ds_algo_program.md) > [architecturepatterns](../architecturepatterns/architecturepatterns.md) > [csharpdotnet](../csharpdotnet/csharpdotnet.md) > [webdev](../webdev/webdev.md) > [azure](../azure/azure.md) > [devops](../devops/devops.md) > [performance](../performance/performance.md) > [security](../security/security.md) > [services](../services/services.md) > [sql](../sql/sql.md) > [trending](../trending/trending.md) |
| --- |

# Needed tools

- VS Code
Neat trick to get the list of installed extensions of VS Code:
Open powershell prompt and run the following command: code --list-extensions | % { "code --install-extension $_" }

The extensions I use are listed below: TO enable AzureDevops integration (check-in/check-out); installing ms-vsts.team is a MUST.
- code --install-extension ms-mssql.mssql
- code --install-extension docsmsft.docs-markdown
- code --install-extension eamodio.gitlens
- code --install-extension ed-elliott.azure-arm-template-helper

- code --install-extension abusaidm.html-snippets
- code --install-extension alefragnani.Bookmarks
- code --install-extension alefragnani.project-manager
- code --install-extension alefragnani.read-only-indicator
- code --install-extension andyyaldoo.vscode-json
- code --install-extension azemoh.one-monokai
- code --install-extension christian-kohler.npm-intellisense
- code --install-extension christian-kohler.path-intellisense
- code --install-extension chrmarti.regex
- code --install-extension CoenraadS.bracket-pair-colorizer-2
- code --install-extension dbaeumer.vscode-eslint

- code --install-extension donjayamanne.jquerysnippets
- code --install-extension dracula-theme.theme-dracula


- code --install-extension eg2.vscode-npm-script
- code --install-extension esbenp.prettier-vscode
- code --install-extension fabiospampinato.vscode-terminals
- code --install-extension formulahendry.auto-close-tag
- code --install-extension formulahendry.auto-rename-tag
- code --install-extension formulahendry.code-runner
- code --install-extension Gruntfuggly.todo-tree
- code --install-extension herrherrmann.angular-bootstrap
- code --install-extension HookyQR.beautify
- code --install-extension jasonnutter.search-node-modules
- code --install-extension jchannon.csharpextensions
- code --install-extension johnpapa.Angular2
- code --install-extension jrebocho.vscode-random
- code --install-extension leizongmin.node-module-intellisense
- code --install-extension Mikael.Angular-BeastCode
- code --install-extension ms-azure-devops.azure-pipelines
- code --install-extension ms-azuretools.vscode-azureappservice
- code --install-extension ms-azuretools.vscode-azurefunctions
- code --install-extension ms-azuretools.vscode-azureresourcegroups
- code --install-extension ms-azuretools.vscode-azurestorage
- code --install-extension ms-azuretools.vscode-azurevirtualmachines
- code --install-extension ms-azuretools.vscode-cosmosdb
- code --install-extension ms-azuretools.vscode-docker
- code --install-extension ms-dotnettools.csharp
- code --install-extension ms-dotnettools.vscode-dotnet-runtime
- code --install-extension ms-python.python
- code --install-extension ms-vscode-remote.remote-wsl
- code --install-extension ms-vscode.azure-account
- code --install-extension ms-vscode.azurecli
- code --install-extension ms-vscode.powershell
- code --install-extension ms-vscode.vscode-node-azure-pack
- code --install-extension ms-vsts.team
- code --install-extension msazurermtools.azurerm-vscode-tools
- code --install-extension msjsdiag.debugger-for-chrome
- code --install-extension PKief.material-icon-theme
- code --install-extension RoscoP.ActiveFileInStatusBar
- code --install-extension samcogan.arm-snippets
- code --install-extension sdras.night-owl
- code --install-extension shardulm94.trailing-spaces
- code --install-extension slevesque.vscode-hexdump
- code --install-extension spywhere.guides
- code --install-extension techer.open-in-browser
- code --install-extension vscode-icons-team.vscode-icons
- code --install-extension waderyan.nodejs-extension-pack
- code --install-extension xabikos.JavaScriptSnippets
- code --install-extension zhuangtongfa.material-theme
- code --install-extension Zignd.html-css-class-completion

- Powershell v5.1 (Note powershell core is in works https://github.com/PowerShell/Powershell)

- Az powershell module v3.5.0 (if you intend to use azure powershell functions)
Check installed version from powershell using command: Get-InstalledModule -Name Az -AllVersions | Select-Object -Property Name, Version
Installing latest Az powershell module: Install-Module -Name Az -AllowClobber -Force

- LINQPad (Free / Paid version)
LINQPad v5 supports >NET Framework 4.6/4.7/4.8
LINQPad v6 supports .NET Core 3.0/3.1
For most part LINQPad v5 will suffice. At times, LINQPad scripts of v5 won't run along well in .NET Core unless an upgrade is done.
Recommend keeping LINQPAD v5 and v6 snippets separate.
https://www.linqpad.net/Download.aspx
LINQPad v5 / v6 run side by side.
