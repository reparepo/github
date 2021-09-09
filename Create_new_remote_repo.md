### To create new remote repository

```
1. mkdir testrepo

2. cd testrepo

3. git init

4. git branch -m main

5. git remote add origin https://github.com/USERNAME/testrepo.git

6. curl -u 'USERNAME' https://api.github.com/user/repos -d '{"name":"testrepo"}'

7. touch text.txt

8. echo 1234567890 > text.txt

9. git add --all

10. git commit -m "Add text.txt"

11. git push -u origin main
```
