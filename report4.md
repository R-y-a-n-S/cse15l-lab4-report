# Lab 4 Report 
**Step 4:** After opening the terminal, I used the command `ssh cs15wi23ajj@ieng6.ucsd.edu` to login to the remote server. 

<img src="login.png" width="800">

As can be seen on the screenshot, the command logged me into the ieng6 remote server. 
Keys pressed: All the characters in the command + \<enter\>

**Step 5:** I went to the github page to copy the SSH key, and entered `git clone git@github.com:R-y-a-n-S/lab7.git` in the terminal to clone the repository. 

<img src="ssh_key.png" width="800">
<img src="clone.png" width="800">

The screenshot shows that the command clone the repository into the remote server. 

Keys pressed: \<Ctrl-v\>\<enter\>

**Step 6:** I used `cd lab7/ ` firstly to get into the directory, during which I used \<Tab\> to auto complete the directory name. I copied the following two command on the course website, pasted and run them in the terminal by such order :
`javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java`
`java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests`
For the second command, I used <Tab> to auto complete the directory name and used <backspace> to delete a dot. 

<img src="Junit.png" width="800">

The screenshot shows that the command run the Junit tests in the ListExamplesTests.java file and one test failed.
  
Keys pressed: cd + l + \<Tab\<enter>
