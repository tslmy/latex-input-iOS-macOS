# LaTeX-Input for iOS and macOS

![Demo](https://i.imgur.com/JA7uqES.gif)

A Text Replacement definition `plist` file

Based on the brilliant idea of [LaTeX-Input](https://github.com/clarkgrubb/latex-input) from [clarkgrubb](https://github.com/clarkgrubb).

## Introduction

- Helps to add some math symbols under text-only scenarios.
- For people who thinks switching to another input method just for one or two symbols is too much work (as offered by LaTeX-Input).
- Text-replacement definitions are automatically synced via iCloud. Hence, once installed on your Mac, these shortcuts can work on all your iOS devices.

## Installation

1. Go to System Perferences > Keyboard > Text.
2. Drag `LaTeX.plist` to the listbox on the left.

For a while, no change may be observed in this listbox. That's because this Text Replacement functionality wasn't really designed to handle definitions as many as such. Give it a few minutes.

## Known Issues

macOS seems to have its own logic handling upper cases in text substitution, which cause `\alpha` and `\Alpha` to both yield `Α`. One solution is to manually remove the uppercased versions from the listbox, as macOS automatically converts the replacement to uppercase when the first letter you types is capitalized. 

However, not being a native speaker to Greek, I don't have time or confidence to figure out a comprehensive list of LaTeX instructions that complies with this behavior. Let me know if you can do it. Thanks.

## See Also

Check out [Macmoji](https://github.com/warpling/Macmoji), a Text Substitution `plist` file for Slack-style emojis.
