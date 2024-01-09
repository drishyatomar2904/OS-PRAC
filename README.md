# Linux
#linux commands execution in os prac 1
export "PS1=$ "

$ pyt.txtwd
pwd

/home/cg/root/659cdd0923335
export "PS1=$ "
$ mkdir
mkdir
mkdir: missing operand
Try 'mkdir --help' for more information.
export "PS1=$ "

$ mkdir rt
mkdir rt

export "PS1=$ "
$ cd rt
cd rt

export "PS1=$ "

$ touch yt.txt
touch yt.txt

export "PS1=$ "

$ ls 
ls 

rt  yt.txt
export "PS1=$ "

$ nano yt
nano yt

bash: nano: command not found
export "PS1=$ "

$ nano yt.txt
$ nano yt.txt
bash: $: command not found
export "PS1=$ "

$ cd..
cd..
bash: cd..: command not found
export "PS1=$ "

$ cd ..
$ cd ..
cd ..

export "PS1=$ "

$ touch mt.txt
touch mt.txt

export "PS1=$ "
export "PS1=$ "

$ mv mt.txt rt
mv mt.txt rt

export "PS1=$ "
export "PS1=$ "

$ cp rt/yt.txt
cp rt/yt.txt

export "PS1=$ "
cp: missing destination file operand after 'rt/yt.txt'
Try 'cp --help' for more information.
export "PS1=$ "
$ cd rt
cd rt
export "PS1=$ "

$ ls
ls

export "PS1=$ "
rt  yt.txt
export "PS1=$ "

$ cp rt/yt.txt 659cdd0923335/yt1.txt
export "PS1=$ "
cp rt/yt.txt 659cdd0923335/yt1.txt

cp: cannot stat 'rt/yt.txt': No such file or directory
export "PS1=$ "$ ls
export "PS1=$ "
ls

rt  yt.txtexport "PS1=$ "

$ cp yt.txt rt/yt1.txt
export "PS1=$ "
cp yt.txt rt/yt1.txt

export "PS1=$ "

$ cd rt
$ ls
mt.txt  yt1.txt
$ cd ..
export "PS1=$ "
cd ..

export "PS1=$ "

$ ls rt
ls: cannot access 'rt': No such file or directory$ 
export "PS1=$ "
export "PS1=$ "$ ls
rt  yt.txt
$ ls rt
mt.txt  yt1.txt
$ cat yt1.txt mt.txt
cat yt1.txt mt.txt

cat: yt1.txt: No such file or directory
cat: mt.txt: No such file or directory
export "PS1=$ "

$ ls
ls
rt  yt.txt
export "PS1=$ "

$ cat yt.txt mt.txt
cat yt.txt mt.txt

export "PS1=$ "
cat: mt.txt: No such file or directory
export "PS1=$ "

$ ls
rt  yt.txt
$ touch mt.txt
touch mt.txt

export "PS1=$ "

$ cat yt.txt mt.txt
cat yt.txt mt.txt

export "PS1=$ "
export "PS1=$ "
$ 
..............................................................................................................................................................................................................................................................................
#work of each command used here

1. `export "PS1=$ "`: Sets the appearance of your command prompt.

2. `pwd`: Shows you which directory you are currently in.

3. `mkdir`: Makes a new directory (folder).

4. `cd rt`: Changes into the "rt" directory.

5. `touch yt.txt`: Creates a new empty file called "yt.txt."

6. `ls`: Lists the files and folders in the current directory.

7. `nano yt.txt`: Tries to open the "yt.txt" file for editing (but nano is not available in this case).

8. `cd..`: Tries to move up one directory, but there should be a space between `cd` and `..`.

9. `touch mt.txt`: Creates a new empty file called "mt.txt."

10. `mv mt.txt rt`: Moves the "mt.txt" file into the "rt" folder.

11. `cp rt/yt.txt`: Tries to copy "yt.txt" from the "rt" folder, but it needs a destination.

12. `cd rt`: Changes into the "rt" folder.

13. `ls`: Lists the files and folders in the "rt" folder.

14. `cp rt/yt.txt 659cdd0923335/yt1.txt`: Tries to copy "yt.txt" to a folder named "659cdd0923335" with a new name "yt1.txt," but there's a typo.

15. `cd ..`: Goes back to the previous (parent) directory.

16. `ls rt`: Tries to list the contents of the "rt" folder, but encounters an error because "rt" is not in the current directory.

17. `ls`: Lists the files and folders in the current directory.

18. `cat yt1.txt mt.txt`: Tries to show the contents of "yt1.txt" and "mt.txt," but there's an error because "yt1.txt" doesn't exist.

19. `touch mt.txt`: Creates a new empty file named "mt.txt."

20. `cat yt.txt mt.txt`: Shows the contents of "yt.txt" and "mt.txt."

    



