<h1>
    🚀  LAB 1 - 2 🚀
</h1>

<h3>
    1. Create the operator1 user and confirm that it exists in the system. Set the password for operator1. Create the additional operator2 and operator3 users. Set their passwords as well.
    <br><br>
    2. Run the usermod -c command to update the comments of the operator1 user account. Remove the operator3 user from the system.
</h3>

<hr>

<h1>
    Solution :
</h1>

<h5>Lab 1:</h5>
<p></p>
<p>1. Open the terminal and type:</p>
<i>sudo useradd operator1</i>
<br>

![image](https://github.com/user-attachments/assets/e1615343-b510-4a88-8e91-61f5f09613f8)

<p> </p>

<p>2. To check whether or not the user is added:</p>
<i>sudo cat /etc/passwd</i>
<br>

<p>3. To add the password:</p>
<i>sudo passwd operator1</i>
<br>

![image](https://github.com/user-attachments/assets/7bcbc428-4bf7-4ca7-9e01-dc6562da7ae9)


<p> </p>
<p>4. Follow the same steps for operator2 and operator3 as well:</p>
<br>

![image](https://github.com/user-attachments/assets/69b96089-7056-4d03-8c54-3b2464d23357)



<h5>Lab 2:</h5>
<p>1. To add comments to a particular user, type:</p>
<i>sudo usermod -c "Operator1's comment" operator1</i>
<br>

![image](https://github.com/user-attachments/assets/0928ffaa-c0ea-49a9-a4b1-c8e1be9993f3)



<p>2. To delete the user:</p>
<i>sudo userdel -r operator</i>
<br>

![image](https://github.com/user-attachments/assets/7bcd767f-eb82-4b20-bcd6-1f79f496c0a3)



<h5>Creating Practice Files and Directories:</h5>
<p>Use the <i>touch</i> command to create sets of empty practice files:</p>
<i>touch song{1..6}.mp3 snap{1..6}.jpg film{1..6}.avi</i>

<p>Use a single command to create all three subdirectories:</p>
<i>mkdir friends family work</i>

![image](https://github.com/user-attachments/assets/5b43ca09-9988-4b6a-91db-0d13c37f397b)


-------------------------------------------------------------------------------------------------------------------------------------------------------------------
