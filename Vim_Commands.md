In Vim, you manage text using different modes.
To use any command, you must first press Esc to enter Normal Mode.

Insert Text

These commands switch you into Insert Mode. Press Esc when you are done typing to return to Normal Mode.
i – Insert text before the cursor.
a – Append text after the cursor.
I – Insert text at the beginning of the current line.
A – Append text at the end of the current line.
o – Open a new line below the cursor.
O – Open a new line above the cursor.

Copy (Yank) Text

Vim refers to copying as yanking.
yy – Copy the entire current line.
3yy – Copy three lines starting from the cursor.
yw – Copy from the cursor to the end of the word.
y$ – Copy from the cursor to the end of the line.

Paste (Put)

TextVim refers to pasting as putting.
p – Paste the copied text after the cursor (or on the line below).
P – Paste the copied text before the cursor (or on the line above).Copy and Paste using Visual Selection.
This is the easiest way to highlight specific text blocks.Press v to start selecting character by character (or V to select whole lines).Move your cursor using the arrow keys to highlight your text.Press y to copy the highlighted section.Move to your desired destination and press p to paste.

System Clipboard (Copying to/from outside Vim)

By default, Vim has its own internal clipboard. To interact with your computer's regular system clipboard, use the + register:"+y – Copy the selected text to your system clipboard."+p – Paste text from your system clipboard into Vim.
