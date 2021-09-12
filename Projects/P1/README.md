# Project 1
Due: 09/17, 11:59pm EST (Late 09/19, 09/24)

This project can be completed in-class on 09/10. It is a simple exercise to get you familiar with using git on the command line, creating a local repo, and pushing that repo to GitHub.

## Create A Local Repo

On your command line,

1. Create a directory for your repository and cd into it
```bash
mkdir MyFirstRepo
cd MyFirstRepo
```
2. Create an empty file in your repo
```bash
touch test.txt
```
3. Add your file to the **staging area**
```bash
git add test.txt
```
4. Commit your file to your local repository
```bash
git commit -m "Adding my first file"
```
5. [Optional] Verify that your commit shows up in your log
```bash
git log
```

## Create A Remote Repository

On GitHub,

1. Hit the green new button on the left sidebar
2. Give your repository a name, set permissions to public, and leave all other options to default
3. Click ssh on the blue quick setup box and copy the endpoint (git@...MyFirstRepo.git)

## Push Your Local Repository to GitHub

1. Add the **remote** endpoint that you copied from GitHub
```bash
cd MyFirstRepo
git remote add origin {the_remote_you_copied}
```
2. Push your local repository to GitHub
```
git push -u origin main
```

## Submission

Submit the link to your public repo on ELMS. It should look something like: `https://github.com/your_username/MyFirstRepo`

## Academic Integrity

Please **carefully read** the academic honesty section of the course syllabus. **Any evidence** of impermissible cooperation on projects, use of disallowed materials or resources, or unauthorized use of computer accounts, **will be** submitted to the Student Honor Council, which could result in an XF for the course, or suspension or expulsion from the University. Be sure you understand what you are and what you are not permitted to do in regards to academic integrity when it comes to project assignments. These policies apply to all students, and the Student Honor Council does not consider a lack of knowledge of the policies to be a defense for violating them. Full information is found in the course syllabus, which you should review before starting.
