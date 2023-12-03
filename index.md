## Part 1
1. Content of student's post

This screenshot shows that there is a failure in the code meaning there is a bug that needs to be fixed.
![Image](Lab5Pt1.png) 
- The symptom is that there is an error in the code since the failure-inducing output shows that there is failures in such code where the error is shown when testing in ListExamplesTest.java which uses the logic and methods in ListExamples.java. There may be a bug in how the code works because the syntax seems to be correct.

2. Response from TA
- Does the logic of the each line of the code make sense? Check if each variable is correctly used in the methods in ListExamples.java.

3. Terminal Output
![Image](LAB5Pt2.png) 
- In ListExamplesTests.java, one of the test failed due to the bug in the code where there was a logic error in one of the methods in ListExamples.java. The bug was that there was a variable mistake where index1 was used in a while loop that was handling index2 information. To fix the bug, the variable index1 needed to be changed to index2.

4a. File and Directory Structure
![Image](LAB5Pt3.png) 

4b. Contents of each file before fixing the bug
![Image](LAB5Pt4.png) 
![Image](LAB5Pt5.png) 

4c. Command Lines ran to trigger bug
~~~
bash test.sh
~~~
![Image](LAB5Pt6.png) 
To see results of the test, test.sh holds the information used to run the results using the command: bash test.sh to see the failures/presence of bugs.

4d. Description of what to edit to fix the bug
To fix the bug, there is a logic error in the file ListExamples. The logic does not make sense to increment the count of index1 when handling list 2 information, we want to increment index2 when comparing list 2 so the fix in the bug is to change index1 to index2 which fixes the error as index2 is the correct variable to be incrementing when handling list 2 information.

5. Interesting Error
![Image](LAB5Pt7.png)
![Image](LAB5Pt8.png)
This error is interesting as there is an unexpected error in handling list 1 and list 2 information. The error is in the length of the array where it is not the correct array length which produces a failure inducing output. This error is rooted in the merge function in which index1 and index2 hold very high values in incrementation when handling list 1 and list 2 information. This high value creates an error in array length bounds. 

## Part 2
Something interesting I learned in the second half of this lab course is learning how to use vim and learning how useful it can be outside using it in this course. I learned how efficient vim is by making coding faster and the shortcuts in commands that can be used. Overall, I think I learned how to efficiently code and code better in general in this class. 
