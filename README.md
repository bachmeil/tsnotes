# tsnotes

tsnotes stands for "timestamped notes". I tested out Gemini's code creation abilities. With the exception of some CSS issues, Gemini created this app from scratch in just a few seconds. All I did was give it some prompts and enough debugging info to fix the CSS problem.

There's help in the hamburger menu, but here's the quick overview:

- Type your note into the text box. Hit the button to save it or type Ctrl-Enter. All data is stored in localStorage on your computer. This can easily be verified by looking at the source code. That means you have full responsibility for backups, have to figure out a solution for saving, etc.
- Open the menu to download notes, import previously exported notes, or clear all notes.

  - Notes are downloaded in a particular CSV format. You are free to open that file in a spreadsheet, in R, etc.
  - Imports require the same CSV format as export. You can import any notes in CSV format as long as you have the right columns. Importing adds those notes to your existing notes. If you don't want that, you'll need to clear all notes first.
  - Since clearing all notes is the nuclear option (you're deleting the only copy in existence), you'll have to confirm the deletion twice.

I intended this to be an experiment, but it's actually kind of valuable. It's released under the Boost license (not sure why that matters when it's AI-generated) so do whatever you want with it, basically. Ask Gemini/Copilot to customize it for your preferences or needs.