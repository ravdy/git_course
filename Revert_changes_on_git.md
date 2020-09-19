# Revert changes on git

### Revert changes from working directory
```sh
   git restore <file_name> 
          or
   git checkout -- <file_name>
```
Note: even you can remove changes manually. But if we have updated multiple files and don’t know which lines to remove this command really helps 

### Revert changes from Staging Area
```sh 
   git restore --staged <file_name>  #to revert changes from Staging area to working directory  
   git restore <file_name> #to revert changes from working directory  
```

### Revert changes from Local Repository 
```sh 
   git reset HEAD~         # to revert changes from local repo to working directory
   git restore <file_name(s)> # to revert changes from working directory  
```

### Revert changes from Remote Repository 

We dont have direct way to do this.
