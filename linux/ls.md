# ls

## Name

  ls - list directory contents
  
## Descriptions

**List** information  about the FILEs (the current directory by default).  Sort entries alphabetically if none of -cftuvSUX nor --sort.

Mandatory arguments to long options are mandatory for short options too.

 -a, --all : 
  + do not ignore entries starting with .

 -A, --almost-all
  + do not list implied . and ..

 --author
  + with -l, print the author of each file

 -b, --escape 
  + print octal escapes for nongraphic characters

 --block-size=SIZE 
  + use SIZE-byte blocks

 -B, --ignore-backup 
  + do not list implied entries ending with ~

 -c     with -lt: sort by, and show, ctime (time of last modification of file  status
              information) with -l: show ctime and sort by name otherwise: sort by ctime

 -C     list entries by columns

 --color[=WHEN]
  + control  whether  color  is  used  to  distinguish  file  types.  WHEN may be ‘never’, ‘always’, or ‘auto’

 -d, --directory
  + list directory entries instead of contents, and do not  dereference  symbol links

 -D, --dired
  + generate output designed for Emacs’ dired mode

 -f     
  + do not sort, enable -aU, disable -lst

 -F, --classify
  + append indicator (one of */=>@|) to entries

 --file-type
  + likewise, except do not append ‘*’

 --format=WORD
  + across  -x,  commas -m, horizontal -x, long -l, single-column -1, verbose -l, vertical -C

 --full-time
  + like -l --time-style=full-iso

 -g     
  + like -l, but do not list owner

 -G, --no-group
  + like -l, but do not list group

 -h, --human-readable
  + with -l, print sizes in human readable format (e.g., 1K 234M 2G)

 --si   
  + likewise, but use powers of 1000 not 1024

 -H, --dereference-command-line
  + follow symbolic links listed on the command line

 --dereference-command-line-symlink-to-dir
  + follow each command line symbolic link that points to a directory

 --hide=PATTERN
  + do not list implied entries matching shell PATTERN (overridden by -a or -A)

 --indicator-style=WORD 
  + append indicator with style WORD to entry names: 
    + none (default), slash (-p), file-type (--file-type), classify (-F)

 -i, --inode
  + with -l, print the index number of each file

 -I, --ignore=PATTERN
  + do not list implied entries matching shell PATTERN

 -k     
  + like --block-size=1K

 -l     
  + use a long listing format

 -L, --dereference
  + when showing file information for a symbolic link, show information  for  the file the link references rather than for the link itself
  
 -m     
  + fill width with a comma separated list of entries

 -n, --numeric-uid-gid
  + like -l, but list numeric user and group IDs

 -N, --literal
  + print raw entry names (don’t treat e.g. control characters specially)

 -o 
  + like -l, but do not list group information

 -p, --indicator-style=slash
  + append / indicator to directories

 -q, --hide-control-chars
  + print ? instead of non graphic characters

 --show-control-chars
  + show  non graphic characters as-is (default unless program is ‘ls’ and output is a terminal)

 -Q, --quote-name
  + enclose entry names in double quotes

 --quoting-style=WORD
  + use quoting style WORD for entry names: literal, locale, shell, shell-always, c, escape

 -r, --reverse
  + reverse order while sorting

 -R, --recursive
  + list subdirectories recursively

 -s, --size
  + with -l, print size of each file, in blocks

 -S     
  + sort by file size

 --sort=WORD
  + extension  -X,  none  -U,  size  -S, time -t, version -v, status -c, time -t, atime -u, access -u, use -u

 --time=WORD
  + with -l, show time as WORD instead of modification time: atime, access,  use, ctime or status; use specified time as sort key if --sort=time

 --time-style=STYLE
  + with -l, show times using style STYLE: full-iso, long-iso, iso, locale, +FORMAT.  FORMAT is interpreted like ‘date’; if  FORMAT  is  FORMAT1<newline>FORMAT2,  FORMAT1  applies  to  non-recent files and FORMAT2 to recent files; if STYLE is prefixed with ‘posix-’, STYLE takes effect only  outside  the  POSIX locale

 -t     
  + sort by modification time

 -T, --tabsize=COLS
  + assume tab stops at each COLS instead of 8

 -u     
  + with  -lt:  sort by, and show, access time with -l: show access time and sort by name otherwise: sort by access time

 -U     
  + do  not  sort;  list  entries  in  directory  order.   In  combination   with one_per_line format ‘-1’, it will show files immediately and it has no memory limitations.

 -v     
  + sort by version

 -w, --width=COLS
  + assume screen width instead of current value

 -x     
  + list entries by lines instead of by columns

 -X     
  + sort alphabetically by entry extension
 
 -1     
  + list one file per line
       
**SELinux options:**

 --lcontext
  + Display security context.   Enable -l. Lines will probably be  too  wide  for most displays.

 -Z, --context
  + Display  security  context  so it fits on most displays.  Displays only mode, user, group, security context and file name.

 --scontext
  + Display only security context and file name.

 --help 
  + display this help and exit

 --version
  + output version information and exit

 SIZE may be (or may be an integer optionally followed by) one of following: kB 1000, K 1024, MB 1000*1000, M 1024*1024, and so on for G, T, P, E, Z, Y.

 By  default, color is not used to distinguish types of files.  That is equivalent to using --color=none.  Using the --color option without the optional WHEN argument  is equivalent  to using --color=always.  With --color=auto, color codes are output only if standard output is connected to  a  terminal  (tty).   The  environment  variable LS_COLORS  can influence the colors, and can be set easily by the dircolors command.

Exit status is 0 if OK, 1 if minor problems, 2 if serious trouble.

## AUTHOR
       
 Written by Richard Stallman and David MacKenzie.

## REPORTING BUGS

 Report bugs to <bug-coreutils@gnu.org>.

## COPYRIGHT

Copyright © 2006 Free Software Foundation, Inc.
This is free software.  You may redistribute copies of it under the terms of the [GNU
General  Public  License](http://www.gnu.org/licenses/gpl.html).   There is NO WAR-
RANTY, to the extent permitted by law.

## SEE ALSO

 The full documentation for ls is maintained as a Texinfo manual.  If the info and ls programs are properly installed at your site, the command

```
  info ls
```

 should give you access to the complete manual.
