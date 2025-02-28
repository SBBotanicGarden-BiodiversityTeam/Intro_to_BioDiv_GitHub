# Error: large files detected

    remote: warning: File RAxML and IQtree/VMMV_phylo_RAxML/infile is 62.12 MB; this is larger than GitHub's recommended maximum file size of 50.00 MB
    remote: error: Trace: f1f28987f78d4504561d79f1941a7051548f07c197ab815b2a100c912afe52b7
    remote: error: See https://gh.io/lfs for more information.
    remote: error: File RAxML and IQtree/VMMV_all_RAxML/infile is 316.26 MB; this exceeds GitHub's file size limit of 100.00 MB
    remote: error: GH001: Large files detected. You may want to try Git Large File Storage - https://git-lfs.github.com.
    To https://github.com/mayroberts/VMMV.git
     ! [remote rejected] main -> main (pre-receive hook declined)
    error: failed to push some refs to 'https://github.com/mayroberts/VMMV.git

I got this error essentially saying I was trying to push files that are too big for GitHub to store and this happened because I did not have `infile` included in the .gitignore file which is the file that tells github what file to ignore when I push things from my local repo up.

So to fix this, we need to revert git back to before we commited the offending file. If it was the last commit you made, 
    
    git reset HEAD~

Since I triend all sorts of things before this solution I had more commit to go back. 

`git log` shows your git interactions to help find the commit ID (very long string of numbers and letters) you'll need.

    mayroberts@Mays-Mac-Book_Pro VMMV % git log
    commit 42c374f0cb942aece10eac42a279e7acaae3bb38 (HEAD -> main, origin/main)
    Author: May Roberts <mroberts@sbbotanicgarden.org>
    Date:   Fri Feb 28 13:40:48 2025 -0800
    
        try push after git reset 
    
    commit 09c3eb8d649a631f94d4c2c54064a80f68795127
    Author: May Roberts <mroberts@sbbotanicgarden.org>
    Date:   Fri Feb 28 13:38:01 2025 -0800
    
        .gitignore update
    
    commit f284b99c93addae725ddcd4ca31d3e5382e7ba90
    Author: May Roberts <mroberts@sbbotanicgarden.org>
    Date:   Wed Feb 26 15:47:48 2025 -0800
    
        md updates

`git reset` followed by the commit ID will reset the commits you've made to that point. This will not revert your actual repo/folder to that time, just your gits memory if that makes sense.

    mayroberts@Mays-Mac-Book_Pro VMMV % git reset f284b99c93addae725ddcd4ca31d3e5382e7ba90
    
    vim .gitignore
    git add .gitignore
    git commit -m "update .gitignore to include large infile"
    git push -u origin main
    git add .
    git commit -m "update results files"
    git push -u origin main
