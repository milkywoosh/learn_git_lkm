how to delete all log history : https://stackoverflow.com/questions/13716658/how-to-delete-all-commit-history-in-github


++++ Note for Github

- check last git activity
git status

- add specific file into repo
git add anyFile.txt	

- commit message use HEADER and BODY
git commit [ -m HEADER message” ]	[ BODY MESSAGE: create message for commit we made ]

- check log commit message
git log 	check history of commit with message and its hash code

- check commit message with simple list
git log --oneline	check unique number of commit history

- add all editted files to staging area
git add .	set status change we made just

- go back to previous specific commit directly, and overwrite all lastest update
git revert NUMBER COMMIT	

- add file to repo to specific existed repo
git remote add origin https://github.com/milkywoosh/jstrial-milkywoosh.git
git remote add origin <http of the repo>

- push file to github repo
git push -u  origin master  [master adalah nama branch utama di Github]

- check list remote which repe address push
git remote -v

- delete push
git remote rm origin

- after commit change the code in local git
git push -u origin master

- fetch the changing after other person commit a change in our repo
first -> git fetch 
git pull origin master

- clone folder and data from github repo
git clone http_address_of_repo

- push update to specific remote branch: for example -> "jstrial_mac" 
git push origin jstrial_mac


- go to specific branch
git checkout -b namebranch

- push to remote branch github
git push origin HEAD:branch2

	
git config –global user.name “milkywoosh”	

git config –global user.email “name@email.com”	





// HOW TO PULL REQUEST

- go to REPO target punya orang
- FORK ke akun pribadi
- clone to local repo
- create new branch : -> git branch "new_name_branch"
- ke branch baru: -> git checkout new_name_branch
- edit file yg akan kita kontribusi
- git add . then git commit -m "any message"
- git remote add upstream "address REPO target"
- git push -u origin "spesifik branch target"
- kemudian: git push -u origin "new_name_branch"
- MENUNGGU RESPON OWNER REPO TARGET



