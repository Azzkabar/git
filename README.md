# git

Git, a ubiquitous version control system, is present on every developer's machine, simplifying branch creation and merging. Concurrently, GitHub enhances the accessibility of Git for both individuals and teams, facilitating version control and collaborative efforts 

I'm delighted to provide you with a set of Git commands I employed in crafting my GitHub portfolio.

##### Creating, cloning, pushing and pulling repositories  
```git
git init Azzkabar                                           # Create your repository with the same name as your username 
git clone git@github.com:Azzkabar/Azzkabar.git              # Clone your repository on your computer to a separate folder
git clone git@github.com:Azzkabar/test      .git            # Clone https://github.com/Azzkabar/test on your computer to a separate folder
cd Azzkabar                                                 # Push data from Azzkabar repository to your own one 
git commit -m "commited change description"                 # Add commit 
git push                                                    # Push change

```

##### Creating, adding remote repositories  
```git
git init SQL                                                # Create separate repository for portfolio item 
git remote add SQL git@github.com:Azzkabar/SQL.git          # Declarie repository remotely 
README.md edited manually                                   # Add links to your repositories to the README.md file
git commit -m "commited change description"                 # Push changes to remote repository
git push                                                     

```
