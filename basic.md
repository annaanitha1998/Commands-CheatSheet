| Commands                    | Description                             | Input sample                | Output sample                                                                           |
| --------------------------- | --------------------------------------- | --------------------------- | --------------------------------------------------------------------------------------- |
| `sudo [command]`            | Execute the command with root privilege | `sudo -h`                   | List help manual for the sudo command                                                   |
| `pwd`                       | Path of present working directory       | `pwd`                       | /home/users/nit/images                                                                  |
| `ls`                        | List files in present directory         | `ls`                        | goa.jpg commands.txt                                                                    |
| `ls -a`                     | List hiden files as well                | `ls -a`                     | goa.jpg commands.txt passwd.txt                                                         |
| `ls -l`                     | List files with detailed information    | `ls -l`                     | drwxrwxrwx 1 nit nit 145201 Feb 29 12:17 goa.jpg                                        |
| `cd [directory name]`       | Change directory                        | `cd documents`              | The file path got changed to documents directory                                        |
| `cp [source] [destination]` | Copy a file                             | `cp commands.txt basic.txt` | Will copy the content from the commands.txt(source) to basic.txt(destination            |
| `mkdir [directory name]`    | To make a directory                     | `mkdir sample-dir`          | sample-dir will be created in your current directory, it can be checked with ls command |
| `rmdir [directory name]`    | To remove a empty directory             | `rmdir sample-dir`          | sample-dir will get deleted                                                             |
| `touch [file name]`         | To create a blank file                  | `touch index.html`          | index.html will be created in current repository                                        |
| `cat [file name]`         | To display the raw content of the file                  | `cat index.html`          | file content will get displayed                                        |
| `lsof i:<port_number>	`| To see whether the provided port is openly available or not.| `lsof i:9915`  | To see whether the 9915 port is available or not|
| `kill -9 $(lsof -t -i tcp:<port_number>)	`| To kill tcp port.| `kill -9 $(lsof -t -i tcp:9915)`  | To kill TCP port 9915
|