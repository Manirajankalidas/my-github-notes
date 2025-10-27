# Clone the remote GitHub repository to the local Linux Machine for offline development and version control operations. 

1. Retrieved the repository's HTTPS clone URL from Github.

2. Navigate to the desired local directory. 

3. Excuted the git clone cmd to duplicate the remote repository. 

'''
git clone https://github.com/Manirajankalidas/my-github-notes.git
'''

4. verifed successfully cloning by list files (ls) and check remote linkage. 

'''
git remote -v
'''

# Purpose:
To establish a synchronized local copy of the GitHub repository, enabling direct code edits, commits and push operations without relying solely on the web interface.

# Results:
* local repository created with an active connection to remote GitHub origin. 
* Verified remote URL for both fetch and push operations. 
* Environment read for local version control workflow (add -> commit -> push) 
