# placeMarkers #

* Authors: Noelia, Chris.
* download [stable version][1]
* download [development version][2]

This addon is used for saving and searching specific text strings or bookmarks. It can be used  on web pages or documents in NVDA's browse mode. It can also be used for saving or searching strings of text in multi-line controls; in this case, if it's not possible to update the caret, the corresponding string will be copied to the clipboard, so that it can be searched using other tools.
The plugin saves the specified strings and bookmarks to files whose name is based on the title and URL of the current document.
This addon is based on SpecificSearch and Bookmark&Search, developed by the same author. You should uninstall them to use this one, since they have common keystrokes and features.

## Key Commands: ##

*	control+shift+NVDA+f: Opens a dialog with an edit box that shows the last saved search; in this dialog you can also select the previously saved searches from a combo box or remove the selected string from the history using a checkbox. You can choose if the text contained in the edit box will be added to the history of your saved texts. Finally, choose an action from the next group of radio buttons (between Search next, Search previous or Don't search), and specify if NVDA will make a case sensitive search. When you press okay, NVDA will search for this string.
*	control+shift+NVDA+k: Saves the current position as a bookmark. If you want to provide a name for this bookmark, select some text from this position before saving it.
*	control+shift+NVDA+delete: Deletes the bookmark corresponding to this position.
*	NVDA+k: Moves to the next bookmark.
*	shift+NVDA+k: Moves to the previous bookmark.
*	control+shift+k: Copies the file name where the place markers data will be saved to the clipboard, without an extension.
*	alt+NVDA+k: Opens a dialog with the bookmarks saved for this document. You can write a note for each bookmark; press Save note to save changes. Pressing OK you can move to the selected position.

Note: Sometimes this doesn't work on browsers like Firefox. If it happens, please refresh the buffer pressing NVDA+f5 and try to use the dialog again, or move to the bookmark from the document using NVDA+k.


## Place markers Submenu (NVDA+N) ##

Using the Place markers submenu under NVDA's Preferences menu, you can access:

*	Specific search folder: opens a folder of specific searches previously saved.
*	Bookmarks folder: Opens a folder of the saved bookmarks.
*	Copy placeMarkers folder: You can save a copy of the bookmarks folder.
*	Restore placeMarkers: You can restore your bookmarks from a previously saved placeMarkers folder.

Note: The bookmark position is based on the number of characters; and therefore in dynamic pages it is better to use the specific search, not bookmarks.


## Changes for 8.0 ##
*	Removed fragment identifiers from bookmark filenames, which can avoid issues in the VitalSource Bookshelf ePUB reader.
*	Added a Notes dialog, to associate comments for saved bookmarks and move to the selected position.

## Changes for 7.0 ##
*	The dialog to save a string of text for specific search has been removed. This functionality is now included in the Specific search dialog, which has been redesigned to allow different actions when pressing the OK button.
*	The visual presentation of the dialogs has been enhanced, adhering to the appearance of the dialogs shown in NVDA.
*	Performing a Find Next or Find Previous command in Browse Mode will now correctly do a case sensitive search if the original Find was case sensitive.
*	Requires NVDA 2016.4 or later.
*	Now you can assign gestures to open the Copy and Restore place markers dialogs.
*	NVDA will present a message to notify when place markers have been copied or restored with the corresponding dialogs.

## Changes for 6.0 ##
* When the add-on features are not usable, gestures are sent to the corresponding application.

## Changes for 5.0 ##
* Added case sensitive search.
* Removed option to open documentation from Place markers menu.
* More intuitive key commands.

## Changes for 4.0 ##
* Removed fragment identifiers from bookmark filenames, which can avoid issues in ePUBREADER Firefox add-on.
* Add-on help is available from the Add-ons Manager.

## Changes for 3.1 ##
* Translation updates and new language.
* Bookmark position is not announced in skim reading.

## Changes for 3.0 ##
* Added support for skim reading.

## Changes for 2.0 ##
* Added options to save and delete different searches for each file.
* Fixed bug which broke when paths contained non latin characters.
* Shortcuts can now be reassigned using the NVDA gesture input dialog.

## Changes for 1.0 ##
* Initial version.
* Translated into: Brazilian Portuguese, Farsi, Finnish, French, Galician, German, Italian, Japanese, Korean, Nepali, Portuguese, Spanish, Slovak, Slovenian, Tamil.

[1]: http://addons.nvda-project.org/files/get.php?file=pm

[2]: http://addons.nvda-project.org/files/get.php?file=pm-dev
