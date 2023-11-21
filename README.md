# CU MCA Worksheets
Welcome to the `CU MCA Worksheets` repository! This repository contains worksheets for the MCA course of Chandigarh University. 

## Contributing Guidelines

### You can contribute to this project in following ways:
1. **Add a new worksheet:**
   - You can add a new worksheet to this repository.

2. **Add a new subject:**
    - You can add a new subject to this repository.

3. **Improve an existing worksheet:**
   - You can improve an existing worksheet by adding more questions or by adding solutions to the questions.
4. **Remove unnecessary worksheets or subjects:**
   - You can remove unnecessary worksheets or subjects from this repository.

   
### PR Process

1. **Fork the repository:**
   - Fork the repository by clicking on the fork button on the top of the page. This will create a copy of this repository in your github account.

2. **Clone the repository:**
   - Clone this repository to your local machine. Go to your GitHub account, open the forked repository, click on the code button and then clone the repository.
    ```bash
    git clone "url of forked repository"
    ```
    - After cloning the repository, move to the repository directory.
     ```bash
    cd CU-MCA-Worksheets
    ```

3. **Make a new branch:**
   - Once you are in the local repository, create a new branch with your name_uid.
   For example: `Gaurav_Kumar_22MCC20177`
    ```bash
    git checkout -b <your-name_uid>
    ```

4. **Make changes in worksheet:**
   - To add a new worksheet, create a new folder with your name_uid inside the subject folder and add your worksheet in word format inside your folder.
    
    For example: if you want to add semester-1 worksheet of `DAA` subject, create a folder with your name_uid inside `Semester-1 > DAA` folder and add your worksheet in word format inside your folder.
    ```bash
    mkdir Semester-1/DAA Gaurav_Kumar_22MCC20177
    cd Semester-1/DAA Gaurav_Kumar_22MCC20177
    ```

5. **Add Changes and Commit Changes:**
    - Add those changes to the branch you just created using the `git add` command:
     ```bash
     git add .
     ```
     - Now commit those changes using the `git commit` command:
     ```bash
     git commit -m "Added <your-name_uid> worksheet"
     ```

6. **Push changes to GitHub:**
    - Push your changes to your remote repository on GitHub.
    ```bash
    git push origin <add-your-branch-name>
    ```

7. **Submit your changes for review:**
    - If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

    - Now submit the pull request.

    - Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.

8. **Review Process:**
    - Wait for the maintainers to review your pull request.

    - After that, I'll merge the changes and you will get a notification email regarding the merging of your changes.

9. **Congratulations!** 
    - You have successfully created a pull request and contributed to this project.