ug - an ad-hoc `curl | sh` install script manager

if you choose to use this, do so at your own risks
links may change
i make no guarantees

should be POSIX compliant too.

so, this is all you need to do:

create a text file at `~/.local/share` called `l_l`
format the given install script as follows:

<label>:<script>

this must be on one line only

ug accepts one argument with two possibilities:

all - execute all install scripts
<label> - execute the install script for the specified label

labels must be unique;
labels must contain underscores, hyphens, or alphanumeric ANSI characters.

prototyped by me, refined and rewritten with help from GPT4

you can read about the process of making `ug` here:
https://rgibbons-dev.github.io/ug
