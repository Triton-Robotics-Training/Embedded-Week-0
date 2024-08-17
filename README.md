# Embedded-Week-0

## Understanding Git

Git is a distributed version control system that allows multiple people to work on a project simultaneously without interfering with each other's work. It's widely used in software development for managing and tracking changes to source code, but it can also be used for managing changes to any set of files.

### Cloning a Repository
You can clone an existing repository to get a local copy on your machine. This gives you all the files and the full history of the project.

```console
git clone <repository-url>
```

### Making Changes
After editing files, you use git add to stage the changes and git commit to save them with a message describing what you did.

```console
git add .
git commit -m "Description of changes"
```

### Pushing Changes
If you're working with others, you push your commits to a remote repository (like GitHub) so others can see your changes.

```console
git push
```

### Pulling Changes:
You can pull changes from the remote repository to update your local copy with what others have done.

```console
git pull
```

### Branch and Merging 
To work on a new feature, you create a branch, make changes, and then merge the branch back into the main branch when you're done.

```console
git branch <new-branch-name>
git checkout <new-branch-name>
# make changes and commit them
git checkout main
git merge <new-branch-name>
```

## Github
GitHub is a web-based platform that provides hosting for Git repositories, enabling developers to manage, share, and collaborate on code projects. It's one of the most popular platforms for version control and source code management, leveraging the power of Git.

## Training, Workflow, and Duties

### Training 

There will be 5 weeks of content that will prepare you on a plethora of topics relating embedded systems.

Week 1: Signals
Week 2: Binary Bites and Protocol 
Week 3: PID
Week 4: Motors and Chasis
Week 5: Pitch, Yaw, and Shoot

You can do all of these online except week 4 & 5 because you'll need to test it with the actual motors on the robots. If you are stuck feel free to attend the weekly embed team meetings (3 per week).

### Capstones

Upon the completion of the training program you will be assigned to a capstone project. This project will likely involve adding a feature or increase efficency in the robots. There is not a time limit but it is recommended to present what you have been working on after 3-4 weeks. After this you will be an official member of the club. You will get a partner for the capstone. 

### Workflow

This is a sneak peak of what a embeded member's week looks like. From Monday to Friday, there will be 3 team meetings where the different teams meet together to work on projects or discuss plans. You are required to attend one meeting a week. These meetings usually last anywhere from 30 minutes to 2 hours. On saturday there will be a club meeting with everyone. This starts at 11 and last all the way till 5. Saturdays is the main workday so the hours is longer which allows you to work with your teammates. 

Most of your time at these meetings would be writing code and testing it with the robots. 

### Robots

We have 3 main robots (Infantry, Sentry, and Hero). You will meet them very soon. They all have different functionality but their code is very similar and we our work would be mainly focused on these 3 robots.

### Extra Ressources

- Good Web Code Editor: [Programiz](https://www.programiz.com/cpp-programming/online-compiler/)
- Git command Cheat Sheet: [Git](https://education.github.com/git-cheat-sheet-education.pdf)











