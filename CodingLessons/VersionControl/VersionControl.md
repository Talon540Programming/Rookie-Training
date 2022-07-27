## Version Control
If you've ever tried working with multiple people on a piece of code, you know it can be difficult. Also, you may have experienced the pain of having all your work get lost due to software issues. Version control tackles both these problems!

### This is The Way
- TALON 540 uses Git as its version control method, and we host the remote on GitHub
- What does this mean? 
    - Each time an executable amount of code (meaning it can run- doesn't have to work) is completed, you **commit**
        - When you commit, you essentially create a checkpoint in your code, that you can always return back to.
        - This commit is saved locally on your machine at first, but we back these up to what's called a **remote** in Github's server space, called **pushing**
- Collaboration
    - Git also allows us to easily collaborate with each other without interference. 
    - This is done through **branching**
        - When 2 people are working on different pieces of code in the same **repository** (folder of code) they each create a branch. 
        - When done, the branches can be merged into the **main branch** through a creation of a **pull request**
        - This allows for seamless collaboration on the same code

![Collaboration](https://www.nobledesktop.com/image/gitresources/git-branches-merge.png)

### 540 Convention
- Continually push your commits to the remote repository, with an accurate description of the commit (NO RANDOM TEXT)
- NEVER PUSH DIRECTLY TO MAIN
    - Always create a branch, and then pull request if you want to merge to main
    - Programming Lead will approve the pull requestion
        - Code must be CLEAN and COMMENTED to get approval
        - Any programmer should be able to understand the functionality and clarity of the code
- Creating a public repo requires lead approval, all repos will be private by default. 
- Main branch is always protected. 

Next: See [Git Tutorial](/CodingLessons/VersionControl/GitTutorial.md)
