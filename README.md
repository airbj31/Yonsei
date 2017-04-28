# Linux commands

## File/Directory Command

- [ls](http://man7.org/linux/man-pages/man1/ls.1.html) ls command shows the list of files and directories in the specific directory

[cd]

[mkdir]

[rmdir]

[cp]

[mv]

[rm]

[chmod]

[chown]

ls – directory listing
ls -al – formatted listing with hidden files
cd dir - change directory to dir
cd – change to home
pwd – show current directory
mkdir dir – create a directory dir
rm file – delete file
rm -r dir – delete directory dir
rm -f file – force remove file
rm -rf dir – force remove directory dir *
cp file1 file2 – copy file1 to file2
cp -r dir1 dir2 – copy dir1 to dir2; create dir2 if it
doesn't exist
mv file1 file2 – rename or move file1 to file2
if file2 is an existing directory, moves file1 into
directory file2
ln -s file link – create symbolic link link to file
touch file – create or update file
cat > file – places standard input into file
more file – output the contents of file
head file – output the first 10 lines of file
tail file – output the last 10 lines of file
tail -f file – output the contents of file as it
grows, starting with the last 10 lines



## User/Group management

- You need a admin privilege to manage user/groups

-

#


# Grid Engine

- [qsub]()
- [qhold]()
- [qrls]()
- [qmod]()
- [qalter]()
- [qdel]()
- [qstat]()
- [qhost]()

## some built-in script to handle job.

- [qsub.sh](./gridEngine/qsub)

- [qdel_seq.sh](./gridEngine/qdel_seq)

- [qcount](./gridEngine/qcount)

- [qsuspend](./gridEngine/qsuspend)

- [qresume](./gridEngine/qresume)

## 

##
