# Lab 4 Report 
**Step 4:** After opening the terminal, I used the command `ssh cs15wi23ajj@ieng6.ucsd.edu` to login to the remote server. 

<img src="login2.PNG" width="400">

As can be seen on the screenshot, the command logged me into the ieng6 remote server. 

*Keys pressed: All the characters in the command + \<enter\>*

**Step 5:** I went to the github page to copy the SSH key, and entered `git clone git@github.com:R-y-a-n-S/lab7.git` in the terminal to clone the repository. 

<img src="ssh_key.PNG" width="400">
<img src="clone.PNG" width="800">

The screenshot shows that the command clone the repository into the remote server. 

*Keys pressed: \<Ctrl-v\>\<enter\>*

**Step 6:** I used `cd lab7/ ` firstly to get into the directory, during which I used \<Tab\> to auto complete the directory name. I copied the following two command on the course website, pasted and run them in the terminal by such order :
`javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java`
`java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests`
For the second command, I used \<Tab\> to auto complete the directory name and used <backspace> to delete a dot. 

<img src="Junit.PNG" width="800">

The screenshot shows that the command run the Junit tests in the ListExamplesTests.java file and one test failed.
  
*Keys pressed: cd + l + \<Tab\>\<enter\>, \<Ctrl-v\>\<enter\>, \<Ctrl-v\> + L + \<Tab\> + \<Backspace\>*
  
**Step 7:** I used the command `nano ListExamples.java` to start editing the file, during which I used \<Tab\> to auto complete the directory name. Then, I pressed the down arrow 42 times and right error 12 times to get to the error location. I used \<Backspace\> to delete the character '1' and replaced it with '2'. Then I used \<Crtl-O\>\<Ctrl-X/> to save and exit nano. 
  
<img src="nano.PNG" width="800">
  
The screenshot shows that the error has been fixed. 
  
*Keys pressed: nano + \<space\> + L + \<Tab\> + .j + \<Tab\>\<enter\>, \<down\>\<down\>......\<down\>\<down\> (42 times in total) + \<up\>\<up\>......\<up\>\<up\> (12 times in total) + \<Backspace\> + 2  , \<Ctrl-o\>\<enter\>\<Ctrl-x\>*
  
**Step 8:** The command `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` was 3 up in the search history, so I used up arrow to access it. Then, the command `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests` was  also 3 up in the search history, I access it the same way. 
  
<img src="Junit2.PNG" width="800">
  
The screenshot shows that the command run the Junit tests in the ListExamplesTests.java file and all tests passed. 

*Keys pressed: \<up\>\<up\>\<up\>\<enter\>, \<up\>\<up\>\<up\>\<enter\>*

**Step 9:** The following commands were manually entered to add, commit, and push the codes to Github.
  
```
git add .
git commit -m "c"
git push
```
<img src="final.PNG" width="800">
  
The screen shot shows that all the commands are successful and the Github repository has been updated.
  
*Keys pressed: all the characters in the commands*


