# Git and Github: Create and Clone Project
The goal this repository is show how create and clone project


### Create Local Project

1 - First, create one repository in the device (notebook) where it'll be to salve all project. I like of puting in the Disc "C". Because I think more difficult of delete for accident.
![image](https://github.com/user-attachments/assets/8284d7f8-eb0b-42ed-9b72-626330f57252)

Remenber, organization is of your preference.

2 - Now, via command screen (bash), enter in the diretory created. In this case, diretory: GiHub Project

- Use command: ``` cd .. ```. Return root folder.
  
  ![image](https://github.com/user-attachments/assets/e909526f-bea1-49ab-a6f8-e47a5a3731e8)

- Use Command: ``` cd Project-GitHub/ ```

   ![image](https://github.com/user-attachments/assets/22ef9754-3507-4e55-a1b4-d72413b496a8)

Avoid step above, open "command screen (bash)" directly inside Project-GitHub directory:
![image](https://github.com/user-attachments/assets/4c342456-5c76-4564-b5ea-f21916e85293)

3 - On command screen, create the project. It going to upload to GitHub:
![image](https://github.com/user-attachments/assets/82dfb0de-e213-4c0c-bc59-5a3d4fe94955)

4 - Open "Firstproject":
![image](https://github.com/user-attachments/assets/f595ba92-4381-45ac-b690-18adfaf0b4c2)

5 - In the moment, let's transform this repository in "Git", use command: ``` git init ```
![image](https://github.com/user-attachments/assets/681e10ab-3149-4b87-9f02-e5f7efc41f22)

On screen above apparently there wasn't modification but:
- Included "Main" in the end.
- in the windows folder appear empty, however, it's hidden. Use commnad ``` cd .git ``` after command: ``` ls ```:
  ![image](https://github.com/user-attachments/assets/7f992828-0a6a-4d45-86ee-7934549a0f92)

  This hidden folder or files are of configuration to GitHub integration. "Don't change!"



### Clone

1 - Use Command: ``` git clone "Add address HTTPS or SSH" ``` (https://github.com/WanderBernardo/Git_Github_InstallConfiguration):
![image](https://github.com/user-attachments/assets/be80b417-5f8e-4814-8c54-58268bd96d0f)

Case, I want clone using other project name, Use command:  ``` git clone "Add address HTTPS or SSH" "New name"```:
![image](https://github.com/user-attachments/assets/8d71db47-fd8e-41cc-b54e-775993755b49)

When clone repository it comes as a git repository (step 5). 


### Link a local repository with a remote one

1 - It was create one project in the portal GitHub e other in the device local. And you want link both.

- Copy in the portal GitHub the address HTTPS or SSH" (https://github.com/WanderBernardo/Git_Github_InstallConfiguration) of the project.
  ![image](https://github.com/user-attachments/assets/42e108c4-21eb-411d-85d2-2e73975b6e5d)

- On the command screen type command: ``` git remote add origin  "Add address HTTPS or SSH" ```. But first, enter in the diretory of the project that you want link with remote (portal GitHub).
  ![image](https://github.com/user-attachments/assets/dcd0910e-7753-4035-91c4-0b474d5c9704)

2 - Check link from remote to local, use command: ``` cd .git  ``` and ``` cat config  ```
![image](https://github.com/user-attachments/assets/d1e5323d-41f4-4715-a599-b3120173711b)

The same address of the portal GitHub.
