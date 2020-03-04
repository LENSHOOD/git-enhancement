### Git Enhancement
This repo is to share my own git shorthands and hooks - which can empowered my git and make my daily work more efficient.

#### What's in it ?

The whole project contains three parts:

**1. git alias**

  Don't you feel so boring and annoying, when typing everything relate to git you have to type `git<space>` before the real command?
  
  Many people build there own git alias, so do I. And mine have already practice at daily work about 2 years，I feel it's very convinient and really improved my efficiency.
  
  Let's take a look:
  - `g` for `git`
  - `gs` for `git status`
  - `gc` for `git commit`
  
More detial please see the readme file in the git-alias dir.
	
**2. git hooks demo**

  I'm not an experienced git-hook user. I use pipeline hook to check code style before, but after the first taste, I began to love it. 
  
  Git-hooks is easy to use, and have very few dependencies. Furthermore, git-hooks is lightweight and flexible, I can write it with shell script, python, even put the real check logic into maven or gradle.
 
  There is a simple demo project in the git-hooks-demo dir, to demonstrate how I use git hooks to:

  1. Do checkstyle before commit.
  2. Check if the commit message follows the [Conventional Commit Standard](https://www.conventionalcommits.org).
  3. Run all tests before push.

**3. conventional commit message checker by shell**

  According to the demo above, it contains a commit message hook to check if the message is following conventional commit message format.
  
  Actually such format checker is esay to find at NPM world, like: [Husky](https://github.com/typicode/husky), but I cannot find some properly java solution yet, so I write a simple shell based commit-msg hook to do so.
  
  Get and try it in git-hooks dir.
  
> Check the article series of [*Clean Git*](https://lenshood.github.io/2019/04/08/keep-git-branch-clean/) at my personal blog. 
