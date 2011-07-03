Align Assignments -- Sublime Text 2 Plugin
===========================================
Sometimes I like to align my assignment statements in a given selection.
Not everyone likes to do this, but it occassionally makes it easier for me to read.
This features was in TextMate and I loved it. Migrating to Sublime Text 2 I missed it,
so here it is for Sublime Text 2

Align assignment statements for a selection

**This:**

	variable = 1
	other_variable = 2
	yet_another_variable = 3

**Becomes This:**

	variable             = 1
	other_variable       = 2
	yet_another_variable = 3

**And This:**

	$array = array(
                   "key" => $value,
                   "other_key" => $other_value,
                   "yet_another_key" => $yet_another_value
                  );

**Becomes This:**

	$array = array(
                   "key"             => $value,
                   "other_key"       => $other_value,
                   "yet_another_key" => $yet_another_value
                  );



Install (OS X)
----------------------------
Drop align_assigments.py into:

~/Library/Application\ Support/Sublime\ Text\ 2/Packages/User/

If you would like to bind it to the same key combination as TextMate, add this:

*{ "keys": ["super+alt+]"], "command": "align_assignments" }*

to your:

~/Library/Application\ Support/Sublime\ Text\ 2/Packages/User/Default (OSX).sublime-keymap



