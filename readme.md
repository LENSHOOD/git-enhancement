### Git Enhancement
This repo is to share my own git shorthands and hooks - which can empowered my git and make my daily work more efficient.

#### What's in it ?
The whole project contains two parts:
1. git alias
	Don't you feel so boring and annoying,  when typing everything relate to git you have to type `git<space>` before the real command ?
	Many people build there own git alias, so do I. And mine have already practice at daily work about 2 years，I feel it's very convinient and really improved my efficiency.
	Let's take a look:
	`g` for `git`
	`gs` for `git status`
	`gc` for `git commit`
	More detial please see the readme file in the git-alias dir.

2. git hooks
	I'm not a experienced git-hook user. I use pipleline hook to check code style before, but after the first taste,  I began to love it. 
    Git-hooks is easy to use, and have very few dependencies. Forthemore, git-hooks is lightweight and flexible, I can write it with shell script, python, even put the real check logic into maven or gradle.
	It's a simple demo project In the git-hooks dir, to demostrate how I use git hooks to:
	1. do checkstyle before commit
	2. check if the commit message follows the [Conventional Commit Standard](https://www.conventionalcommits.org).

	I use gradle task to do that, and I'll provide pure shell script solution later...
	
