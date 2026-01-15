ALWAYS follow these rules: 

1. if there is things to be cleared always ask me for clearence , and save user's decision to rules.md. and folow them. 
2. reference agent_progress_log.md for previous actions.
3. when user say: "remember ....." always save the user decision to rules.md and folow them.
4. check rules.md and follow them.


in project_list.md , there has a list of projects 
for each project: 
    create a report/{project_name}/ dir for the project 

    1. check the project is in github or not.
    2. if not, suggest user to init git for the project , notice some project may have a git repo for submodules or subdir 
    3. if the project is not save to github (account laohanmsa) you should access the github and create a new repo for the project, but make sure inform user to get approval first
    4. project file should either be tracked or excluded in .gitignore
    
    5. review last change/commit of the project , suggest next move for the project , if the project is not active for a long time(plus 3 days), you should remind user what the project is about and what the project is used for rules.md mentioned action.

    6. give me develop progress report for this project saving to report/{project_name}/progress_report_{date}.md, consist 
       a: project name and short description
       b: last edited time 
       c: last move short desc


