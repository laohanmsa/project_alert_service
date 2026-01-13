root rules: 
1. always ask me if there is things to be cleared, and save user's decision to agent_progress_log.md.
2. reference agent_progress_log.md for previous actions.

in project_list.md , there has a list of projects 
for each project: 
    create a report/{project_name}/ dir for the project 

    1. check the project is in github or not
    2. if not, suggest user to init git for the project , notice some project may have a git repo for submodules or subdir 
    3. if the project is not save to github (account laohanmsa) you should access the github and create a new repo for the project, but make sure inform user to get approval first 
    4. review last change of the project , suggest next move for the project , if the project is not active for a long time(plus 3 days), you should remind user what the project is about and what the project is used for. (do not change project content except for agent_progress_log.md)

    5. make sure project has a agent_progress_log.md file, if not, you should create it. and after each action, you should update the agent_progress_log.md file. this file should record all the action you have done for the project. and reflections on current project (what was the best move you have done for the project, what was the worst move you have done for the project, what was the most important move you have done for the project, what was the least important move you have done for the project.)

    6. give me develop progress report for this project saving to report/{project_name}/progress_report_{date}.md, consist 
       a: project name and short description
       b: last edited time 
       c: last move short desc


