# Change Linux Enviroment
You can change your Linux/OS X terminal color more visible by these comment.
You also can see where branch you are on git without typing git status all the time.

## Step one
Create a file .bash_prompt and Paste the file to .bash_pormopt.
<br>
The comment is from <https://github.com/paulirish/dotfiles/blob/master/.bash_prompt>

	vi .bash_prompt
Press "i" to enter into insert mode, then paste the comments. After paste the comments, press :wq to store you comments.
You have to revise you user name and also can revise any color you like inside.
##Step two

	echo [[ -f "$HOME/.bash_prompt" ]] && source "$HOME/.bash_prompt" > .bash_profile

In this step, you make shell to execute the comment in .bash_prompt.

##Step three

	source .bash_profile
