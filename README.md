[(201) Git and GitHub for Beginners - Crash Course - YouTube](https://www.youtube.com/watch?v=RGOj5yH7evk)
# Git and Github for Beginners

## What is Git?
A: Free and open source version control system.

## What is Version Control?
A: way to track code changes. We save an initial version of our code into Git. When we update code, we can save it into Git again and again. Throughout time as our code continues to evolve, we can look back at all of the changes we have made over time.
This helps us to see and understand what we did when, track down bugs, or go back to previous versions of our code.

## Terms:
directory -> Folder
Terminal or Command Line -> Interface for Text Commands
CLI -> Command Line Interface
cd -> change directory
Code Editor -> Word Processor for Writing Code
Repository -> Project, or the folder/place where your project is kept
Github -> A website to host your repositories online

## Git Commands:
clone -> Bring a repository that is hosted somewhere like Github into a folder on your local machine.
add -> Track your files and changes in Git. (update, create, delete..)
commit -> Save your files in Git.
push -> Upload Git commits to a remote repository, like Github
pull -> Download changes from remote repository to your local machine, the opposite of ‘push’

## Checking entire Git history
![image](https://user-images.githubusercontent.com/105096396/174553237-93b4bd4b-7d20-439d-b50f-1bdd92ff7922.png)
![image](https://user-images.githubusercontent.com/105096396/174553576-d985ee49-9cb2-47cb-9943-a4edea77f3e0.png)

![image](https://user-images.githubusercontent.com/105096396/174553820-1f78ed52-1e63-433d-a412-ffaf49dc1837.png)


## How to check if Git is installed in your local machine
1. Open cmd/terminal
2. enter git --version
![image](https://user-images.githubusercontent.com/105096396/174554271-92c5cc2d-e5a5-46b8-85a2-808653b9b6d1.png)


## How to clone git repo to your local machine
1. copy git address
![image](https://user-images.githubusercontent.com/105096396/174555466-d1dad7e6-e8c1-47a0-ad63-ee20a28c33f1.png)

2. Open Code Editor(Visual Studio Code) and go to destined folder in local machine
![Screenshot (1)](https://user-images.githubusercontent.com/105096396/174556245-586ec2cb-0d4b-47c4-bdaa-34fb0c3f40ae.png)

3. Open Terminal -> new Terminal and enter git clone [github address]
![image](https://user-images.githubusercontent.com/105096396/174557095-0f888e8d-8edf-46ca-b8a9-5a09b243e206.png)

4. git status shows modifications, updates in the local machine
![image](https://user-images.githubusercontent.com/105096396/174559860-22f11464-1b06-4059-927e-a657de567eb0.png)

5. git add . tracks all the files in Git.
![image](https://user-images.githubusercontent.com/105096396/174560062-7007df7d-6294-4551-803d-9b76cb707850.png)

6. git commit -m "[my heading msg] -m "[my description msg]" to commit
![image](https://user-images.githubusercontent.com/105096396/174560937-6c44b4e4-c8a0-4871-9233-b1b0a3e19f32.png)

## side note to identify myself to github (in case push does not work)
![image](https://user-images.githubusercontent.com/105096396/174563317-86c41923-d664-4b33-925a-5cff44fc0fab.png)
![image](https://user-images.githubusercontent.com/105096396/174564232-c2495e0e-fc66-4e22-9b43-ecc5c5e3941b.png)
- go to github Settings -> SSH and GPG keys -> New SSH -> Enter title and paste the ssh copied -> Add SSH key
![image](https://user-images.githubusercontent.com/105096396/174565209-d2c8b9a1-765e-4b58-8f6e-883fa7bdd748.png)

7. git pull and git push

![image](https://user-images.githubusercontent.com/105096396/174980193-2289436d-6515-42cc-8518-a98f524e3fb9.png)

