## BST 209 Course Repository
### Summer 1, 2022

Welcome to the BST 209 course repository! You can find and download all course materials here. 

# Instructors
* Heather Mattie  hemattie@hsph.harvard.edu

* Leo Celi  lceli@mit.edu

* Tom Pollard tpollard@mit.edu

# Teaching Assistants

* Yanran Li      	yanranli@hsph.harvard.edu
* Yi-Ting Tsai	yitingtsai@hsph.harvard.edu

# Office Hours
3:30-4:30pm July 6-8, 11-15
Room TBD


# Downloading course materials using Git with RStudio

You can use Git within RStudio to download the course materials. If you
haven't cloned the repository before, follow these instructions:

1. Click on the green "Clone or Download" on Github and copy the link.
2. Open RStudio, and go to File > New Project > Version Control > Git,
and paste in the link you just copied. Under "Create Project as
Subdirectory of", browse and select a folder where you want the course
materials to go.
3. Press "Create Project". This will create a folder called `BST209-2022`
in the folder you selected in step 2.
4. Now, you can open this project using the projects tab in the upper
right of RStudio, or going to File > Open Project and then navigating
to the BST209-2022 folder and opening the `.Rproj` file.

If you already cloned the repository outside of RStudio (e.g. using
Git Bash), you can associate the directory that was created in that
step with RStudio. In RStudio, go to File > New Project > Existing Directory, and then navigate / click on the BST209-2022 folder. Then click
"Create Project". Then you can follow step 4 above to open the project
when you launch RStudio. You can read more about RStudio projects here:
https://support.rstudio.com/hc/en-us/articles/200526207-Using-Projects

# Updating Course Repo

Once you cloned the course repository and want to get updates, you must
use `git pull` to get updates.

In RStudio, if you followed the instructions above, simply navigate
to the Git tab and press the Pull button. In terminal / Git bash, use
`cd` to navigate to the `BST209-2022` folder, then run `git pull`.


# Taking Notes on Course Materials

If you wish to take notes and write in the course materials, you can
save a copy of the file you want to take notes on with the filename
containing `personal`. For example, if you want to take notes on the
file `00-motivation.Rmd`, save it as `00-motivation_personal.Rmd`. Then,
you can edit the `00-motivation_personal.Rmd` file. We have configured
Git to ignore any files that contain `personal` in the filename, so any changes you make won't show up in Git. This will
allow you to update the course repo without any issues.
