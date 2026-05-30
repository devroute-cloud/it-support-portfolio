# Topics 📚

* find 
* grep
* locate
  

# What I Learned📗

* find
* grep
* locate

#Linux Commands and Their Purpose✍

* find = To find files and directories in real time (Linux), it can be challenging to locate a specific one. Fortunately, there is this command, sometimes this command is slow for the disk size.
* grep = It is the ultimate text extractor, this command filters out the lines that match.
* locate = To find files instantly, it doesn't check the disk in real time, it is ultra-fast, but if you create a file 5 minutes ago, the locate command not will find.

# Practices👨‍💻

## 1️⃣ The find command: Here's a quick exercise, we create many files using the command: "nano" inside of User files for can to practice,
<img width="1347" height="647" alt="158" src="https://github.com/user-attachments/assets/bd02f7a8-5e0e-4030-a144-b4840e802541" />
- Find files larger or smaller than a given size:
  - Files larger than 100 MB
    - the command: find /var -type f -size +100M
  - Files smaller than 10 KB
    - find /tmp -type f -size -10k


## 2️⃣ The grep command: The grep command is perfect for text extract.Here's a two quick exercises.
<img width="1333" height="565" alt="158" src="https://github.com/user-attachments/assets/fa306ade-b91f-463e-8a7e-fe111f0e56f5" />


## 3️⃣ The locate command:
