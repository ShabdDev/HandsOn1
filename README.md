1.  cd /E
2.  cd Devops
3.  cd DevOps_Labs
4.  cd Git_Labs/
5.  mkdir HandsOn1
6.  cd HandsOn1/
7.  git init
8.  git config user.name
9.  nano main.txt
10. git add .
11. git commit -m "main.txt file is added in the master branch"
12. git remote add origin https://github.com/ShabdDev/HandsOn1.git
13. git branch -M main
14. git push -u origin main
15. git log
16. git branch
17. git checkout -b Feature
18. nano login.txt
19. nano signup.txt
20. nano signin.txt
21. rm login.txt
22. ls
23. git add .
24. git stash
25. ls
26. git stash show
27. git checkout main
28. git pull origin main
29. ls
30. git checkout Feature
31. git merge main
32. ls
33. git stash pop
34. git commit -m "signin and sign up logic is committed"
35. ls
36. git push -u origin Feature
37. git log
38. git checkout main
39. ls
40. git pull origin main
41. git log
42. history
