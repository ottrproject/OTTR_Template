The OTTR template: https://github.com/ottrproject/OTTR_Template is always a work in progress. We are working on adding more features and smoothing out bugs as we go. 

If you want to receive updates from the template to your course, you will need to enroll this repository to the template updates by adding it to the `sync.yml` file.

# Step 1: Enroll your repository in template updates

## Option A: Open an issue in the OTTR Quarto Template Repository

- [ ] [Open an issue in the OTTR_Template Repo, providing the URL of the new repository](https://github.com/ottrproject/OTTR_Template/issues/new?assignees=kweav,carriewright11&labels=&projects=&template=new-course-add-to-sync.md&title=)

## Option B: Fork the template repository and edit the sync file to open a Pull Request

- [ ] Navigate to the [OTTR_Template sync file](https://github.com/ottrproject/OTTR_Template/blob/main/.github/sync.yml)

- If you're not part of the ottrproject organization
  - [ ] Click on the "Fork this repository and edit this file" button in the upper right (look for a pencil).
  - [ ] Click the "Fork this repository" button.
  - [ ] Add your repository's name
    - [ ] above `###ADD NEW REPO HERE following the format above#`
    - [ ] Indent the same amount as other listed repos
    - [ ] Include the account name (personal or organization), a forward slash (/), and the repo name
  - [ ] Click the "Commit Changes..." button (as the banner on the top of the page says, this will write your changes to a new branch in your fork so you can open a pull request)
  - [ ] Type `Add new repository to sync` as the `Commit message`
  - [ ] Click the "Propose Changes" button (This will automatically open a new page comparing the changes from your branch to the original OTTR_Quarto repository)
  - [ ] Optionally edit the title or provide an extended description
  - [ ] Click the "Create pull request" button.
  - [ ] Alert us there is a new PR by adding a comment
    - [ ] Scroll down to "Add a comment"
    - [ ] Type "@kweav @carriewright11"
    - [ ] Click the "Comment" button
     
- [ ] If you are part of the ottrproject organization, you do not need to Fork the repository to edit the file, but you should still create a new branch and open a Pull Request. 

# Step 2: Add the jhudsl-robot as a collaborator

In order for these syncs to happen we need credentials to do so. If your repository is not part of the `jhudsl` or `fhdsl` GitHub organizations, our `jhudsl-robot` is what you need to give access to. 

- [ ] In your repository, navigate to the Settings tab in the top navigation (look for a gear)
- [ ] Go to "Collaborators" in the side navigation
- [ ] Click the "Add people" button
- [ ] In the pop up window
  - [ ] Search `jhudsl-robot`
  - [ ] Select `jhudsl-robot ᐧ Invite collaborator`
  - [ ] Click the "Add jhudsl-robot" button
