# Awesome Angular Pack

A colection of useful and stable angular/typescript extensions

## Angular

* [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)
  This extension provides a rich editing experience for Angular templates, both inline and external templates including (Completions lists, AOT Diagnostic messages, Quick info, Go to definition)

* [VSCode Angular TypeScript & Html Snippets](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode)
  Visual Studio Code TypeScript and Html snippets and code examples for Angular 2,4,5 & 6. All code snippets are based on and follow the [Angular style guide](https://angular.io/docs/ts/latest/guide/style-guide.html).

* [VS Code Angular Files](https://marketplace.visualstudio.com/items?itemName=alexiv.vscode-angular2-files)
  This extension allows quickly scaffold angular 2 file templates in VS Code project.

* [Angular2 Switcher](https://marketplace.visualstudio.com/items?itemName=infinity1207.angular2-switcher)
  Easily navigate to typescript(.ts)|template(.html)|style(.scss/.sass/.less/.css) in angular2 project.

* [SimonTest](https://marketplace.visualstudio.com/items?itemName=SimonTest.simontest)
  An Angular test generator. It analyzes your code and creates the necessary stubs, configures the TestBed, and it even generates tests for you.

* [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
  The Material Icon Theme provides lots of icons based on Material Design for Visual Studio Code. It include seperate icon for example Angular-Services, Angular-Components, Angular-Directives,....

## Typescript

* [TSLint](https://marketplace.visualstudio.com/items?itemName=eg2.tslint)
  Integrates the tslint linter for the TypeScript language into VS Code.

* [TypeScript Hero](https://marketplace.visualstudio.com/items?itemName=rbbit.typescript-hero)
  Sort and organize your imports (sort and remove unused). Code outline view of your open TS / TSX document. Add import to the document or add an import that is under the cursor to the document.

* [Auto Import](https://marketplace.visualstudio.com/items?itemName=steoates.autoimport)
  Automatically finds, parses and provides code actions and code completion for all available imports. Works with Typescript and TSX.

* [Move TS README](https://marketplace.visualstudio.com/items?itemName=stringham.move-ts)
  Supports moving typescript files and updating relative imports within the workspace.

* [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)

* [Code outline](https://marketplace.visualstudio.com/items?itemName=patrys.vscode-code-outline)
  Displays a code outline tree in the explorer pane.

* [Comment TS](https://marketplace.visualstudio.com/items?itemName=salbert.comment-ts)
  "Comment TS" is a Visual Studio Code extension that automatically generates a template for JSDoc comments. It is adapted for TypeScript files. Typescript comes with a lot of language annotations, which should not be dublicated to the comments. If you like comments generated from name semantics:

```
"comment-ts.parseNames": true
```

## HTML

* [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
  Automatically add HTML/XML close tag, same as Visual Studio IDE or Sublime Text does.
  If you like to exclude typescript (collides with explicit type conversions):

```
    "auto-close-tag.activationOnLanguage": [
        "xml",
        "php",
        "markdown",
        "html",
        "HTML (Eex)"
    ]
```

* [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
  Automatically rename paired HTML/XML tag, same as Visual Studio IDE does.

## NPM

* [Node npm](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script)
  This extension validates the installed modules against the dependencies defined in the package.json.

* [Version Lens](https://marketplace.visualstudio.com/items?itemName=pflannery.vscode-versionlens)
  Shows package version information for npm, jspm, bower, dub and dotnet core in the Visual Studio Code editor.

## Code formatting

* [Prettier formatter for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
  VS Code package to format your JavaScript / TypeScript / CSS using Prettier. Configure your preferences in a ".prettierrc" file:

```
{
   "printWidth": 150,
   "singleQuote": true,
   "arrowParens": "always"
}
```

* [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
  This plugin attempts to override user/workspace settings with settings found in .editorconfig files. No additional or vscode-specific files are required. As with any EditorConfig plugin, if root=true is not specified, EditorConfig will continue to look for an .editorconfig file outside of the project.

* [EMBRACE extension for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=mycelo.embrace[])
  Surround the selection with parenthesis, brackets, quotes, etc.

## Dev Tools

* [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
  GitLens supercharges the Git capabilities built into Visual Studio Code. It helps you to visualize code authorship at a glance via Git blame annotations and code lens, seamlessly navigate and explore Git repositories, gain valuable insights via powerful comparison commands, and so much more. If you don't like the gitlens on the current line set:

```
"gitlens.currentLine.enabled" = false
```

* [Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)
  Debug your JavaScript code in the Chrome browser, or any other target that supports the Chrome Debugger protocol.

* [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
  Visual Studio Code plugin that autocompletes filenames.

## Tipps

* If you do not like vs code telemetry set:

```
"telemetry.enableTelemetry": false
```

* [TypeDoc](http://typedoc.org/guides/installation/)
  A documentation generator for TypeScript projects.

* All NPM scripts to start in the explorer view:

```
"npm.enableScriptExplorer": true
```

* Organize imports on file save:

```
"[typescript]": {
    "editor.codeActionsOnSave": {
        "source.organizeImports": true
    }
}
```
