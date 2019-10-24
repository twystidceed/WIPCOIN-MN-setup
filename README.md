# WIPCOIN-MN-setup
WIPCOIN Masternode Setup DIP003 NODES ONLY - 
<br>
<li>sudo apt-get update
<li>sudo apt-get install git
<br><br>
<li> If you need the script to make a node <b> WITH SWAP</b> Use this line to install
<li> This is typical usage with VULTR and Digital Ocean 
<li>Copy the entire line below and paste into your ssh session or vps terminal
<li>git clone https://github.com/twystidceed/WIPCOIN-MN-setup.git && cd WIPCOIN-MN-setup && bash wipcoin-setup.sh
<br><br>
<li> For installation on VPS with preset swap use this line - <b>This does NOT install Swap</b> 
<li> This is typical for more specialized nodes for advanced users
<li>Copy the entire line below and paste into your ssh session or vps terminal
<li>git clone https://github.com/twystidceed/WIPCOIN-MN-setup.git && cd WIPCOIN-MN-setup && bash wipcoin-setup-noswap.sh
<li><b>If script asks for input about a version  - select Y for package maintainers version and hit enter to continue</b>

