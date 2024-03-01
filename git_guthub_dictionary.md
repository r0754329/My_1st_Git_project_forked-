# Git & GitHub Dictionary

- Git: a versioning system that keeps track of changes - allows you to go back, allows for collaboration, is locally stored.

- GitHub: Where we can acces other's files, online repository for your codes (not only) (Back up place for you rgit projects). "cloud based" located ... remote ...

IMPORTANT: Don't do doble `git init`

IMPORTANT: Don't remove the `.git` folder where your history is kept

# Conceptual Areas

1. Developing area: The workinng directory

2. Staging area: Temporary space to store file beffore commiting to the local repo.

3. Local repo: It is where the snapshots are saved
   
   - To access the history in the local repo so I can get informatino about who, when and what was modified I can use `log`. That will be useful when I want to travel in time.
4- Remote repository: Backspace, example github.

## Git status allow me to check what files are

1. to be staged: You have commited tjhis file/folder before, you have made new changes and git recognise the new changes are not yet `add` not `commit`.

2. to be commited: You have commited file before, you have made new changes and git recognises you have `add` **but not** `commit`

3. Untracked: Is a completely new file/folder that **HAS NEVER** been `add` nor `commit`

# Important docuemnts that should be part of my repo

1.  **README.txt or README.md :** Where I should describe my project, my code, main goals, and usage, etc .... Can also be a good idea to add links and directins for data that should be related for example...

2. **.gitignore :** A text file, with no extension that should be ALWAYS in non-caps and where I'll list all the files to be ignored and not tracked by git nor shared on github. For exmaple: DAta file, Intermediate files, etc....


# Parallel timelines - how to experiment risk free in Git

1. creat a new timeline - branch and give it a name
`git branch <name>`
2. checkout to the timeline you want to work on...
`git checkout <name/id>`

p.s.: You can travel branchs and commits