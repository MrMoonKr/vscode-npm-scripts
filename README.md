# Information
- VS Code 내장된 기능입니다.
- Extension 작성시 TreeView 구성 참고용으로 Clone 함.
- 최신 프로젝트 구성으로 업데이트 예정.

## Dependencies
- @types/vscode + vscode-test
- typescript
- @types/node
- ...

## vscode-npm-scripts ( NPM Scripts )

설치 필요 없는 익스텐션입니다.  
VS Code 에 비슷한 기능이 내장되어 있습니다.

[![Downloads](https://vsmarketplacebadge.apphb.com/installs/traBpUkciP.vscode-npm-scripts.svg)](https://vsmarketplacebadge.apphb.com/installs/traBpUkciP.vscode-npm-scripts.svg)
[![Rating](https://vsmarketplacebadge.apphb.com/rating/traBpUkciP.vscode-npm-scripts.svg)](https://vsmarketplacebadge.apphb.com/rating/traBpUkciP.vscode-npm-scripts.svg)

## This same functionality is now built in to vscode

Check it out [here](https://code.visualstudio.com/updates/v1_23#_npm-script-running)

----

# Features

**Now supports Workspaces!**

View and run NPM scripts from the sidebar

# Demo

![NPM Scripts](https://github.com/Duroktar/vscode-npm-scripts/raw/master/media/demo.gif "Demo")

# Usage

Open the NPM SCRIPTS section in the sidebar to view all
scripts in the projects package.json file. Click on one
to start it in the console. Each instance gets its own
console tab based on the script name, so running multiple
scripts at the same time is no problem.

## Contributors

* zachschuster @(github) - Miscellaneous improvements - PR#1
* frankMazzarella @(github) - Added script command/text to the tooltip of each TreeItem - PR#6

Thanks a ton, everyone!

## Configuration

{
...
"npm-scripts.showStartNotification": false // Disables dropdown notification
...
}

## Development

* Open this example in VS Code
* `npm install`
* `npm run compile`
* `F5` to start debugging

## License

MIT
