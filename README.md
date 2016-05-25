# Godot Engine pt_BR translation

This is a temporary repository to help collaborating with the translation
of the [Godot Engine](https://godotengine.org) editor to Brazilian Portuguese.

## Instructions

0. First, open a [new issue](https://github.com/vnen/godot-editor-ptbr/issues/new) and
   claim a file to work on (the files are numbered from 1-19). See if it's not claimed already.
   There are about 70 strings per file to translate.
0. Fork this repository and start working on the translation (instructions [below](#how-to-translate)).
0. Push the changes to your fork.
0. Start a [Pull Request](https://github.com/vnen/godot-editor-ptbr/compare) from
   your fork. Be sure to include "Closes #nnn" in the message, being "nnn" the number
   of your opened issue.
0. I'll review and approve as soon as possible.

If you're not familiar with Git, you can also download the file from GitHub and send me the result
later in any other way, such as a Dropbox link in the original issue.

Once this is all done, I'll push the new translation to the
[official Godot repository](https://github.com/godotengine/godot). And, of course,
I'll thank you all.

Feel free to review the other translators' work and point out issues.

## How to translate

The easiest way is to download and install a program specific for this purpose.
A good free one is [Poedit](https://poedit.net), available for all platforms. With it
you can open the `.po` file you chose to edit and start translating through its interface.

If you need to set the default language, use "pt_BR" (Brazilian Portuguese).
Also, try to keep the files in UTF-8 encoding.

You can also use a regular text editor, such as [Notepad++](https://notepad-plus-plus.org),
and fill the empty quotes after the `msgstr` word, translating the `msgid` just above it.

## License

This follows the same license as the Godot Engine source code.
