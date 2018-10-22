
[<<< Previous](what-is-the-command-line.md) | [Next >>>](why-is-the-command-line-useful.md)

# Text editors 

## What is text?

Plain text and formatted text are not the same. Words on a screen may have hidden formatting. Many of us grew up using Microsoft Word and don't realize how much is going on behind the words shown on the screen. For the purposes of communicating with the computer and for easier movement between different programs, we need to use text without hidden formatting.

![Word Doc](worddoc.png)

If you ask the command line to read that file, this Word .docx file will look something like this

![Cat Word Doc](CatWordDoc.png)

Word documents which look like "just words" are actually comprised of an archive of extensible markup language (XML) instructions that only Microsoft Word can read. Plain text files can be opened in a number of different editors and can be read within the command line.

## Plain text

Basically, plain text is the bare minimum necessary to depict characters and symbols in a file.

According to the [Unicode Standard](https://www.unicode.org/versions/Unicode6.1.0/), 

> "Plain text is a pure sequence of character codes; plain Unicode-encoded text is therefore a sequence of Unicode character codes."

Plain text has two main properties in regard to rich text:

1. "plain text is the underlying content stream to which formatting can be applied. Plain text is public, standardized, and universally readable."
2. Plain text shows its cards-- if it's marked up, the markup will be human readable. Plain text can be moved between programs more fluidly and can respond to programmatic manipulations. Because it is not tied to a particular font or color or placement, plain text can be styled externally.

The opposite of plain text is rich text (sometimes denoted by the Microsoft rich text format ".rtf" file extension) or "enriched text" (sometimes seen as an option in email programs). In rich text files, plain text is elaborated with formatting specific to the program in which they are made.

## Text editors

An important tool for programming and working in the command line is a text editor. A text editor is a program that allows you to edit plain text files, such as .txt, .csv, or .md. Text editors are not used to edit rich text documents, such as .docx or .rtf, and rich text editors should not be used to edit plain text files. This is because rich text editors will add many invisible special characters that will prevent programs from running and configuration files from being read correctly. 

While it doesn't really matter which text editor you choose, you should try to become comfortable with at least one text editor. 

## Default recommendation

Choosing a text editor has as much to do with personality as it does with functionality. Graphical user interfaces (GUIs), user options, and "hackability" vary from program to program. For our workshops, we will be using [Visual Studio Code](https://code.visualstudio.com/). Not only is Visual Studio Code free and open source, but it is also consistent across OSX, Windows, and Linux systems.

Download VS Code using these [instructions](https://github.com/DHRI-Curriculum/install/blob/master/sections/vscode.md) now.

[<<< Previous](what-is-the-command-line.md) | [Next >>>](why-is-the-command-line-useful.md)
