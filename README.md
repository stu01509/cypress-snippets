# VS Code Cypress Snippets

[![Version](https://vsmarketplacebadge.apphb.com/version/CliffSu.cypress-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=CliffSu.cypress-snippets)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/CliffSu.cypress-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=CliffSu.cypress-snippets)
[![Update](https://img.shields.io/visual-studio-marketplace/last-updated/CliffSu.cypress-snippets)](https://marketplace.visualstudio.com/items?itemName=CliffSu.cypress-snippets)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating/CliffSu.cypress-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=CliffSu.cypress-snippets)

![Demo](./assets/demo.gif)

This extension includes the most common cypress snippets. If you like it, please leave your Rating & Review and share it with your friends.

## Installation

In order to install an extension, you need to open the Extensions Palette (`Ctrl + Shift + X` or `Cmd ⌘ + Shift + X`). There you have either the option to show the already installed snippets or install new ones.

[Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=CliffSu.cypress-snippets)

## Supported Languages (file extensions)

- JavaScript (.js)
- TypeScript (.ts)
- JavaScript React (.jsx)
- TypeScript React (.tsx)

## Snippets

### Mocha Snippets

| Snippet  | Code                                                   |
| -------- | -------------------------------------------------------|
| `dsb`    | describe('', () => {<br><br>});                        |
| `ctx`    | context('', () => {<br><br>});                         |
| `spe`    | specify('', () => {<br><br>});                         |
| `it`     | it('', () => {<br><br>});                              |
| `bf`     | before('', () => {<br><br>});                          |
| `bfe`    | beforeEach('', () => {<br><br>});                      |
| `af`     | after('', () => {<br><br>});                           |
| `afe`    | afterEach('', () => {<br><br>});                       |

**[⬆ Back to top](#Installation)**

### Cypress Snippets

| Snippet  | Code                                                   |
| -------- | -------------------------------------------------------|
| `cyvt`   | cy.visit('');                                          |
| `cygt`   | cy.get('');                                            |
| `cyfd`   | cy.get('').find('');                                   |
| `cyft`   | cy.get('').first('');                                  |
| `cylt`   | cy.get('').last('');                                   |
| `cyte`   | cy.get('').type('');                                   |
| `cyck`   | cy.get('').click();                                    |
| `cycs`   | cy.contains('');                                       |
| `cywt`   | cy.wait('');                                           |
| `cyul`   | cy.url().should('', '');                               |
| `cylg`   | cy.log('');                                            |
| `cype`   | cy.pause();                                            |
| `cydg`   | cy.debug();                                            |
| `cyst`   | cy.screenshot('');                                     |
| `cyvpt`  | cy.viewport();                                         |

**[⬆ Back to top](#Installation)**

## Change Log

See the [CHANGELOG](./CHANGELOG.md) for details about the changes in each version.

## License

[MIT](./LICENSE)
