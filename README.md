# ssm-session

## Requirements
* Bash
* [jq](https://stedolan.github.io/jq/)
* [fzf](https://github.com/junegunn/fzf)
* [aws-cli](https://docs.aws.amazon.com/ja_jp/cli/latest/userguide/cli-chap-install.html)
* [session-manager-plugin](https://docs.aws.amazon.com/ja_jp/systems-manager/latest/userguide/session-manager-working-with-install-plugin.html)

## Installation
Copy/Link `ssm-session` file in the directory specified in PATH.

e.g.
```sh
ln -s ${PWD}/ssm-session /PATH/TO/bin
```

## Run
### Start session
1. `ssm-session start`
