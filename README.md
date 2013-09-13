Vim cheat sheet
===============

Vim is famous for its steep learning curve. Most of the cheat sheet I have seen are extensive and organized by topics. This is an obvious choice when you master this editor and are looking for an command that you know existing. I also find it overwhelming for beginners.

This cheat sheet is organized by "levels", from the very minimal commands. Any next levels will help you to gain more time.

Level 0 (minimal and survival)
==============================

```j``` Move down

```k``` Move up

```m``` Move right

```h``` Move left

```i``` Switch to editor mode and insert before cursor

```esc``` Quit editor mode

```x``` Delete a single char behind the cursor 

```:q!``` Quit and cancel edits

```:wq``` Quit and write edits


Level 1 (quick win)
===================

```ctrl-d``` 1/2 page down

```crtl-u``` 1/2 page up

```a```  Switch to editor mode and insert after cursor (better than i + move right)

```dd```  Delete a full line


Level 2 (more quick win)
========================

```G``` Go to end of file

```gg``` Go to head of file

```$``` Go to end of line (useful with very large lines)

```A``` Go to the end of line and editor mode


Level 3 (copy and paste)
========================

```v + move cursor``` Select text

```V + move cursor``` Select lines

```y``` Copy (yank)

```d``` Cut

```p``` Paste after the current position 


Level 4 (for developers)
========================

```ctrl-x ctrl-o```Omni completion

```:only``` Remove this damn double screen from the omni completion


Contribute
==========

Suggestion and contribution are welcome through pull requests. Keep in mind the spirit of this cheat sheet. Levels are organized from the most mandatory and probably less effective commands, to the most productive ones.
