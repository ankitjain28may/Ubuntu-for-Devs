# Make your Ubuntu the best Developer experience ever.
---

> Linux is awesome for usage on servers, So it is preferred by most of the developers and here are some ways to make your system more developer friendly -

## Install these softwares - 
 
 * [Sublime Text 3](https://www.sublimetext.com/download) - Fast and Feature Rich text editor.
 * [Git](https://git-scm.com/download/linux)- Git Version Control.
 * [Tmux](https://github.com/tmux/tmux)- Terminal Multiplexer for splitting view, keyboard shortcuts etc.

## Now let's make the best of everything -

 1. Sublime - 

     * [Install](https://packagecontrol.io/installation) Package Control.
     * Install Source Code Pro font.
     * Install usefull packages by doing this -
        - Go to Prefences>Package Settings>Settings-User
        - It will open Package Control.sublime-settings, there find the **installed_packages** field.
        - It will be an empty array, change it to this - 
          ```md
            "installed_packages":
            [
              "A File Icon",
              "AutoFileName",
              "CodeFormatter",
              "Emmet",
              "JS Snippets",
              "phpcs",
              "DocBlockr"
              "Markdown Preview",
              "Material Theme",
              "Package Control",
              "PackageResourceViewer",
              "SideBarEnhancements"
            ],
          ``` 

     * Customize every setting in sublime.
        - Open Preferences>Settings.
        - This will open Preferences.sublime-settings file.
        - In that place the content of Preferences.sublime-settings file present in this repo's Sublime folder.
        - This makes some important changes like : 
            * Excludes folders like node_modules from sidebar directory listing.
            * Adds newline at the end of every file.
            * Changes the sublime theme.
            * Indents with 2 spaces on using Tab.

            
     * Add custom snippets.
     * Add custom keyboard shortcuts.
