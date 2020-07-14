# A cooking recipe for using git

First time pull / clone
1. Open git-able command line (e.g., [*Git Bash*](https://git-scm.com/), *Linux/macOS* *Terminal* or *PyCharm* through [*Anaconda*](https://www.anaconda.com/distribution/))
2. Change to the target clone directory <br>`cd "D:/Target/Directory/"`
3. Clone the desired repository:<br>`git clone https://github.com/USER/REPO`

Now is the moment to modify the repository code (add, remove or edit files). After finalizing and testing (push only debugged code to the master branch) new code, go back to the command line to update the repository (`add` – `commit` – `push`):

1. Verify the modifications made <br> `git status`
1. If the status seems OK with consciously made changes, type <br>`git add .`<br>
	*use `git add filename.py` to add single files changes only - best solution: use a local .gitignore file.*
1. Commit changes (be concise , write in past tense)<br>`git commit -m "Leave a message"`
1. `git pull --rebase` <br>*Got conflict messages? Open concerned files, verify the tagged `>>> CODE BLOCKS <<<`, manually delete undesired code (including the `>>> <<<` signs) and keep desried code only.*
1. `git push`

![In case of fire](https://github.com/louim/in-case-of-fire/blob/master/in_case_of_fire.png?raw=true)
*Image: [Louis-Michel Couture on Github](https://github.com/louim/in-case-of-fire/)*
