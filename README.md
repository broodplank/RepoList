RepoList
========

Function: 

This shell script allows you to fetch ALL repositories from a github user / organization.
The advantage of this script is that it does not need the Github API and thus has no rate limit.
It will fetch raw html pages and grep the repositories out of it.



Installation (with this readme):
- git clone https://github.com/broodplank/RepoList
- mv RepoList/repolist ~/bin/repolist
- chmod +x ~/bin/repolist


Usage:
Repolist only requires 1 parameter which is the Github username/organization
- repolist [github username]

example:
- repolist broodplank

Afer the fetching is done, the repositories will be listed in the 'links' file in your current directory.

Afterwards the script will ask you if it should generate a auto clone script. 
If you choose yes it will generate 'autoclone.sh' in the current directory



