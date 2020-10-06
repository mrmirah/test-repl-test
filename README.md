# Practice Quest: A New Beginning
**`Quest giver: Frost Limesprite`**
>Oh... I don't recognize you... hold on... ahem... WELCOME TRAVELER! It is not often that somebody passes my residence.  Now that I think of it, it has probably been around one year since I have last seen a traveler.  I will gladly help you test your new abilities.  Hmmm, yes, yes, I think you would be capable of handling this.  I hope you are good at making lists.

### Objectives required to complete
#### Objective 0 - Videos
[GitHub Setup Playlist](https://www.youtube.com/playlist?list=PL9rLYHglJZYWRymDZ_ac-eAviKn_KcquM) - 6 number of videos, total runtime around 36 minutes

[Git Branch Work Playlist](https://www.youtube.com/playlist?list=PL9rLYHglJZYVE4S_6zDQBIQ60SwBfAN1G) - 4 number of videos, total runtime around 16 minutes

#### Objective 1 - Project Board
- Try to come up with a simple project board

It will be helpful to practice playing with project boards in situations like this practice quest before needing to do it for part of a grade.  Directions for creating a Project Board are below.  They can also be seen in the [GitHub Setup Video 3](https://youtu.be/A0Z7CxVgxsY).

On GitHub, you will need to create a Project Board.  There will be a "Projects" tab at the top of your repository.  Click on this and set up a Project Board:

- Click the "Create a project button" (should be green)
	- Give the project a relevant name and description
	- Select the "Template" dropdown and choose "Automated Kanban"
		- this will be helpful with issues getting moved around automatically for us sometimes
	- Click create project
- Delete all the cards that are in the "To do" column
	- Click the ... on a specific card and select "Delete Note"

With the project board made, you will need to add some cards to the project.

- Click the + on the top of the "To do" column
	- Enter a note and hit add
		- our notes should be short messages about what needs to be completed

#### Objective 2 - Cloning
- Clone this repo into IntelliJ
	- remember to place it into a correct folder

If you are having difficulty doing the clone or are unsure about how to get it into a different folder please ask.  This process including folder changing can also be seen in the [GitHub Setup Video 4](https://youtu.be/RzpVCev12Tg).

#### Objective 3 - Branching from the master
The directions below are displayed in the [Git Branch Creation](https://youtu.be/dfBl_Zu1Geo) video.

- Click on the word "master" in the bottom right corner of IntelliJ
	- Select "+ New Branch"
- On the pop up name the branch `dev`
	- Leave the checkmark in "Checkout Branch"
	- Click "Create"

Now we have our `dev` branch, we double-check the bottom right corner it should say `dev`, not master. 

We can now work on this `dev` branch.  We do our "add, commit, and push" process.  This [working on new branch](https://youtu.be/YK0L9FpB5dI) video.

#### Objective 4 - Top List
- Create a class called `FreshBeginning`
    - make the class in the following location (-> denotes going to a sub-folder)
        - `src` -> `main` -> `java`
- Make a list of print statements of your top 10 favorite movies and/or shows (google if you can't think of 10)
	- add a commit after every three movies

Print statements are written as `System.out.println();`. In between the (), we place variables or words we wish to print.  When printing words we wrap them between ""; therefore the statement would look something like `System.out.println("Words that will appear on the console exactly as they are typed here");`

#### Objective 5 - Merging to master
The directions below are displayed in the [Git Branch Merging to Master](https://youtu.be/GygLvhdcjeE) video.

- Click on the word "dev" in the bottom right corner of IntelliJ
	- Select "master" (it should only say master)
		- this option should be under a heading of "Local Branches" NOT "Remote Branches"
- Select "Checkout" on the pop-out after clicking on master under Local Branches 
	- This should switch IntelliJ back to the master branch
	- You should see the word "master" in the bottom right corner of the screen now
- Select "VCS" up in the top menu options bar
	- Select Git -> Merge Changes...
- Put a checkmark in the `dev` option
	- Only select the `dev` branch with no other words as this is our local version
- Click the merge button

#### Objective 6 - Pushing back to GitHub
- Push all your commits to GitHub on both the master and dev branches
    - It does not hurt to do a final "add and commit" before pushing to verify the latest version is up on GitHub

The committing and pushing process does not change for different branches it is always the same. Directions on how to do commits and pushes can be found in [GitHub Setup Video 5](https://youtu.be/hvd7gmXbRto).  If you are confused or struggling with this process please reach out and let me know.
