## GIT Integration in Bruno Overview

### Open-source version

In the open-source version of Bruno, users need to manually perform GIT operations using the terminal or tools like VS Code's GIT features. This includes initializing a GIT repository, adding changes, committing, pushing, and pulling updates. Below is a step-by-step guide on how to use GIT with Bruno in the open-source version.

### Initializing GIT in Bruno collection

To begin version controlling your Bruno collection, you need to initialize a GIT repository in the directory where your `.bru` files are stored using the following steps:

1. **Navigate to the Bruno Collection Location:**

   - Navigate to the location on your PC where you created the Bruno collection, and copy the path.

2. **Change directory in Terminal:**

   - Run the following command in the terminal:
     ```
     cd path/to/your/bruno/collection
     ```

3. **Initialize Git:**
   - Run the following command to initialize Git in the Bruno collection directory:
     ```
     git init
     ```

### Adding and Committing Changes

After initializing the GIT repository, you can add and commit changes to your collection.

1. **Creating a New HTTP Request in Bruno App**

   - Hover over the collection name in the Bruno app.
   - Click on the three dots, then click on "New Request."
   - Type in the name of the request and populate the URL field with `https://example.com`.
   - After making the change, save it.

2. **Adding and committing the changes**
   - Stage all the changes made inside the collection:
     ```
     git add .
     ```
   - Commit the changes:
     ```
     git commit -m "Created my first Bruno request 🐶"
     ```

### Pushing and Pulling Changes

To share your changes with others, you can push and pull your commits to/from a remote repository.

1. **Pushing changes**

   ```
   git push -u origin main
   ```

2. **Pulling changes**
   ```
   git pull origin main
   ```

### Golden edition version

#### Initializing GIT

Initializing GIT is simpler in the Golden edition of Bruno. You can simply click on the "initialize" button in the GIT modal dialogue to initialize the Collection with GIT.

![Demo for git initialisation]([https://i.imgur.com/dT2zWil.mp4](https://raw.githubusercontent.com/sanjai0py/bruno-docs-test/main/assets/demo-git-initialise.mp4))

#### Adding and Committing the Changes

Once you make the changes, you can click on the Git UI button and include the changes you made to be committed.

![Demo for git adding and commiting](https://i.imgur.com/dT2zWil.mp4)

#### Pushing and pulling the Changes

![Demo for git pushing and pulling](https://i.imgur.com/dT2zWil.mp4)

In conclusion, the Golden edition simplifies the process of initializing GIT and adding/committing changes to enhance the user experience.

---

[^5]: A repository is nothing but a folder; in this case, it is the Bruno collection.
