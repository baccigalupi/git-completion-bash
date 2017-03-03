# Git completion bash

Borrowed from Shawn O. Pearce <spearce@spearce.org>
Conceptually based on gitcompletion (http://gitweb.hawaga.org.uk/)
And modified for my own use!

## Usage

In `~/.profile`:

    source ~/git-completion.bash

    export GITAWAREPROMPT=~/.bash/git-aware-prompt
    source $GITAWAREPROMPT/main.sh
    export PS1="\[$txtblu\]\w\[$txtrst\] \[$txtcyn\]\$git_branch\[$txtred\]\$git_dirty\[$txtrst\] $ "

## Git aware prompt

Available at [https://github.com/jimeh/git-aware-prompt](https://github.com/jimeh/git-aware-prompt).

