1. Setup Name and Email
    
    ```bash
    $ git config --global user.name "Your Name"
    $ git config --global user.email your.email@example.com
    ```

2. Setup Line Ending Preferences

    ```bash
    # for Unix/Mac users:
    $ git config --global core.autocrlf input
    $ git config --global core.safecrlf true
    # for Windows users:
    $ git config --global core.autocrlf true
    $ git config --global core.safecrlf true
    ```
3. Config Sublime Text 2 as the Default Text Editor

    ```bash
    $ git config --global core.editor "subl -w"
    # Replace "subl -w" with "mate -w" for TextMate, "gvim -f" for gVim, or "mvim -f" for MacVim.
    ``` 
5. (optional) Config command alias

    ```base
    $ git config --global alias.co checkout
    ```
6. Config .gitignore file, may use [github's collections of .gitignore files](https://github.com/github/gitignore)

    ```bash
    # Ignore bundler config
    /.bundle
    
    # Ignore the default SQLite database.
    /db/*.sqlite3
    
    # Ignore all logfiles and tempfiles.
    /log/*.log
    /tmp
    
    # Ignore other unneeded files.
    doc/
    *.swp
    *~
    .project
    .DS_Store
    .idea
    ```
