# AEON Funding System
Do more with your cryptocurrency by getting the community involved. The goal of the AEON Funding System is to enable community members to complete projects and be paid for the projects by other community members. 

## Example
This funding system is live at: [https://aeonfunding.com
](https://aeonfunding.com)

## Features
* Proposal system
* Accounting system
* User system
* Stats per proposal
* * Coins received
* * Coins paid out
* * Coins available
* Comment system per proposal
* Wallet / Daemon status
* More in development

## Setup
Be sure to install any and all dependencies. Our funding system is running on Ubuntu 16.04 and confirmed working using the details below. No additional steps should be needed.

### Install dependencies
```sudo apt install python-virtualenv python3 redis-server postgresql-server-dev-* postgresql postgresql-client python-pip virtualenv git```
 
```
git clone https://github.com/aeoncommunity/aeon-funding-system.git
cd aeon-funding-system
virtualenv -p /usr/bin/python3 <venv>
source <venv>/bin/activate
pip install -r requirements.txt
cp settings.py_example settings.py
- change settings accordingly
python run_dev.py
```
Tip: `<venv>` can be anything you want. 
Tip: Your funding system will be ran on whatever port you setup in the config. Running on port 80 is not advised. There are many ways you can have the funding system run on port 80 via Apache/Nginx and many others.

## Credits
Without [Wownero](https://github.com/wownero), this funding system would not be possible. We thank the developers from Wownero. 

## Links
[AEON Community Discord](https://discord.gg/TM8mEsx)
[AEON IRC Channel (freenode)](https://kiwiirc.com/client/irc.freenode.net/aeon)
[AEON Reddit](https://reddit.com/r/aeon)
[AEON BitcoinTalk](https://bitcointalk.org/index.php?topic=641696.0)