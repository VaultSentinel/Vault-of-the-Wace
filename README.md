## *There are no files in this repository*. Download files [from here](https://vaultofthewace.xyz)
We are very interested in receiving more resources, especially from the last few years. If you would like to support other WACE students, please send us the resources at vaultofthewace@proton.me.

# How to contribute
## General rules
- Don't delete any resources unless duplicates.
- When uploading tests, try to keep the naming convention similar to currently existing tests.
- Try to keep the general organization the same (e.g. place exams and their marking guides in the same folder)

## Uploading files
There's a couple ways to contribute by adding your own tests or notes to the repository, described below.

**PSA:** Some of the resources that you want to contribute may already be on the site. Use the search feature and enable fragmented search to make sure that you aren't uploading a duplicate.

### With the GitHub website
Unfortunately the GitHub website only allows for uploading of folders/files, or editing files individually. This means that you'll be able to only upload tests/notes using the website, so depending on how you're contributing you may need to use the other method.

To upload a file:
1. First you'll need to fork the repository (make your own copy of it), by going [here](https://github.com/VaultSentinel/Vault-of-the-Wace) and clicking `Fork` near the top right.
    - If you've done this in past there's no need to create a second fork.
2. Go to the folder in your fork's repository where you want the file(s) uploaded.
3. Drag-and-drop the file from your file explorer onto the website.
4. If you want to add multiple files to the same location, just continue dragging them.
5. Describe the changes you made, then press `Commit changes`.
6. To merge your files this repository from your fork, go to your fork's main page and click the pull request button then follow the steps.

To upload a folder:
- Do the exact same process as above.

### By cloning the repository
Steps:
1. You may first have to download and install Git if your computer doesn't have it already.
2. Then you'll need to fork the repository (make your own copy of it), by going [here](https://github.com/VaultSentinel/Vault-of-the-Wace) and clicking `Fork` near the top right.
    - If you've done this in past there's no need to create a second fork.
3. Open your terminal in the directory that you want to download the repository to.
4. On your fork's repository, find the `Code` dropdown button and copy the .git link shown. Then type `git clone <insert link here>` in the terminal, using the link. For example, it might be `git clone https://github.com/VaultSentinel/Vault-of-the-Wace`
    - If you have already done this in past, before you make any further changes you should type `git fetch` to update the local copy on your computer.
5. Make your changes, by uploading/removing/renaming files.
    - You can review the changes you've made by typing `git status`
6. To make Git recognise all your changes, type `git add -A`
7. Then to upload your changes to your fork, type `git commit -m message`, replacing `message` with a description of your changes, and then type `git push`
8. After uploading your changes, to merge them into this repository from your fork, go to your fork's main page and click the pull request button then follow the steps.