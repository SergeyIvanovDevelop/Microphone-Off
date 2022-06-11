<p align="center">
  <a href="https://github.com/SergeyIvanovDevelop/Microphone-Off">
    <img alt="Microphone-Off" src="./resources/logo.png" width="280" height="280"/>
  </a>
</p>
<h1 align="center">
  Microphone-Off
</h1>

## Microphone-Off &middot; [![GitHub license](https://img.shields.io/badge/license-CC%20BY--NC--SA%203.0-blue)](./LICENSE) [![BASH](https://img.shields.io/badge/shell-bash-brightgreen)](https://www.gnu.org/software/bash/) [![Linux](https://img.shields.io/badge/OS-Linux-lightgrey)](https://www.linux.org/) [![LinkedIn](https://img.shields.io/badge/linkedin-Sergey%20Ivanov-blue)](https://www.linkedin.com/in/sergey-ivanov-33413823a/) [![Telegram](https://img.shields.io/badge/telegram-%40SergeyIvanov__dev-blueviolet)](https://t.me/SergeyIvanov_dev) ##

This repository contains a `bash` script that allows you to disable the microphone at the `Linux` OS level. As you know, in `Linux` **ALL** is a **file**, therefore, to ensure that microphones are disabled in the system (there may be many reasons why this may be necessary), it is enough to delete the microphone files. To restore the files, just restart the device discovery service. This functionality is implemented in the `bash` script below.

## :computer: Getting Started  ##

**Step 1**

1. Go to home directory and clone repository from github: `cd ~ && git clone https://SergeyIvanovDevelop@github.com/SergeyIvanovDevelop/Microphone-Off`

**Step 2**<br>

2. Go to the directory of the downloaded repository: `cd ~/Microphone-Off`

**Step 3**<br>

3. Execute the `bash` script: `./mic_switch <mic_device_filename> <on>|<off>`

_Note: The hardest part is identifying the microphone file. For example, it could be `pcmC1D0c`_

_:warning: With a little adaptation of this script, it can also be used on rooted `Android` devices (tested on `Samsung Galaxy J7. Android 6 (Marshmallow)`)_ 

### :bookmark_tabs: Licence ###
Microphone-Off is [CC BY-NC-SA 3.0 licensed](./LICENSE).
