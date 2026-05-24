# Topics 📚

* mkdir 
* cp
* mv
* rm
* touch

## What I Learned📗
- In this lessons we have been learning about differente commands Linux such as:
- mkdir = creat folders.
- cp = copy folders and files to other locations
- mv = move files or rename files or folders.
- rm = delete files or folders always be careful.
- touch = create a new empty file or update the last modified date of an existing file.
- All of these commands are important for automation, write scripts, write tasks, in environments such as: Linux or Windows with WSL.



## Linux Commands and Their Purpose✍

* mkdir = We use it to create new folders.
* cp = We use it to copy miltiple files and folders at once.
* mv = We use it to move or rename files and folders.
* rm = We use for delete files and folders, but be care full this command will never ask you if you're sure want to delete it, 'rm just delete it'
  - But if you write the command - rm -i , if you used this command this way, it will always ask for confirmation.
  - Also, if you agree the: -r  at the ende of this command, like this: ( rm -r ), will be aloows delete all folders along with all its content.
  - Rememeber be carful with the commands: ( rm , -r , -f ), because insido of the terminal there is no recycling bin.
* touch = the principal function is to create a new empty file, also update the date and hour of modification of the file, while the contents remain intact inside.
  - In other words, never change anything inside the file.


## Practices👨‍💻

### 1️⃣ We will create a directory called "Proyect" using the command -  mkdir -p
#### Example.
* step 1: We will write this command - mkdir Proyect.
* step 2: We can see that the folders is create.
* step 3: We will create more folders with this command -  mkdir -p
  * Is important put on the correct command for creat multiple folders at once.
  * Inside the main folder.
  * In this case, we'll create 2 folders called 'css and html'
* step 4 and step 4.1 : We can see that all folders is creat.
  * 1 - <img width="596" height="262" alt="image" src="https://github.com/user-attachments/assets/ffcdd20c-7686-4b3a-af22-62fbc8cdb6db" />
  * 2 - <img width="558" height="499" alt="image" src="https://github.com/user-attachments/assets/3fcc0488-dc66-4bdd-8f4d-1c9dc228db54" />
  * 3 - <img width="439" height="257" alt="image" src="https://github.com/user-attachments/assets/47a785a9-f717-4516-bdad-8e559b6a6fbd" />
  * 4 - <img width="398" height="446" alt="image" src="https://github.com/user-attachments/assets/a54db042-04a7-42c8-9bc3-a207e1e705b2" />
  * 4.1 - <img width="237" height="143" alt="image" src="https://github.com/user-attachments/assets/391e70e8-86b8-4313-b17e-5e6889280ac0" />
  
##

### 2️⃣ We will copy multiple folders and files here step by step, with the command - cp
#### This commmand is very important in the globe of It because, we can copy diferents files and folders at once and put on in different local, here an example.
- Example.
* step 1: We will create a file called 'Saturday.txt', with command - nano
  - (nano will open an editor in the terminal, to write something).
  - (Press the 'Ctrl + X' key).
  - (Save, press the 'Y' key)
  - (Enter)
* step 2: We will create a folder called 'backup' 
* step 3: Now, we will copy the file called 'saturday.txt' to folder called 'backup.' , with this command - cp Saturday.txt Sunday/   (This will creat a copy clear the file to folder)
  * 1 <img width="716" height="274" alt="image" src="https://github.com/user-attachments/assets/aa84acd6-4334-4dee-b966-0f72ee4f7567" />
  * 1.1 <img width="531" height="164" alt="image" src="https://github.com/user-attachments/assets/778a8e51-f410-486b-bc17-a59a45c6da75" />  (Write something)
  * 1.2 <img width="1002" height="392" alt="image" src="https://github.com/user-attachments/assets/e02888b4-98c4-4bc5-8310-76760c80f858" />  (Created)
  * 2 <img width="1002" height="392" alt="image" src="https://github.com/user-attachments/assets/96b0f544-045d-437d-be24-0d7bf3cfe123" /> 
  * 3  <img width="776" height="503" alt="image" src="https://github.com/user-attachments/assets/79e83390-01f6-4297-a157-ea83fdcc29ed" />

##

### 3️⃣ We will move and rename to files and folders in this examples with command -  mv  . And, we will see different commands through of this practice.
- Example.
* step 1: We'll creat a files called 'inform.txt', using the command - nano
* step 2: We'll creat a folder caller 'informs', using the command - mkdir -p
* step 3: We'll move it, files called 'inform.txt' to files called 'informs', using the command - mv
* step 4: We'll rename file using (   _   ). In this case we rename 'today.txt' to 'today_monday.txt'  We just need to rename files.
* step 5: We can rename and move different files and folders at once, we'll create the file called 'day.txt'
* step 6: We'll move it and rename it like this.

 * 1  <img width="674" height="505" alt="image" src="https://github.com/user-attachments/assets/9c8be91b-b61f-461c-9d47-8d87a1be7447" />
 * 2  <img width="398" height="476" alt="image" src="https://github.com/user-attachments/assets/b4a0c220-dac1-4952-bd00-509987a031dd" />
 * 3  <img width="831" height="379" alt="image" src="https://github.com/user-attachments/assets/0a9d6747-23e2-440d-b31f-b16e88fc2ebb" />
 * 4  <img width="374" height="309" alt="image" src="https://github.com/user-attachments/assets/bb022717-0b18-4fb5-8a95-428907ed59d2" />
 * 4.1  <img width="602" height="532" alt="image" src="https://github.com/user-attachments/assets/cf3a973a-9048-4e81-b051-24605f78d65d" />
 * 5  <img width="630" height="534" alt="image" src="https://github.com/user-attachments/assets/99e52c77-a1a1-4a91-959a-5d36a0be9827" />
 * 6  <img width="839" height="537" alt="image" src="https://github.com/user-attachments/assets/a52d9a15-74c5-4542-98da-4134476093db" />

##
 
### 4️⃣ We'll create file and folder for practice the commands - rm     -    and     rm -i
- Example.
* step 1: We'll create 4 files: one.txt two.txt three.txt four.txt , using the command - nano
* step 2: We'll delete the 4 files and for this used the next command: rm one.txt two.txt three.txt four.txt
* step 3: We'll creat 3 folders using the command: mkdir -p , one two three.
* step 4: We'll delete the 3 folders and all its content like this: rm -r , rm -r one two three.

  * 1 - <img width="808" height="509" alt="image" src="https://github.com/user-attachments/assets/35c98ad1-d6f0-4ca4-b296-f059a974159c" />
  * 2 - <img width="822" height="556" alt="image" src="https://github.com/user-attachments/assets/02228762-45b7-4e1c-9b15-eeceedc238b1" />
  * 3 - <img width="778" height="510" alt="image" src="https://github.com/user-attachments/assets/19016761-1d32-4302-bd87-e4f9265669d5" />
  * 4 - <img width="766" height="495" alt="image" src="https://github.com/user-attachments/assets/f42cea2d-e140-4306-b750-ddda9c483441" />

##

### 5️⃣ The command Touch in action.
#### Is necessary that your understand that, this command is essential for 'automate tasks' in the world of Linux or Windows with WSL.
#### We'll automation tasks, create empty files yo can later edit using settings or scripts. Literally the command touch is great.
- Example.
* step 1: We'll creat a files called ' deploy.sh ' , like this: - touch deploy.sh  - this will create a file when you can write a scripts to deploy cloud infrastructure.
* step 2: We'll see the time is inside of the our new file ' deploy.sh ' , like this: touch deploy.sh : the next the command: ls -l for review the time.
* step 3: We'll create multiples tasks at once like this: touch index.html style.css app.js  , this is practic and quikly for web proyects
  
 * 1 - <img width="774" height="403" alt="image" src="https://github.com/user-attachments/assets/ee375794-0df8-434b-b583-61965f170167" />
 * 2 - <img width="1016" height="559" alt="image" src="https://github.com/user-attachments/assets/82bc65ac-5816-4d11-803b-983552a8ea64" />
 * 2.1 - <img width="1026" height="560" alt="image" src="https://github.com/user-attachments/assets/9b408e0a-0232-470b-a3e6-3162ed3570e7" />
 * 3 - <img width="803" height="491" alt="image" src="https://github.com/user-attachments/assets/9468dd69-8674-4ac6-a790-510b5423899a" />






  





 

 


























