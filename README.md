

### Method 1: The Easy Way (Directly on GitHub)

This is the fastest method for adding a single file to your repository.

1.  Go to your repository page on GitHub in your web browser: `https://github.com/ankankp007/Tree-Plantation`
2.  On the main page of your repository, you should see an "Add a README" button, or an "Add file" dropdown menu.
3.  Click the **`Add a README`** button.
4.  You will be taken to a new page with a simple text editor. GitHub will automatically create a title for you (`# Tree-Plantation`).
5.  Write a brief description of your project. For example: "This is a simple website for a tree plantation initiative."
6.  Scroll to the bottom of the page. You will see a section titled "Commit new file."
7.  Add a short commit message, like "Add README.md" or "Create README file."
8.  Click the green **`Commit new file`** button.

That's it\! The README file will be instantly added to your repository.

-----

### Method 2: The Pro Way (Using the Command Line)

This method is the standard workflow that professional developers use. It's a great way to practice your Git skills.

1.  Go to your project folder on your computer in the command prompt.
2.  Create a new file named `README.md`. You can use a text editor or a command.
    ```bash
    notepad README.md
    ```
    or, on some systems:
    ```bash
    touch README.md
    ```
3.  Add some content to the `README.md` file and save it.
4.  Use `git status` to see that a new file has been created.
5.  Add the new file to your staging area.
    ```bash
    git add README.md
    ```
6.  Commit the file with a message.
    ```bash
    git commit -m "Add README file"
    ```
7.  Finally, push your changes to GitHub.
    ```bash
    git push origin master
    ```

Both methods will achieve the same result. The first is perfect for quick changes, while the second is essential for your regular development workflow.
