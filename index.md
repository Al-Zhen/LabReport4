# CSE 15L - Lab Report 4 - Alexander Zhen

* Log into ieng6

![image](3.PNG)

> Keys pressed: I typed out `ssh alzhen@ieng6.ucsd.edu` and then pressed `<enter>`. Then I typed in `cs15lwi24` then pressed `<enter>`, in order to connect my personal computer to the CSE basement.


---

* Clone your fork of the repository from your Github account (using the `SSH` URL)

![Image](33.PNG)

> Keys pressed: I typed out `git clone` (a command to create a copy of a respository into a new directory), then I pressed `<ctrl>` and `v` to paste the `SSH` URL clone `git@github.com:Al-Zhen/lab7.git` (which is the SSH URL of the repository, using `git clone` to retrieve all the files from that directory into a local copy on my computer) and pressed `<enter>`. By pressing `<enter>`, it finalizes the command, starting up the process of cloning the Git repository from my SSH URL clone, downloading all the repository files from the Git repository and setting up a copy on my own personal computer.

---


* Run the tests, demonstrating that they fail

![Image](5.PNG)

> Keys pressed: I typed out `cd lab7` which is the directory I want to be in, which contains the files I need. Then, I pressed `<enter>` which runs the `cd lab7` command, changing my current directory into the `lab7` directory. Then, typed out `bash`, `<space>`, then `t`, `<tab>` to get `test.sh`, this is to type out a script file called `test.sh` which contains commands to run the tests in `ListExamplesTest.java` and execute it using the `bash` shell. Then, I pressed `<enter>` to execute the command `bash test.sh`, which runs the `test.sh` script, containing the commands to run the tests in `ListExamplesTest.java`.

---

* Edit the code file to fix the failing test

![Image](7.PNG)

> Keys pressed: I typed out `vim ListExamples.java` then pressed `<enter>` to open up `ListExamples.java` via the Vim text editor. Then, I pressed `<shift>` and `g` to get to the last line of the code. After, I pressed `k`,`k`,`k`,`k`,`k`,`k` (6 times) to go up to the line that contained `index1 += 1`. Then, I pressed `<ctrl>` and `a` to increment the nearest numerical value on that line, which was the `1` on `index1`, which incremented it to `index2` to fix the code. Afterwards, I pressed `<esc>` to switch back into command mode. Then, I typed out `:`, which indicates entering a command, then `w` which tells vim to save any changes made to `ListExamples.java`, then `q` to tell vim to exit the text editor, then `!` to force the command to run, following up with `<enter>` to execute the `:wq!` command, which saves any changes done to `ListExamples.java` and exits out of the vim text editor.

**Side note** : In regards to this specific instance, I didn't need to press `<esc>` to go back into command mode, I was able to do `<shift> + g`, `k` and `<ctrl> + a` and was able to type out `:wq!` all while in command mode (I didn't enter any other mode like insert) after entering the Vim text editor. But, I'll include the `<esc>` keypress just in case.

---

* Run the tests, demonstrating that they now succeed

![Image](8.PNG)

> Keys pressed: I typed out `bash` , `<space>` , `t` , `tab` to get `test.sh`, this is to type out a script file called `test.sh` which contains commands to run the tests in `ListExamplesTest.java` and executes it using the `bash` shell. Then, I pressed `<enter>` to execute the command `bash test.sh`, which runs the `test.sh` script, containing the commands to run the tests in `ListExamplesTest.java`. 


---

* Commit and push the resulting change to your Github account (you can pick any commit message!)

![Image](9.PNG)

> Keys pressed: I typed out `git add "ListExamples.java"` and pressed `<enter>` to add `ListExamples.java` to the staging area in my Git repository. Then I typed out `git commit -m "Fixed ListExamples.java"` and pressed `<enter>` to create a commit on my Git repository and a message to specify the commit. After, I typed out `git push origin main` and pressed `<enter>` to take the changes made in `ListExamples.java` and 'pushes' it back to GitHub. 
