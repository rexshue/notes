# Git

### Push to remote
* git push origin

### ERROR: Repository not found. Could not read from remote repository.
* git remote set-url origin git@github.com:xxxx/xxxx.git

### Generate ssh public/private key
* cd~/.ssh && ssh-keygen
* cat id_rsa.pub | xclip /* linux */
* cat id_rsa.pub | clip /* Git Bash */

### ReUpdate 
* git remote -v
* git remote set-url origin git@github.com:xxxx/xxxx.git
