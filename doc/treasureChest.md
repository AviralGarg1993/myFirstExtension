# Treasure Chest

| Concept                 | Description                                                                                                                                                   | Links                    | Image                   |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------ | ----------------------- |
| **Contribution Points** | areas your extension contributes to?                                                                                                                          | [contribution-points][1] | ![contributions][2]     |
| **Extension Manifest**  | `package.json` Manifesto of your extension                                                                                                                    | [extension-manifest][3]  |                         |
| **Activation Events**   | Your extension becomes activated when the Activation Event happens                                                                                            | [activation-events][4]   | ![activation][5]        |
| **disposable**          | f(n)s for cmd implementation (disposed <= extn deactivates)                                                                                                   |                          |                         |
| **subscriptions**       | array of disposables; when extn deactivates => disposables disposed                                                                                           |                          |                         |
| **Extension Context**   | collection of utilities private to an extension (An instance of an ExtensionContext is provided as the first parameter to the activate-call of an extension.) |                          | ![extension-context][6] |

## Extension File Structure

    .
    ├── .vscode
    │   ├── launch.json     // Config for launching and debugging the extension
    │   └── tasks.json      // Config for build task that compiles TypeScript
    ├── .gitignore          // Ignore build output and node_modules
    ├── README.md           // Readable description of your extension's functionality
    ├── src
    │   └── extension.ts    // Extension source code
    ├── package.json        // Extension manifest
    ├── tsconfig.json       // TypeScript configuration

Link for more [NodeJS Debugging][7]

<!-- Links -->
[1]: https://code.visualstudio.com/api/references/contribution-points
[3]: https://code.visualstudio.com/api/references/extension-manifest
[4]: https://code.visualstudio.com/api/references/activation-events
[7]: https://code.visualstudio.com/docs/nodejs/nodejs-debugging

<!-- Images -->
[2]: ../resource/img/treasureChest/contribution-points.png
[5]: ../resource/img/treasureChest/activation-events.png
[6]: ../resource/img/treasureChest/extension-context.png