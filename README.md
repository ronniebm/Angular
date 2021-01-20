## Angular learning repository.
<img src="https://sg.com.mx/sites/default/files/styles/570x500/public/images/angular-logo.png" width="200px">

### Steps to install/work_with angular in Ubuntu 18.04 LTS
1) First we check all packages are uptaded/upgraded:
```
sudo apt update
sudo apt upgrade
```

2) Before installing angular, first we must install Node Js and Node Package Manager (npm)
```
curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
sudo apt-get install -y nodejs
sudo npm install npm@latest -g
```

3) Installing CLI Angular in Ubuntu
```
sudo npm install -g @angular/cli
```

4) Checking angular version in terminal
```
ng --version
```

5) Angular CLI use git to deploy neccesary modules, that's why we need to have git configured
```
git config --global user.email "correo@electronico.com"
git config --global user.name "usuario"
```

6) Creating a new angular version
```
ng new application-name
```

7) Launch an angular application
```
cd application-name
npm start
```

## Vscode config and Extensions:
<img src="https://damiandeluca.com.ar/wp-content/uploads/2018/04/visual-studio-code.png" width="200px">

1) Configuration (thins can change):
```
{
    "workbench.settings.editor": "json",
    "editor.fontSize": 17,
    "editor.formatOnSave": true,
    "editor.formatOnPaste": true,
    "editor.renderWhitespace": "all",
}
```

2) Some extensions to install:

- Prettier - code formatter:
https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode

- Angular 2 TypeScript Emmet:
https://marketplace.visualstudio.com/items?itemName=jakethashi.vscode-angular2-emmet

- Angular v5 Snippets:
Angular v5 Snippets

- Angular Language Service:
https://marketplace.visualstudio.com/items?itemName=Angular.ng-template

- Angular2-inline:
https://marketplace.visualstudio.com/items?itemName=natewallace.angular2-inline

- Bootstrap 4, Font awesome 4, Font Awesome 5 Free & Pro snippets:
https://marketplace.visualstudio.com/items?itemName=thekalinga.bootstrap4-vscode

- HTML CSS Support:
https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css

- JavaScript (ES6) code snippets:
https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets

- JS-CSS-HTML Formatter:
https://marketplace.visualstudio.com/items?itemName=lonefy.vscode-JS-CSS-HTML-formatter

- JShint:
https://marketplace.visualstudio.com/items?itemName=dbaeumer.jshint

- Terminal:
https://marketplace.visualstudio.com/items?itemName=formulahendry.terminal

- TSLint:
https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin

- TypeScript Hero:
https://marketplace.visualstudio.com/items?itemName=rbbit.typescript-hero

- TypeScript Importer:
https://marketplace.visualstudio.com/items?itemName=pmneo.tsimporter
