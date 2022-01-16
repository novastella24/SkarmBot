# SkarmBot

## Getting Started

### Add the bot to your server
 [Ask your Server Administrators to add Skarm to your favorite server today!](https://discordapp.com/oauth2/authorize?client_id=319291086570913806&scope=bot)

### Running the code
1. Clone the repository locally by running `git clone https://github.com/DragoniteSpam/SkarmBot.git`
2. Install Box Drive and log in with credentials that have access to the database repository `skarmData`
3. Run the powershell script `initialize-Dependencies.ps1` to install node.js and all required packages to execute skarmbot
4. Resolve any errors identified by the initialization script so that another run of it confirms that all node packages are installed, all data files are present, and all tokens are present
5. Run the powershell script `.\launcher.ps1 -operationMode live` to host the live instance of SkarmBot
6. Run the powershell script `.\launcher.ps1 -operationMode test` to host the test instance of SkarmBot
