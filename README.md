# VSCode GIFT Language Support and Snippets
[![Version](https://vsmarketplacebadge.apphb.com/version/ethan-ou.vscode-gift.svg)](https://vsmarketplacebadge.apphb.com/version-short/ethan-ou.vscode-gift.svg)
[![Install](https://vsmarketplacebadge.apphb.com/installs/ethan-ou.vscode-gift.svg)](https://vsmarketplacebadge.apphb.com/installs-short/ethan-ou.vscode-gift.svg)
[![Downloads](https://vsmarketplacebadge.apphb.com/downloads/ethan-ou.vscode-gift.svg)](https://vsmarketplacebadge.apphb.com/downloads-short/ethan-ou.vscode-gift.svg)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating-short/ethan-ou.vscode-gift.svg)](https://vsmarketplacebadge.apphb.com/rating-short/ethan-ou.vscode-gift.svg)

**NOTE:** This plugin is in alpha.

This extension provides syntax highlighting and code snippets for Moodle's GIFT format. It allows for faster and easier development of Moodle quiz questions.

## Demo

### Syntax Highlighting
![Syntax Highlighting](examples/Syntax Highlighting.gif)

### Snippets
![Code Snippets](examples/Code Snippets.gif)

## Formats

* GIFT (.gift) [recommended]
* Plain Text (.txt)

It is recommended to save files with the GIFT file extension (.gift). VSCode will automatically set the language to Gift when these files are opened. 

If you prefer using Plain Text (.txt), you will need to manually set the language in VSCode to ```Gift``` by [accessing the language tab](https://code.visualstudio.com/docs/languages/overview#_changing-the-language-for-the-selected-file) in the bottom right-hand corner. Alternatively, use the shortcut ```Ctrl+K M```.

## Snippets

**NOTE:** Snippets are still subject to change.

### At a Glance

|  Prefix     | Description                                                                            |
| -----------:| ---------------------------------------------------------------------------------------|
|  `mcq`      | `Multiple choice question with four options.`                                          |
|  `mcqf`     | `Multiple choice question with four options and feedback.`                             |
|  `mcqn`     | `Multiple choice question (numerical) with four options.`                              |
|  `mcqnf`    | `Multiple choice question (numerical) with four options and feedback.`                 |
|  `maq`      | `Matching question with four options.`                                                 |
|  `saq`      | `Short answer question with three correct answers.`                                    |
|  `tfq`      | `True-False question.`                                                                 |
|  `ess`      | `Essay question.`                                                                      |
|  `nq`       | `Numerical question.`                                                                  |
|  `cat`      | `Category label.`                                                                      |
|  `catn`     | `Nested category label.`                                                               |

### For Power Users

These snippets are useful if you've mastered the basic commands. To use these snippets, replace the number in brackets with the number of options you would like. For instance, a multiple choice question with three options is `mc3`.

|  Prefix     | Description                                                                            |
| -----------:| ---------------------------------------------------------------------------------------|
|  `mc[2-5]`  | `Multiple choice question with two to five options.`                                   |
|  `mc[2-5]f` | `Multiple choice question with two to five options and feedback.`                      |
|  `mc[2-5]n` | `Multiple choice question (numerical) with two to five options.`                       |
|  `mc[2-5]nf`| `Multiple choice question (numerical) with two to five options and feedback.`          |
|  `ma[2-5]`  | `Matching question with two to five options.`                                          |
|  `sa[1-5]`  | `Short answer question with one to five correct answers.`                              |

## License
MIT
