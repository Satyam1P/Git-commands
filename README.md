# Git-commands

You must always follow the standard 3-step Git workflow to save and upload the changes:

1. Stage the new files (Tell Git to track them):
cmd


git add .
(This tells Git to prepare the newly dropped folder/files for upload).

2. Save the changes locally (Commit them):
cmd


git commit -m "Add new folder"
(This locks in the changes on your computer with a description).

3. Upload to GitHub:
cmd


git push origin main
Why is this necessary?
Git is designed to act like a camera.

git add . is like setting up the shot.
git commit is like taking the picture (saving it to your roll).
git push is like uploading the picture to the cloud.
