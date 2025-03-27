<h1>
  🚀 LAB 3 - 4 🚀
</h1>

<h3>
  1. View the gedit man page.<br><br>
  2. Use the man -k ext4 command to find the command to tune ext4 file-system parameters.<br><br>
  3. Understand and demonstrate the use of brace expansion.
</h3>

<hr>

<h1>
  Solution : 
</h1>

<h5>
  Lab 3: 
</h5>

  1. Open the terminal and type:
     <i>
       man gedit
     </i>
     
![image](https://github.com/user-attachments/assets/c43837fa-af56-4b3a-9e44-e3dea47300f5)



  2. If the manual page is not available, try installing `gedit` first:
     <i>
       sudo apt update && sudo apt install gedit
     </i>
     
![image](https://github.com/user-attachments/assets/0e85752a-c420-47ae-a6e8-ea2191a18889)



<h5>
  Lab 4:
</h5>

  1. To search for commands related to ext4, type: <br>
     <i>man -k ext4</i>
     
![image](https://github.com/user-attachments/assets/7c3a7ad1-bd4d-4538-bb0c-f42116f95604)



  2. To find the command to tune ext4 file systems, look for `tune2fs` in the output and check its manual page:
     <i>man tune2fs</i>
     
![image](https://github.com/user-attachments/assets/b89e38bb-e4ea-425e-8ceb-cd50c0933f25)



  3. Understanding Brace Expansion: <br>
     <i>echo file{1,2,3}.txt</i><br>
     Output:
     <pre>file1.txt file2.txt file3.txt</pre>

![image](https://github.com/user-attachments/assets/8c633856-1ac5-44fb-a3ec-704629faa295)



  4. Using a sequence expression:
     <i>echo file{1..5}.txt</i>

![image](https://github.com/user-attachments/assets/fdf0fdb9-a346-4209-9046-a0e12b9796ba)


     
