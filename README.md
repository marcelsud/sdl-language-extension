# SDL Language Support

Syntax highlighting for Service Definition Language (SDL) v0.1.

## Features
- Highlights SDL keywords (`package`, `import`, `type`, `enum`, `service`), primitives, annotations, unions/optionals/arrays, arrows and punctuation.
- Supports line comments `//` and doc comments `///`.
- Recognizes enum variants and type names with a distinct scope.

## Usage
- Install the extension and open any `.sdl` file; VS Code switches to the SDL language mode automatically.
- Try the sample in `highlight.sdl` to see all tokens.

## Development
- Run `npm install`.
- Launch extension debug: press `F5` in VS Code.
- Package locally: `vsce package` and install via `code --install-extension <file>.vsix`.

## Release Notes

### 0.1.0
- Initial syntax grammar and language configuration for SDL v0.1.
