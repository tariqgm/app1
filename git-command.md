
- create a .ssh folder inside your users folder usually located at c:/users/yourusername
- ssh-keygen -t ed25519 -C "tariqgm@gmail.com"
- Copy the public file to github.com ssh key setting by using new key
- eval $(ssh-agent)
- ssh-add ~/.ssh/fileName
- git clone git-repository-url
- git status
- git configure --global user.name "tariqgm"
- git configure --global user.email "tariqgm@gmail.com"
- git status
- touch index.html (or create index.html using visual studio code)
- Add some HTML to index.html or keep it empty
- git status (Now index.html will show in red to message it's untracked)
- git add index.html
- git status (after git add index.html it starts showing in green means it's tracked in git local storage area)
- git commit -m "a message about your changes"
- git push 

git push command will push your local commit (tracked changes) to your github.com/repository

