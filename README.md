**Helper commands :**

- git branch -M main
- git remote add origin https://github.com/burhankhaja/TezRep.git
- git push -u origin main

- git remote -v
```c
  // sample
origin  https://github.com/burhankhaja/TezRep.git (fetch)
origin  https://github.com/burhankhaja/TezRep.git (push)
```
**For multiple fetches and pushes**
- git remote add $IDENTIFIER $LINK_TO_REPO
- then git push -u $IDENTIFIER main

**IN case two remote origins cause errors due to direct commit changes in github on each of them, do this :**
-  git pull --no-rebase $IDENTIFIER_ORIGIN main
-  otherwise you cant push to the repo that had some changes past your local copy



**tried `git push` for simultaneous two repo pushing but failed to get change in both , don't know ?**

