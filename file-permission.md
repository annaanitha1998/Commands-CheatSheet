| Commands            | Description                                                      | Input sample  | Output sample                 |
| ------------------- | ---------------------------------------------------------------- | ------------- | ----------------------------- |
| `ls -l [file name]` | List detailed information for the file including file-permission | `ls -l a.txt` | File permission will be shown |
| `chmod [OPTIONS] MODE FILE`. | Change the file permission of the file | chmod g=r filename| Give the members of the group permission to read the file, but not to write and execute it|
| `chmod -R 755 [repo]` | Change the repo permission recursively to 755. 7=rwx 5=r-x 5=r-x | `chmod -R 755 images` | All files and folder inside of `images` folder get 755 permission`|