# Description

This my personal console configuration files used in Ubuntu 12.04.5 LTS & 14.04.1 LTS. It will override the default Ubuntu Terminal settings and make the console more informative and Mac like. Though I use it on my Ubuntu 12.04.5 LTS & 14.04.1 versions, but it should work perfectly on other versions of Linux.


## Directory Structure

    Bash-Config/                    -- Base Path
    ├───images/                     -- images directory
    │   ├───old_new_bash.png        -- image to show bash changes
    │   └───special_tweak.jpg       -- image to show special tweak to bash
    ├───ubuntu_12.04/               -- ubuntu 12.04 directory
    │   └───.bashrc                 -- ubuntu 12.04 specific settings file
    ├───ubuntu_14.04/               -- ubuntu 14.04 directory
    │   └───.bashrc                 -- ubuntu 14.04 specific settings file
    ├───LICENSE                     -- license file
    └───README.md                   -- readme file

## Changes to the Files

#### Common changes
1. Changed `HISTSIZE` from 1000 to 10000
2. Changed `HISTFILESIZE`from 2000 to 20000 so that the system can store more history

#### Changes to ubuntu_12.04/.bashrc

1. Uncommented `Line 43` to make console colorful
2. Changed `line 57` console output to make console a bit informative and Mac Like :smiley: :tada:
3. Uncomment `Line 59` and comment `Line 57` to use special tweak of the bash

#### Changes to ubuntu_14.04/.bashrc

1. Uncommented `Line 46` to make console colorful
2. Changed `line 60` console output to make console a bit informative and Mac Like :smiley: :tada:
3. Uncomment `Line 62` and comment `Line 60` to use special tweak of the bash

These changes changed the bash console like this:

![bash preview](/images/old_new_bash.png)

There is an special tweak (need to uncomment to use)

![special tweak](/images/special_tweak.jpg)

## References

[Linux-Unix Shell Setup Parameter][1]

[AskUbuntu Answer][2]

## Licence
The files are open-sourced software licensed under the [MIT license]




[1]: http://www.cyberciti.biz/tips/howto-linux-unix-bash-shell-setup-prompt.html
[2]: http://askubuntu.com/questions/16728/hide-current-working-directory-in-terminal
[MIT license]: http://opensource.org/licenses/MIT
