zer0prompt
==========

zer0prompt is a Bash prompt I created after discovering Phil!’s ZSH Prompt. I liked how Phil!’s prompt looked and some of it’s various features but I’m a happy Bash shell user with no need to switch to Z shell. I searched the Internet for various Bash prompts similar to the Phil! ZSH prompt without luck. I tried Bashish but felt there was too much extra going on “under the hood” for what I needed.

It was time to roll up my sleeves and write my own, the way I wanted it and so zer0prompt was born!


Features:
---------

* 18 different colour themes
* a TERMWIDE prompt, fills the width of the terminal no matter how wide.
* 2 line prompt
* the following info is always shown = user, host, current tty, working directory, time, user identifier
* truncates the shown working directory when it’s wider then the terminal.
* shows /home/[user] as a tilde ~
* continuation prompt
* when logged in as root user, display info in red as a visual reminder.
* displays the exit code when a command fails
* sets xterm/rxvt terminal titles (shows username, working directory. and terminal size)
* user selectable colour themes, info colours, time format, and line graphics
* auto detection of supported line graphics mode (standard or fallback)
* user can manually set “no colour mode” and/or “graphics fallback mode"
* very easy to install without making a mess of your .bashrc
* tries not to pollute your bash environment!


Usage:
------

1. Clone the project from github to your local machine.

>  git clone https://github.com/zer0ed/zer0prompt.git

2. Configure user options in zer0prompt/zer0prompt.conf (optional).

3. Append the needed lines into .bashrc

>  cat zer0prompt/install.txt >> ~/.bashrc 

4. Logout then Login to refresh the changes.


Similar Projects and Credit:
----------------------------

Below are some of the projects where I obtained ideas and information for creating zer0prompt.

Phil!'s ZSH Prompt - http://aperiodic.net/phil/prompt/  
Bashish - http://bashish.sourceforge.net/  
TERMWIDE prompt - http://www.tldp.org/HOWTO/Bash-Prompt-HOWTO/x869.html  
Bash Prompt Howto - http://www.tldp.org/HOWTO/Bash-Prompt-HOWTO/  


Screenshots:
------------

![screenshot](.screenshots/prompt.png?raw=true "prompt")
![screenshot](.screenshots/colour_themes.png?raw=true "colour themes")
![screenshot](.screenshots/colour_themes_inverted.png?raw=true "colour themes inverted")
![screenshot](.screenshots/xterm_titlebar.png?raw=true "xterm titlebar")
![screenshot](.screenshots/prompt_continuation.png?raw=true "prompt continuation")
![screenshot](.screenshots/directory_truncation.png?raw=true "directory truncation")
![screenshot](.screenshots/root_notification.png?raw=true "root notification")
![screenshot](.screenshots/error_exit_code.png?raw=true "error exit code")
![screenshot](.screenshots/graphics_fallback_mode.png?raw=true "graphics fallback mode")
