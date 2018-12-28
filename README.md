# VSCode Joomla Snippets

Visual Studio Code Joomla snippets and code examples for Joomla 3 & 4 Alpha.

All code snippets are based on and follow the Joomla style guide <https://docs.joomla.org/Joomla_CodeSniffer>.

## Snippet Prefixes

| Prefix | Description |
| ------- | ----------|
| j- | Joomla Snippets |
| j4- | Joomla 4 Alpha Snippets |

## Usage

All Joomla snippets starts with "j-" or "j4-".

## Joomla Snippets

| Snippet | Description |
| ------- | ----------|
| j4-application | Adds the Joomla Factory declaration and the app variable declaration. |
| j4-arrayhelper | Adds the ArrayHelper declaration. |
| j4-component-params-backend-cli | Declaration of the component helper and params retrieval. |
| j4-component-params-frontend | Declaration of the component helper and params retrieval. |
| j4-document | Adds the Joomla Factory declaration and the document variable declaration. |
| j4-factory | Adds the Joomla Factory declaration. |
| j4-formtoken | Method to determine a hash for anti-spoofing variable names. |
| j4-input | Declaration of the JInput. |
| j4-log | Method to add an entry to one custom log file. |
| j4-registry | Adds the Joomla Registry declaration. |
| j4-script | Adds a deferred extension script to the page, to start optimizing load of files. |
| j4-script-inline | Adds an inline script to the page, to start reducing the number of loaded files. |
| j4-script-remote | Adds a linked template script to the page with a version to allow to flush it. |
| j4-script-remote-defer | Adds a deferred remote script to the page, to start optimizing load of files. |
| j4-stylesheet | Adds a stylesheet. |
| j4-stylesheet-inline | Adds an inline stylesheet declaration to the page, to start reducing the number of loaded files. |
| j4-stylesheet-remote | Adds an absolute URL to link a versiones template stylesheet to the page. |
| j4-stylesheet-remote-defer | Adds a deferred remote stylesheet to the page, to start optimizing load of files. |
| j4-template-head | Common template header variables for Joomla 3. |
| j4-text-translation | Declares the text translation helper (a.k.a JText::_). |
| j4-uri-base | Adds the Joomla URI declaration, to get the Base URI. |
| j4-uri-root | Adds the Joomla URI declaration, to get the Root URI. |
| j4-user | Adds the Joomla Factory declaration and the app variable declaration. |
| j-application | Adds the Joomla Factory app variable declaration. |
| j-arrayhelper | Adds the JArrayHelper declaration. |
| j-component-params-backend-cli | Declaration of the component helper and params retrieval. |
| j-component-params-frontend | Declaration of the component helper and params retrieval. |
| j-document | Adds the Joomla document variable declaration. |
| j-factory | Adds the Joomla Factory declaration. |
| j-formtoken | Method to determine a hash for anti-spoofing variable names. |
| j-function | Standard Joomla function declaration. |
| j-input | Declaration of the JInput. |
| j-log | Method to add an entry to one custom log file. |
| j-module-position | Add a module position to a template. |
| j-registry | Adds the Joomla Registry declaration. |
| j-script | Adds a deferred script to the page, to start optimizing load of files. |
| j-script-inline | Adds an inline script to the page, to start reducing the number of loaded files. |
| j-script-remote | Adds a linked template script to the page with a version to allow to flush it. |
| j-script-remote-defer | Adds a deferred remote script to the page, to start optimizing load of files. |
| j-stylesheet | Adds a stylesheet. |
| j-stylesheet-inline | Adds an inline stylesheet declaration to the page, to start reducing the number of loaded files. |
| j-stylesheet-remote | Adds an absolute URL to link a versiones template stylesheet to the page. |
| j-stylesheet-remote-defer | Adds a deferred remote stylesheet to the page, to start optimizing load of files. |
| j-template-head | Common template header variables for Joomla 3. |
| j-text | Expand a JText for Joomla 3. Translates a string into the current language. |
| j-uri-base | Adds the Joomla URI declaration, to get the Base URI. |
| j-uri-root | Adds the Joomla URI declaration, to get the Root URI. |
| j-user | Adds the Joomla Factory declaration and the app variable declaration. |

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
