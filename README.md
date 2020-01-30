# CSE141L Home Page

This is the starting point for CSE141L.

## Lecture Slides

Available via google drive: https://drive.google.com/drive/folders/1uSgifPM0FluKMH0OcjHQzwUiI_vCrMEp?usp=sharing

## Labs

Due dates are set in gradescope.  Look for them there.

**Note** The links below are disabled until the lab is released (typically around class time).

**Note** The importing process in GitHub Classroom can take a surprisingly long time.  Be patient.

| Number | Name   | Section A Github classroom link         | Section B Github classroom link         | 
|--------|--------|-----------------------------------------|-----------------------------------------|
| 1      | Intro  | [link](https://classroom.github.com/a/IjkqbBTv) | [link](https://classroom.github.com/a/-VPj3rda) |
| 2      | Characterizing  |[link](https://classroom.github.com/a/S1PAs7SE) | [link](https://classroom.github.com/a/tV9Oz_P4) |
| Olympics1 | Pipeline Olympics | [link](https://classroom.github.com/a/sDstmQly) | [link](https://classroom.github.com/a/EMftLy7H) |
| 3      |   |    | |
| 4      |   |    | |
| 5      |   |    | |
| 6      |   |    | |
| 7      |   |   | |
| F1      |   |    | |
| F2     |   |   | |

## Pulling Updates

Occasionally, we find bugs in the starter repo and push updates to it.  Every time you run `runlab` it will check for updates.  To check explicitly, you can do

```
runlab --info
```

Which might generate

```
===================================================================
# The lab starter repo has been changed.  The diff follows.
# Do `runlab --merge-updates` to merge the changes into your repo.
diff --git a/README.md b/README.md
index 700cbaa..d5b2309 100644
--- a/README.md
+++ b/README.md
@@ -3,7 +3,7 @@
 In this lab you will set up the lab environment and learn how to gather
 information about programs using the course tools.  You will download
 some starter code, build and run it in a Docker container, modify the
-code and push the changes to a git repo.  Run the code in the cloud on
+code, and push the changes to a git repo.  Run the code in the cloud on
 our reference processor to gather some data.
```

Then you can do 

``` 
runlab --merge-updates
```

to integrate the changes into your repo.  After which you could do:

```
runlab --info
```

and see

```
No updates available for this lab.
INFO               :
=======            :
lab_name           : Introduction to the Development Environment
short_name         : intro
...
```
## Tip and Tricks

1. [Getting Docker Running On Your Machine](Getting-Docker.md)
2. [Runlab Quick Reference](runlab-quickref.md)
3. [Type your github password less](https://help.github.com/en/github/using-git/caching-your-github-password-in-git)
4. [Working around the limitations of ieng6](ieng6-fixes.md)
5. [Change github accounts no gradescope](use-a-different-github-account.md)


