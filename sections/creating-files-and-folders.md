[<<< Previous](navigation.md) | [Next >>>](creating_a_cheat_sheet.md)

# Creating files and folders

## Creating a file

So far, we've only performed commands that give us information. Let's use a command that creates something on the computer. 

First, make sure you're in the home directory:

```
$ pwd
/Users/patrick
```

Let's move to the Desktop folder, or "change directory" with `cd`:

```
cd Desktop
```

Once you've made sure you're in the Desktop folder with `pwd`, let's try a new command:

```
touch foo.txt
```

If the command succeeds, you won't see any output. Now move the terminal window and look at your "real" desktop, the graphical one. See any differences? If the command was successful and you were in the right place, you should see an empty text file called "foo.txt" on the desktop. Pretty cool, right?

## Handy tip: up arrow

Let's say you liked that "foo.txt" file so much you'd like another! In the terminal window, press the "up arrow" on your keyboard. You'll notice this populates the line with the command that you just wrote. You can hit "Enter" to create another "foo.txt," (note - [`touch`](https://en.wikipedia.org/wiki/Touch_(Unix)) command will not overwrite your document nor will it add another document to the same directory, but it will update info about that file.) or you could use your left/right arrows to change the file name to "foot.txt" to create something different. 

As we start to write more complicated and longer commands in our terminal, the "up arrow" is a great shortcut so you don't have to spend lots of time typing. 

## Creating folders

Let's create a project folder in our home directory so that we can keep all our work in one place. We'll then create a folder inside that where we'll keep the work we're doing for the rest of the workshop.

First, let's check to make sure we're still in the Desktop folder with `pwd`:

```
$ pwd
/Users/patrick/Desktop
```

Once you've double-checked you're in Desktop, we'll use the `mkdir` or "make directory" command to make a folder called "projects":


	mkdir projects

Now run `ls` to see if a projects folder has appeared. Once you confirm that the projects folder was created successfully, `cd` into it. 

```
$ cd projects
$ pwd
/Users/patrick/Desktop/projects
```

It should be visible on your graphical desktop, just like the `foo.txt` file we created earlier. 

Let's create one more folder: a field kit folder for this workshop. We'll use this folder while learning Git.

	mkdir field_kit
	
Finally, use `cd` to enter the folder, and then `pwd` to confirm that it was successful.	

```
$ cd field_kit
$ pwd
/Users/patrick/Desktop/field_kit
```

[<<< Previous](navigation.md) | [Next >>>](creating_a_cheat_sheet.md)

## Example

![Creating files and folders](make-file-folder.gif)
