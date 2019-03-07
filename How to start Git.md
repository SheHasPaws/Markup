# How to start Git

1. [Download Git](https://git-scm.com/downloads)

___

2. After installing open git bash:

Generation private key for ssh connect.

` $ ssh-keygen -t rsa -b 4096 -C "your@mail.com" `

___

Copy ssh-keygen and then paste in "Personal settings" => "SSH and GPG".

` $ clip < ~/.ssh/id_rsa.pub `

___

Check your connection to github.

` $ ssh -T git@github.com `

___

Creating user:

` $ git config --global user.name "Name Surname" `

` $ git config --global user.email your@mail.com `

___

You can check your configs:

` $ git config --list `

### Then you can work as you always do

`
$ git init

$ git add *

$ git commit -m "first commit"

$ git remote add origin git@github.com:username/folder.git

$ git push -u origin master
`