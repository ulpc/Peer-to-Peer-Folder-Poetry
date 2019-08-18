![](https://github.com/melaniehoff/Peer-to-Peer-Poetry/blob/master/folder-cities.jpg)

## Peer-to-Peer Folder Poetry

What if we could build and live in a new kind of digital city that transforms our online networks from a corporate-owned service to a community-run medium of shared placemaking? In this workshop we will collectively create a peer-to-peer city using the structure of nested folders and [DAT](https://dat.foundation/). Taking a closer look at the common practice of computer organization using folders and files and taking a page out of Italo Calvino's book, Invisible Cities, we will explore folder structures as a new kind of poetic form and DAT as a way to build digital spaces with and for our networks.


This workshop assumes no coding experience and simultaneously takes the position that everyone who interacts with computers in some way is already a programmer.
 
## Please Review these Resources Before Class
- [What is DAT and why Peer-to-peer?](https://p2p.newcomputers.group/guides/why-self-host.html)
- [P2P Folder Poetry Arena Channel](https://www.are.na/melanie-hoff/peer-to-peer-folder-poetry)


## Session Objectives

- To create a space where we are getting intimate with computers and writing poetry with their logic
- To develop a taste for creating emotive and community centered software
- To introduce [DAT](https://dat.foundation/) and navigating the Command Line with [Bash](https://en.wikipedia.org/wiki/Bash_(Unix_shell))
- To create poetry through building a folder-based city on the peer-to-peer web for each other to inhabit

## Vocabulary
**Word** | **Definition**
--- | ---
Folder Poetry| The practice of using the structure of computer folder organization as a new kind of [poetic form](https://en.wikipedia.org/wiki/Poetry#Forms) like the [haiku](https://en.wikipedia.org/wiki/Haiku) or [iambic pentameter](https://en.wikipedia.org/wiki/Iambic_pentameter). By naming and nesting folders and files, we can create unfolding narratives, rythmic prose, and choose-your-own-adventure poetry.
terminal | A desktop application to control and make changes to your operating system by typing text commands. In this class we'll use the terminal to create folder poetry.
terminal commands | text commands to control your computer when entered into a command promt like the terminal. The commands we'll learn will be in a language called Bash.
Bash | is the programming language we use in the terminal, often one line at a time, but we can also put Bash code in a file and run that file.
Peer-to-Peer | Peer-to-peer computing is a way to make distributed networks in which each computer can act as a server for the others, allowing shared access to files without the need for a central server.
DAT | is a data distribution tool with for publishing on peer-to-peer networks.
folder | (also referred to as directory) is an organizational regime imposed on your computer used to store and organize files and other folders
file | is an object on a computer which stores data, information, settings, or commands to be used with various computer programs
file types/formats/extensions | indicate how data has been stored and how to read or open files in specific programs. for example, `.txt` files open in a text editor, `.jpg` files open in an image viewer/editor. full list of file formats and extensions [here](https://en.wikipedia.org/wiki/List_of_file_formats)
file path | tells you the location of a file in a system. for example `users/username/desktop/folder_poetry_club`


## File organization
- Naming files and folders
    - All lowercase
    - No spaces, under scores and dashes are ok (for example, `my_folder` or `my-folder`)
- File types
    - `.txt`, `.html`, `.css`, `.js`
- Mind your file path
    - `/../../../../../`
    
Every time you make a folder or rename a file on your computer, the actions you take through moving your mouse and clicking on buttons, have an equivalent text command in Bash. In fact, even when you do this through a visual interface (called a GUI) text commands are still being fired in the background which eventually compile to binary. Using bash in the terminal is a way to get a little closer to the metal and a little further along in uncovering the mechanics of our most common devices.
    

# To create our folder poetry, we will use Bash in the terminal

## Bash Commands

| Command                                                 | Description                               | Verb   |
|-----------------------------------------|-------------------------------------------|--------|
| `cd`                                      | change directory                          | move   |
| `cd ..`                                   | change directory one level back           | return |
| `ls`                                      | list contents of directory                | look   |
| `pwd`                                     | parent working directory                  | where  |
| `open .`                                  | open folder with finder                   | open   |
| `open filename.txt`                       | opens file in Text Edit                   | open   |
| `cat`                                     | print contents                            | print  |
| `touch filename.txt`                      | create a file named filename.txt          | create |
| `mkdir foldername/`                       | create a folder named filename.txt        | create |
| `rm filename.txt`                         | remove file                               | remove |
| `rm foldername/`                          | remove folder                             | remove |
| `cp filename.txt filename2.txt`           | copy file .                               | copy   |
| `say "hello, what is poetic computation"` | say words out loud    | speak  |
| `man cd`                                  | show the manual for 'cd'. Press q to quit | define |

## Keyboard Terminal Commands
| Command         | Description            | Verb     |
|----------------------|------------------------|----------|
| Up + Down Arrow keys | scroll through history | scroll   |
| Tab Key              | autocomplete           | complete |

## Other useful Bash code
| Code                                                        | Description                                          |
|-----------------------------------------------------------------------------------|------------------------------------------------------|
| `open ~/.bash_profile`                                                              | opens your bash profile in a text editor                 |
| `source ~/.bash_profile`                                                            | reloads your bash profile (for after making changes) |
| `export PS1="🌸 \h ✸ \w ⇢ "`                                                        | to change your bash prompt                           |
| `for i in {1..2000}; do printf ' ♡ → ➩ ➪ ➫ ➬ ➭ ➮  '; done;`                      | to make a for loop                            |                   |
| `bash myfile.sh`                                                                    | to run a bash file                                   |
| `curl sfpc.io`                                                                      | prints the html of a website                         |    
    
 **_Check out a related workshop I taught recently with SFPC in Detroit called Folder Poetry: [https://github.com/melaniehoff/folderpoetry/](https://github.com/melaniehoff/folderpoetry/blob/master/README.md)_**
⇢ [folderpoetry.club](http://www.folderpoetry.club)
    
    






