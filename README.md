# Exalt Extension

Syntax highlighting and intellisense for exalt templates

## Features

- Syntax highlighting of inline html blocks.
- IntelliSense for html tags and attributes.
- Quick info hovers on tags.
- Formatting support.
- Auto closing tags.
- Folding html.
- CSS completions in style blocks.
- Works with template literal html strings that contain placeholders.

## Usage
The exalt vscode extension adds highlighting and intellisense for exalt template strings in JavaScript and TypeScript. It works out of the box when you use VS Code's built-in version of the typescript language service.

## Template Example

```js
import { Component, html } from "@exalt/core";

export class HelloWorld extends Component {

    render() {
        return html`
            <h1>This template should now have syntax highlighting and intellisense</h1>
        `;
    }
}

Component.create({ name: "hello-world" }, HelloWorld);
```

---

## Reporting Issues

If you are having trouble getting something to work with this extension or run into any problems, you can create a new [issue](https://github.com/exalt/vscode-exalt/issues).

If this extension does not fit your needs or is missing a feature you would like to see, let us know! We would greatly appreciate your feedback on it.

---

## License

this extension is licensed under the terms of the [**MIT**](https://github.com/exalt/vscode-exalt/blob/main/LICENSE) license.