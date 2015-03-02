# Git tute

## Environment Setup
	1. ssh-keygen -t rsa -C "email" // in ~/.ssh/id_rsa.pub
	2. github Acount setting
	3. ssh -T git@github.com
	4. git config --global user.name "name"
	5. git config --global user.email "email"

## Initiation
	git init

## operation with remote repositories

	git remote -v
	git remote add upstream //repository url
	git fetch upstream
	git checkout master
	git merge upstream/master


## 本地添加到repository

git add .
git commit -m 'message string'
git push upstream master

## 删除后添加到repository

rm ...
git add --all
git commit -m 'delete'
git push upstream master

## Clone
	git clone "url"

