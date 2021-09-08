# EnvBio2021-Unix

## List of commands


### Navigation

| **Command**| **Function**| **Syntax**|
| :---         |     :---     |          :--- |
| `pwd`   | print working directory;returns the path to your current location (directory)    | `pwd`    |
| `ls`   | list contents; if location is not given, lists contents of current location      | `ls ..` #list contents of parent directory  |
| `cd`   | change directory       | `cd  ~`  #go to home directory |



### File/Directory operations

| **Command**| **Function**| **Syntax**|
| :---         |     :---     |          :--- |
| `man`  | manual page; help   | `man` *command* e.g. `man mv`     |
| `cp`   | copy files/directories    | `cp` *source_file* *destination_file* |
| `mkdir`  | make directory   | `mkdir` folder     |
| `cp`   | copy files/directories from source to destination  | `cp` *source_file* *destination_file*  |
| `mv`    | move files/directories  from source to destination| `mv` *source_file* *destination_file* |
| `rm`    | remove (delete) file or folder; use with caution, cannot be recovered| `rm` *file*|
| `find`    | find a file/directory | `find . –name` *file*|


### File manipulation

| **Command**| **Function**| **Syntax**|
| :---         |     :---     |          :--- |
| `touch`    | create file | `touch` *file8 |
| `cat`    | read and/or concatenate files| `cat` *file1* *file2* *file3* |
| `less` or `more`   | view file withe less or more options  | `less` *file* |
| `head`    | show first few lines of file| `head -n 10` *file* #show first 10 lines|
| `tail`    | show last few lines of file| `tail -n 1` *file* #show last line|
| `grep`  | searches a particular pattern of characters; displays all lines that contain that pattern   | `grep` "pattern" *file*    |
| `sed`   | stream editor; search, find and replace, insertion or deletion    | `sed`'s/sting_old/string_new/' *file* |
| `sort`  | sort file   | `sort` *file*    |
| `uniq`  | display unique lines   | `uniq` *file*    |
| `cut`  | break files horizontally   | `cut -d` *delimiter* `-f` *number* file    |
| `paste`  | combine files side by side   | `paste` *file1* *file2*    |
| `wc`  | word count   | `wc` *file*    |

