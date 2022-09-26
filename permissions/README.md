# File permissions in shell, a simple breakdown.

> When coding and scripting in shell often you will be doing it with certain co-workers where each individual will have their own personal files in the same directories. Eventually something is bound to happen and it could be a massive problem. That's why the shell has many different permission options. They allow you to change basically everything that you may need to change.

* File permissions, who should have them, what type of permission

Some may have reading and execution only whilst some others may have full access or no access.

#### It is very simple and easy to understand once you get the gist of it.


 > Now let's see what all the files and commands I've made contain.

- Starting with nr.1 (technically it is nr.0) :
> It changes the superuser to the specified name ( in this case it is betty)

- Onto the actual nr.1:
> This prints the effective username of the user. (depends on how you named yourself)
- Nr.2 :
> It prints the groups the user is in. ( in this case its only the base root group)
- nr.3
> this changes the owner of the file hello to betty.
- onto 4:
> This simply makes an empty file named hello.
- 5 is the time:
> This adds executive permissions to the owner only on the hello file.
- 6 is a Bi#ch
> This adds executive permissions to the owner and the group owner.
- 7-u tell them:
> makes the file executable to everyone.
- 8:
> 007
- 9's the one:
> makes the file readable and executable to the owner, viewable to the group, and only executable to the users.
- 10 is great:
> makes the mode of the hello file the same as its mirror olleh. (olleh is just a name I used, not an actual mirror
)
- 11 december:
> adds the executive permission of all subdirectories in the current directory for the owner, group owner and all other users.
- 12 days of christmas:
> it makes a new directory with the permissions labeled.
- 13 tortoises:
> simply changes the group owner to school for the hello file.
- 14's the dream:
> changes the owner and group owner for all files.
- 15's the slumber:
> changes the owner and group of a symbolic link
- 16's the g:
> its a script that changes the owner of the file hello to thee specified one, if said file is owned by guillaume.