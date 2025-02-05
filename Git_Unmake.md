# Git and GitHub: Unmake modification
The Goal in this repository is show how unmake changes

### Unmake Repository Git

1 - Case you have create a project and without wanting to make command: ``` git init ``` in this project so, use command: ``` rm -rf .git ``` to unmake:

![image](https://github.com/user-attachments/assets/47f94c40-7b0a-4353-aeb1-3830c25f58a8)

- ``` git init ``` Enable to version control Git.
- ``` rm -rf .git ``` Unmake to version control Git.
- ``` git status ``` Validate if folder is with version control Git

### Restore of files after commit

1 - Example, deleted the contents of the file "README.md". Use command: ``` git restore "name file" ```:

![image](https://github.com/user-attachments/assets/60848a7e-8bf4-4918-a40a-c74ccdf58504)

### Restore of files before commit: git reset --soft, --mixed or --hard

Consult Hash - use command: ``` git log ```:

![image](https://github.com/user-attachments/assets/702265f1-6e1c-4422-8ecf-76d48ed5d180)

Consult log again to validation after use command below.

1 - Use command: ``` git reset --soft "hash do commit" ```

![image](https://github.com/user-attachments/assets/243524b4-3cbb-4964-9991-a9a49bb04482)

2- Use command: ``` git reset --mixed "hash do commit" ```

In this comand can it use only:  ``` git reset "hash do commit" ```, because this option is standard.

3- Use command: ``` git reset --hard "hash do commit" ```

### About more: 

![image](https://github.com/user-attachments/assets/0be6a76d-f93b-464b-9ed7-e8b92f6082f8)

https://www.geeksforgeeks.org/whats-the-difference-between-git-reset-mixed-soft-and-hard/

Use command: ``` git reflog ``` to consult historical change:

![image](https://github.com/user-attachments/assets/1f740582-799d-4b94-af32-aba4bc868dfc)


### Delete files of the preparation area

1 - File "README.md.md" is preparation area to commit.
![image](https://github.com/user-attachments/assets/ae2f7f47-4e70-4b0a-87e4-93b7548647ba)

2 - Use command: ``` git reset "name files" ```

![image](https://github.com/user-attachments/assets/5cc9e7a8-8d2f-4514-b84f-180de57fe007)

Use "Git status" again to validate.

## Be careful when using this command


## Next Step

https://github.com/WanderBernardo/Git_Github_DownloadUpload
