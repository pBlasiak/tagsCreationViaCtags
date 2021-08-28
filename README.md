# tagsCreationViaCtags
Do these steps:
1) install ctags exuberant 
2) download the repository 
3) load OpenFOAM variables (e.g. of1612)
4) run ./AllrunTags

AllrunTags script do mainly these commands:
1. cd $WM_PROJECT_USER_DIR
2. run createTags
3. run createMainTagInProjectRoot
4. cd $WM_PROJECT_DIR
5. run createTags
6. run createMainTagInProjectRoot

If you want to delet the .tags file run ./delTags
