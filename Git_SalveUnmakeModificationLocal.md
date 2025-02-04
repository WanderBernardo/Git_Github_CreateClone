# Git and GitHub: Salve and Unmake Modification Local


### Salve

1 - Enter in the repository of the project it will be to salve.
![image](https://github.com/user-attachments/assets/a036232d-7e64-44e0-9024-989065193169)

it's not necessary open windows folder. It was opened because I think the understanding it will be simple.

2 - we're until area of status/modification. Use command:  ``` git status ```:
![image](https://github.com/user-attachments/assets/21ff81d3-c4a9-40f5-917b-07fabb09cd3e)

Return of this command show us that:
- On branch main: principal folder of this project.
- No Commits yet: Not salve modifications.
- Nothing to commit...: Not have anything to salve. Because it was created project but, it wasn't created files for example.

3 - Create a files in project to commit. Use command: ``` touch README.md ```
![image](https://github.com/user-attachments/assets/0f96d5ad-7152-4088-8ffb-0676b84c012c)

4 - Now, execute again command: ``` git status ```:
![image](https://github.com/user-attachments/assets/e1d99e79-2568-49fa-affa-05be6dea917c)

In the screen above, show us there is a file it wasn't salve (untracked files)

5 - Let's include file: "README.md" to area of preparation. Use command: ``` git add README.md ``` and use command: ``` git status ``` again:
![image](https://github.com/user-attachments/assets/16820e9c-b263-4a18-af57-b209ccc93afc)

Message: "Changes to be committed"

It's Okay.

6 - We're salve the modifications. In this case, we created a files. Use command: ``` git commit -m"provides description of the modification" ``` 
![image](https://github.com/user-attachments/assets/b6385cae-e8af-4b5e-8862-2416f399bfa1)

7 - Validate if the files was salve. Use command: ``` git log ``` 
![image](https://github.com/user-attachments/assets/267e80c4-8332-4922-9bba-ea1e3c13f3ad)

