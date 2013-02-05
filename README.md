Paste-Into-DiffMerge
====================

Mac Automator UI to allow pasting into DiffMerge.

DiffMerge (http://www.sourcegear.com/diffmerge/) is a powerful diff/merge tool that shows intra-line changes.  However, it requires text to be in existing files before they can be opened.

PasteDiff is an Automator Application which takes in two text inputs, creates appropriate temporary files, and passes them into DiffMerge.
PasteUnidiff is another Automator Application which takes in a text input (a unified diff), creates appropriate temporary files, and passes them into DiffMerge so you can see the intra-line changes.  (This is very rough right now)

You can open the .app files in Automator to edit the workflow.

