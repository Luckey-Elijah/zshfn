# Zsh Functions

Shell functions I've written and use relatively frequently.

## Install on `zsh`

1. Clone this project to desired path

2. Edit your `~/.zshrc` to include the path of clone with the following lines

```sh
fpath=( "/path/to/clone/zshfn" "${fpath[@]}" )
autoload -Uz $fpath[1]/*(.:t)
```

3. Run `exec zsh` in your terminal

You're done! you can now run any of the scripts in the project. Call the script via the file name.
