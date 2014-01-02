golang-user-install-script
==========================

Bash script to automate Go language tools single user installation (Linux) or even removal.

For 32-bit:
<blockquote>bash main.sh --32</blockquote>
For 64-bit
<blockquote>bash main.sh --64</blockquote>

To remove any changes call:
<blockquote>bash main.sh --remove</blockquote>

The script will make .go and go folders on your home directory, add the needed variables and PATH expansion.

<blockquote>$HOME/.go folder is your where go will be installed to.</blockquote>
<blockquote>$HOME/go is the default workspace.</blockquote>

Read more about the workspace at http://golang.org/doc/code.html