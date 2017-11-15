## Tmux Recommended configuration

>All the tmux configurations are stored in the file ~/.tmux.conf in your home directory.

I’d really recommend beginners to remap the default “prefix” from ctrl-b to ctrl-a. The “prefix” is a key combination control that you have to press before triggering any of the tmux commands/operations. By default it is ctrl-b, but we’d want to remap it to ctrl-a.

I have added `.tmux.conf` file which contains a configuration for the tmux that can ease our work.

  * Download it and paste it in the home directory.
  * Reload the tmux config file from shell:

  ```shell
    tmux source-file ~/.tmux.conf
  ```

### Commands:-

  * To start the TMUX, Type

  ```shell
    tmux
  ```
  in Terminal, Tmux window will open.

  * To Split the window **Horizontally**, Press

  ```shell
    prefix[ctrl+a] + h
  ```

  * To split the window **Vertically**, Press

  ```shell
    prefix[ctrl+a] + v
  ```

  * To **switch** to different panes, Press

  ```shell
    prefix[ctrl+a] + [Arrows Key]
  ```
   OR

   >You can use switch using mouse by clicking on the required pane.

## Getting Started with Tmux

Here are some links to get started with Tmux:-

  1. [Getting started with tmux](https://www.rosehosting.com/blog/getting-started-with-tmux/)

  2. [Tmux: A Simple Start](https://www.sitepoint.com/tmux-a-simple-start/)

  3. [TMUX: My Getting Started Guide](http://www.howardism.org/Technical/Linux/tmux.html)

  4. [A Gentle Introduction to tmux](https://hackernoon.com/a-gentle-introduction-to-tmux-8d784c404340)




