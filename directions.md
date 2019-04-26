1.	Go to github.com and log in.
2.	Navigate to dwchambers/STAPython.
3.	Click the fork button in the upper right hand corner. 
![Alt](/fork1.png "fork1")
4.	Open a terminal.
5.	Navigate to a new/clean folder. You can delete your old STAPython folder if you have one.
6.	Type 
`git clone https://github.com/<yourusername>/STAPython`
7.	Navigate into the cloned folder by typing
`cd STAPython`
8.	Use the first 3 letters of your last name to create a blank text file. For me it would be `touch cha.txt`
9.  Add and commit your changes.
```
git add <first_three_of_last_name>.txt
git commit 'added <first_three_of_last_name>.txt'
git push -u origin master
```
10. Create a pull request.
![Alt](/fork2.png "fork2")
