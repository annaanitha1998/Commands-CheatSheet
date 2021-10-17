| Commands                                | Description                          | Input sample                      | Output sample                                                           |
| --------------------------------------- | ------------------------------------ | --------------------------------- | ----------------------------------------------------------------------- |
| `adduser [username]`                    | To add the new linux user            | `adduser myuser1`                 | myuser1 user will get added in the linux system after some basic prompt |
| `userdel -r [username]`                 | To delete the user                   | `userdel -r myuser1`              | The user will get deleted                                               |
| `groupadd [group-name]`                 | To add the group to the linux system | `groupadd commangrp`              | Group will get created                                                  |
| `usermod -a -G [group-name] [username]` | To add the user into the group       | `usermod -a -G commangrp myuser2` | The user will get added into the group.                                 |
