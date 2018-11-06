# VSCode Joomla Snippets

Visual Studio Code Joomla snippets and code examples for Joomla 3 & 4 Alpha.

All code snippets are based on and follow the Joomla style guide <https://docs.joomla.org/Joomla_CodeSniffer>.

## Snippet Prefixes

| Prefix | Description |
| ------- | ----------|
| j- | Joomla Snippets |
| j4- | Joomla 4 Alpha Snippets |
| jdoc- | Snippets for Templates |

## Usage

All Joomla snippets starts with "j-", "j4-", or "jdoc-".

## Joomla Snippets

| Snippet | Description |
| ------- | ----------|
| j4-add-defer-remote-script | Adds a deferred remote script to the page, to start optimizing load of files. |
| j4-add-defer-remote-stylesheet | Adds a deferred remote stylesheet to the page, to start optimizing load of files. |
| j4-add-defer-script-extension | Adds a deferred extension script to the page, to start optimizing load of files. |
| j4-add-inline-script | Adds an inline script to the page, to start reducing the number of loaded files. |
| j4-add-inline-style | Adds an inline stylesheet declaration to the page, to start reducing the number of loaded files. |
| j4-app | Adds the Joomla Factory declaration and the app variable declaration. |
| j4-arrayhelper | Adds the ArrayHelper declaration. |
| j4-comp-params-backend-cli | Declaration of the component helper and params retrieval. |
| j4-comp-params-frontend | Declaration of the component helper and params retrieval. |
| j4-doc | Adds the Joomla Factory declaration and the document variable declaration. |
| j4-factory | Adds the Joomla Factory declaration. |
| j4-jinput | Declaration of the JInput. |
| j4-registry | Adds the Joomla Registry declaration. |
| j4-text-translation | Declares the text translation helper (a.k.a JText::_). |
| j4-user | Adds the Joomla Factory declaration and the app variable declaration. |
| j-add-defer-remote-script | Adds a deferred remote script to the page, to start optimizing load of files. |
| j-add-defer-remote-stylesheet | Adds a deferred remote stylesheet to the page, to start optimizing load of files. |
| j-add-defer-script-extension | Adds a deferred script to the page, to start optimizing load of files. |
| j-add-inline-script | Adds an inline script to the page, to start reducing the number of loaded files. |
| j-add-inline-stylesheet | Adds an inline stylesheet declaration to the page, to start reducing the number of loaded files. |
| j-add-script-version | Adds a linked template script to the page with a version to allow to flush it. |
| j-add-stylesheet-version | Adds a linked template stylesheet version to the page. |
| jdoc-add-module-position | Add a module position to a template. |
| j-formtoken | Method to determine a hash for anti-spoofing variable names. |
| j-function | Standard Joomla function declaration. |
| j-head | Common template header variables for Joomla 3. |
| j-log | Method to add an entry to one custom log file. |
| j-text | Expand a JText for Joomla 3. Translates a string into the current language. |

## Installation (Mac)

1. Launch VS Code
1. Quick Open (⌘+P)
1. Enter the following command and press enter: 'ext install Angular-BeastCode'
1. Choose extension (Author: Mikael Morlund)
1. Reload VS Code

## Installation (Windows, Linux)

1. Launch VS Code
1. Quick Open (Ctrl-Shift-P)
1. Enter the following command and press enter: 'ext install Angular-BeastCode'
1. Choose extension (Author: Mikael Morlund)
1. Reload VS Code

## Emmets

If you want intellisense to show emmets before the snippets, you can force the emmets suggestions to show up at the top, by add the following to your editor user settings:

```javascript
{
  "emmet.showSuggestionsAsSnippets": true,
  "editor.snippetSuggestions": "top"
}
```

## Feedback

Please send any feedback or suggestions to [@anibal_sanchez](https://twitter.com/anibal_sanchez) (Twitter) or [create an issue](https://github.com/anibalsanchez/VSCode-Joomla-Snippets) on GitHub.

## Open Source

This is an open source project and if you want to contribute I've added issues on github that are easy to start with. [![first-timers-only](https://img.shields.io/badge/first--timers--only-friendly-blue.svg)](https://github.com/anibalsanchez/VSCode-Joomla-Snippets/labels/first-timers-only)

## Disclaimer

Important: This extension due to the nature of it's purpose will create
files on your hard drive and if necessary create the respective folder structure.
While it should not override any files during this process, I'm not giving any guarantees or take any responsibility in case of lost data.

## License

MIT

## Acknowledgements

- [Snippets para Visual Studio Code y Joomla](https://www.sergioiglesias.net/blog/joomla/418-snippets-para-visual-studio-code-y-joomla)
