# Merge Practice

~~we're gonna get a good grade~~

## Q1

Clone sets the variable origin to represent the remote repository.


## Q2

The command git push --set-upstream changes what remote branch the current local branch
is tracking.

## Q3
~~~
*   14f5c06 Merge branch 'master' of https://github.com/eamspoker/MergePractice into JeremyBranch
|\  
| * 397ce57 Fixed markdown in README
* | 9c468f3 Edited SpicyFile
* | 446a3ba Brought Person A's File to the bracnh
|/  
* e65dc32 changed Readme
* 7f03f4f added text file
* 8719b7d created readme
~~~
This is an illustration of the branching and merging of what happens when the
git pull origin master is executed

## Q4

No, the command just added the data from master to my local.

## Q5

This is a merge because a rebase adds on branch data to the end of a 
sequence and then deletes the branch, while our branch is still intact, 
because the two different branches were preserved in version control history. 

## Q6 

The local master branch is still behind the remote master.

## Q7

No, the remote branch was removed without any effect on the local version
 of JeremyBranch.

## Q8

~~~
*   commit 88738c290c103d24ef5d19e98033457cc8100483 (HEAD -> master, origin/master, origin/HEAD)
|\  Merge: 48cacf2 620fde8
| | Author: jgart20 <34671257+jgart20@users.noreply.github.com>
| | Date:   Mon Sep 16 09:51:00 2019 -0600
| | 
| |     Merge pull request #3 from eamspoker/Feature2
| |     
| |     edited spicyfile
| |   
| *   commit 620fde824d6fada7fb2f72a8ddeff3494b75809b
| |\  Merge: c13fd15 48cacf2
| |/  Author: jgart20 <34671257+jgart20@users.noreply.github.com>
|/|   Date:   Mon Sep 16 09:50:51 2019 -0600
| |   
| |       Merge branch 'master' into Feature2
| | 
* | commit 48cacf2e490abd0bcc73b85007ea092fe22292fd
| | Author: Jeremy Gart <jgart20@jgart20.local>
| | Date:   Mon Sep 16 09:47:44 2019 -0600
| | 
| |     Edited SpicyFile
| |   
* |   commit d7c5e9d7229769633e73a026af9619f812073dbe
|\ \  Merge: 000b889 1143f08
| | | Author: Jeremy Gart <jgart20@jgart20.local>
| | | Date:   Mon Sep 16 09:42:50 2019 -0600
| | | 
:
| | 
| |     Merge pull request #3 from eamspoker/Feature2
| |     
| |     edited spicyfile
| |   
| *   commit 620fde824d6fada7fb2f72a8ddeff3494b75809b
| |\  Merge: c13fd15 48cacf2
| |/  Author: jgart20 <34671257+jgart20@users.noreply.github.com>
|/|   Date:   Mon Sep 16 09:50:51 2019 -0600
| |   
| |       Merge branch 'master' into Feature2
| | 
* | commit 48cacf2e490abd0bcc73b85007ea092fe22292fd
| | Author: Jeremy Gart <jgart20@jgart20.local>
| | Date:   Mon Sep 16 09:47:44 2019 -0600
| | 
| |     Edited SpicyFile
| |   
* |   commit d7c5e9d7229769633e73a026af9619f812073dbe
|\ \  Merge: 000b889 1143f08
| | | Author: Jeremy Gart <jgart20@jgart20.local>
| | | Date:   Mon Sep 16 09:42:50 2019 -0600
| | | 
| | |     Merge branch 'master' of https://github.com/eamspoker/MergePractice
| | 
| |     Merge pull request #3 from eamspoker/Feature2
| |     
| |     edited spicyfile
| |   
| *   commit 620fde824d6fada7fb2f72a8ddeff3494b75809b
| |\  Merge: c13fd15 48cacf2
| |/  Author: jgart20 <34671257+jgart20@users.noreply.github.com>
|/|   Date:   Mon Sep 16 09:50:51 2019 -0600
| |   
| |       Merge branch 'master' into Feature2
| | 
* | commit 48cacf2e490abd0bcc73b85007ea092fe22292fd
| | Author: Jeremy Gart <jgart20@jgart20.local>
| | Date:   Mon Sep 16 09:47:44 2019 -0600
| | 
| |     Edited SpicyFile
| |   
* |   commit d7c5e9d7229769633e73a026af9619f812073dbe
|\ \  Merge: 000b889 1143f08
| | | Author: Jeremy Gart <jgart20@jgart20.local>
| | | Date:   Mon Sep 16 09:42:50 2019 -0600
| | | 
| | |     Merge branch 'master' of https://github.com/eamspoker/MergePractice
| | |     
| | |     Pulling in new data from master branch!
| | | 
* | | commit 000b889254cd17719d6ed81108d9632b85b9a80b
| | | Author: Jeremy Gart <jgart20@jgart20.local>
| | | Date:   Thu Sep 12 13:01:32 2019 -0600
| | | 
| | |     Created branch and added different file
| | | 
| | * commit c13fd155c471e0c38c4fee7da928d89da3047980 (origin/Feature2)
| |/  Author: Emily Amspoker <eamspoker21@kentdenver.org>
| |   Date:   Mon Sep 16 09:48:05 2019 -0600
| |   
| |       edited spicyfile
| |   
| *   commit 1143f085353ecad2524010ba202ad9adf959bb14
| |\  Merge: 579105a b4b36c3
| | | Author: eamspoker <46005655+eamspoker@users.noreply.github.com>
| | | Date:   Mon Sep 16 09:42:23 2019 -0600
| | | 
| | |     Merge pull request #2 from eamspoker/JeremyBranch
| | |     
| | |     Updated readme with new questions answered
| | | 
| | * commit b4b36c3b7fc84b2ba48f554e4ef2b848380d2e3f (origin/JeremyBranch)
| | | Author: Jeremy Gart <jgart20@jgart20.local>
| | | Date:   Mon Sep 16 09:41:19 2019 -0600
| | | 
| | |     Updated readme with new questions answered
| | |   
| * |   commit 579105a9a5fffbf4120d0be3e26ed196b399a3b3
| |\ \  Merge: 397ce57 14f5c06
| | |/  Author: eamspoker <46005655+eamspoker@users.noreply.github.com>
| | |   Date:   Mon Sep 16 09:39:18 2019 -0600
| | |   
| | |       Merge pull request #1 from eamspoker/JeremyBranch
| | |       
| | |       Jeremy branch
| | |   
| | *   commit 14f5c06cf0a2e95f1704a4e6c6080e18e9bfdad0
| | |\  Merge: 9c468f3 397ce57
| | |/  Author: Jeremy Gart <jgart20@jgart20.local>
| |/|   Date:   Thu Sep 12 13:24:44 2019 -0600
| | |   
| | |       Merge branch 'master' of https://github.com/eamspoker/MergePractice into JeremyBranch
| | |       
| | |       pulling in emily's changes
| | | 
| * | commit 397ce57bb9fe6271e6a8e9594b07a2e142f41228
| | | Author: Emily Amspoker <eamspoker21@kentdenver.org>
| | | Date:   Thu Sep 12 13:17:11 2019 -0600
| | | 
| | |     Fixed markdown in README
| | | 
| | * commit 9c468f3eb38f2631cc798c3620c42604116aa1b5
| | | Author: Jeremy Gart <jgart20@jgart20.local>
| | | Date:   Thu Sep 12 13:17:26 2019 -0600
| | | 
| | |     Edited SpicyFile
| | | 
| | * commit 446a3ba225e8fecc1a2fefe6d15d95ad13cffc3d
| |/  Author: Jeremy Gart <jgart20@jgart20.local>
| |   Date:   Thu Sep 12 13:10:12 2019 -0600
| |   
| |       Brought Person A's File to the bracnh
| | 
| * commit e65dc320d74c6dc701d34ac206bd0efc7c315b31
| | Author: Emily Amspoker <eamspoker21@kentdenver.org>
| | Date:   Thu Sep 12 13:04:22 2019 -0600
| | 
| |     changed Readme
| | 
| * commit 7f03f4ffb9229664b4d43032f8ddb38b86344416
|/  Author: Emily Amspoker <eamspoker21@kentdenver.org>
|   Date:   Thu Sep 12 12:49:01 2019 -0600
|   
|       added text file
| 
* commit 8719b7df026b42734cb251b0a25b88ffded25bb2
  Author: eamspoker <46005655+eamspoker@users.noreply.github.com>
  Date:   Thu Sep 12 12:40:48 2019 -0600
  
      created readme
~~~
