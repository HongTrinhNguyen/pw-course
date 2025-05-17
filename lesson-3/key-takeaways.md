# Git Undo things 

- Change commit message: 
enter "i" -> open insert mode;
press esc -> close insert mode;
":wp" --> write and input
- Format: git commit --amend -m"message"

**Note**: *enter "git log" to view all git commit and commit message*

- Change commit from Staging area to Working directory: *git restore --staged (file)*

- Change from repository back to working directory (UNCOMMIT): *git reset HEAD~1* (undo 1 commit)

# Branching

Create new branch  --> 
"git branch (name branch)"

Move from main branch to new branch --> "git checkout (name branch)"

Create and move on new branch immediately: "git checkout -b(name branch)"

# .gitignore
 ignore file, not tracking anymore
 add file in .gitignore by "(file_name)/"


# Javascript

## Convention

    snake_case: not used 
    kebab_case: file name
    camelCase: variable name
    PascalCase: class name

## Object
**Object** is used for collect value in the same variable or constant

let/const <(objec_tname)> ={
    <(attributes)> : <(value)>
}
- attributes = camelCase: variable name
- value: same as variable or **another object**

get value:
- user.age =28
- product["manufaturer"]["year"]=2025



