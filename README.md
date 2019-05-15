# parcel-plugin-imba
### Feautres
- Hot Module Reloading
- Single File Components (Styles within Imba files)
    Example: 
    ```
    tag App
      def render
        <self>
          <h1> "hello World"
    sass (or stylus/scss/etc)
      .App
        background-color: white
    ```
- Supports Imba Asset Type
- Loads @pushqrdx's Imba PR with content feature (slots)

#### For syntax highlighting of styles within Imba files 
- Install VS Code Extension [vscode-imba-sfc](https://marketplace.visualstudio.com/items?itemName=tirado.imba)
- or load the imba.tmLanguage.json file from github.com/shreeve/vscode-imba
