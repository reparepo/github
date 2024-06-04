```
1. Generate SSH key:  
	$ ssh-keygen -t rsa -b 4096 -C "username@example.com"
 
2. Add public SSH key to github.

3. Update the URL of the repository origin remote:
	$ git remote set-url origin git@github.com:username/repo.git

4. Execute fetch command

5. Clone repository:
	$ git clone git@github.com:username/repo.git
