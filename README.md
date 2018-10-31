# Overview

**NOTE**: These are *not* officially-supported IBM tools. They are provided
here as a best-effort individual approach. Be careful when using these tools -
you could quickly delete a lot of stuff by accident! 

This repo provides a bash script, `ibmcloud-cli-utils`, which can be sourced
to provide two functions:

`ibmcloud-service-delete-interactive` and `ibmcloud-app-delete-interactive`.

These provides a multi-selectable list, managed by `fzf`, to delete services
and apps respectively. You can multi-select from the list using the `<Tab>`
key (see `man fzf` for other keybindings). When you hit Return, the selected
apps and services will be immediately deleted - be careful!

## Installation

* Pre-reqs: [FZF](https://github.com/junegunn/fzf).

* Add `source <dir>/ibmcloud-cli-utils` or similar to a shell startup script,
  such as `~/.bashrc`.
