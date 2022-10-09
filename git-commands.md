# A1: Basic Tools: Part I: Command Line [9 tasks to complete]

The purpose of this file is for you to demonstrate your knowledge of working with the terminal. Following each prompt below, write the line of code that you used on the terminal to accomplish the task.

```bash
# (1) Print your working directory [complete: YES]
pwd

# (2) List the files in your current directory [complete:  ]
ls

# (3) Change your directory to your info201 root directory.  This should be `~/Documents/info201`. [complete:  ]
cd ~/Documents/info201
# (4) Use the git command `clone` to clone your A1 assignment repository from GitHub to your `assignments` directory [complete:  ]
cd ~/Documents/info201/assignments
git clone https://github.com/info201a-au2022/exercises-rusheelc04
# (5) Using a *relative path*, change your directory to inside the repository you just cloned [complete:  ]
cd a1-rusheelc04
# (6) Find the file "covid-example-2" with 'cd' commands. What is the *absolute path* to this file? [complete:  ]
cd ~/Documents/info201/assignments/a1-rusheelc04/images/COVID-19-Visualizations
# (7) Use the git command `add` to add all of your changes that you've made to this and other files (if any) [complete:  ]
git add .
# (8) Use the git command `commit` to commit your changes. Be sure to include a *descriptive message* [complete:  ]
git commit -m 'added a period in the README.md file'
# (9) Using the git command `push` to push your changes up to GitHub [complete: ]
git push
