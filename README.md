# git-alias

Personal git configuration used in day-to-day projects to make the developer's life more productive and effective

````text
[alias]
	br = branch
	ci = commit
	cm = !git add -A && git commit -m
	co = checkout
	cob = checkout -b
	df = diff
	ec = config --global -e
	i = init
	lg = log -pgit ps
	lg1 = log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit
	lg2 = log --graph --abbrev-commit --decorate --date=relative --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all
	lg3 = log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold cyan)%aD%C(reset) %C(bold green)(%ar)%C(reset)%C(bold yellow)%d%C(reset)%n''          %C(white)%s%C(reset) %C(dim white)- %an%C(reset)' --all
	pl = pull
	plb = pull origin
	pom = pull origin master
	ps = push
	psb = push origin
	st = status
 	plm = pull origin master
 	psm = push origin master
 	rao = remote add origin

[color]
	branch = auto
	diff = auto
	grep = auto
	interactive = auto
	status = auto
	status = auto

[core]
	editor = mate -w

[help]
	autocorrect = 1

[user]
	name = YOUR NAME
	email = YOUR EMAIL

````
