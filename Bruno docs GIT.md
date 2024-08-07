## GIT Integration in Bruno Overview

### Open-source version

In the open-source version of Bruno, users need to manually perform GIT operations using the terminal or tools like [VS Code's GIT](https://code.visualstudio.com/docs/sourcecontrol/overview) features. This includes initializing a GIT repository, adding changes, committing, pushing, and pulling updates. Below is a step-by-step guide on how to use GIT with Bruno in the open-source version.

### Initializing GIT in Bruno collection

To begin version controlling your Bruno collection, you need to initialize a GIT repository in the directory where your `.bru` files are stored using the following steps:

1. **Navigate to the Bruno Collection Location:**

   - First, navigate to the location on your PC where you created the Bruno collection. Once you're there, copy the path.

2. **Change directory in Terminal:**

   - Head over to the terminal and run the following command:
     ```bash
     cd path/to/your/bruno/collection
     ```
     This will place you inside the Bruno collection.

3. **Initialize Git:**
   - Now, initialize Git in the Bruno collection directory by running the following command:

     ```bash
     git init
     ```

     This step marks the beginning of the magical journey of version control for your collection.

With these commands successfully executed, your Bruno collection is now prepared to engage in seamless collaborations using any preferred version control system. Let your creativity flow without the worries of versioning!

---

### Adding and Committing Changes

After initializing the GIT repository, you can add and commit changes to your collection.

1. **Creating a New HTTP Request in Bruno App**
   - Hover over the collection name in the Bruno app.
   - Click on the three dots that appear on hover, then click on "New Request."
   - Type in the name of the request and populate the URL field with `https://example.com`.
   - After making the change save it.

Now, you can add and commit these changes to your GIT repository:

2. **Adding and commiting the changes**

   - Now, stage all the changes made inside the collection so that it can be commited to GIT.

     ```bash
     git add .
     ```

   - Now commit the changes.

     ```bash
     git commit -m "Created my first Bruno request 🐶"
     ```

---

### Pushing and pulling changes.

To share your changes with others, you can push and pull your commits to/from a remote repository. Inorder for this to work the repository [^5]

1. **Pushing changes**

   ```bash
   git push -u origin main
   ```

2. **Pulling changes**

   ```bash
   git pull origin main
   ```

---

### Golden edition version

#### Initializing GIT

Initializing GIT is made easy in the Golden edition of Bruno.

Click on the <span><img src="git-branch.png" alt="Git branch image" width="20" align="center" ></span> icon on the top right, which will open up a modal dialogue like this:

![Git branch image](git-initialise-modal.png)

Then click on "initialize" to initialize the Collection with GIT.

#### Adding and commiting the changes

Inorder to add and commit the changes you first need to make some changes. For that follow this steps as mentioned earlier.

> **Creating a New HTTP Request in Bruno App**
      - Hover over the collection name in the Bruno app.
      - Click on the three dots that appear on hover, then click on "New Request."
      - Type in the name of the request and populate the URL field with `https://example.com`.
      - After making the change save it.
      Now, you can add and commit these changes to your GIT repository:

Then click on the top righ corner <span><img src="image-2.png" alt="Git branch image" width="70" align="center" border-radius="100%"></span> which is the current branch name that is checkedout. And in that drop down click on the Git UI button there.

Now you can add the changes you made to be included in the commit that you are about to make. You can press + icon for every changes that you need to selectively include them or you can press the + icon at the top to include all the current changes. 
<!-- 
<img src="git-add-changes-demo.mov" alt="Git branch image" width="70" align="center" border-radius="100%"> -->

<video width="320" height="240" controls>
  <source src="git-add-changes-demo.mov" type="video/mov">
Your browser does not support the video tag.
</video>

[^5]: A repository is nothing but a folder in this case it is the bruno collection.
