# practice
Practise with git and GitHub, requests except for my students' will be ignored, but feel free to send them in anyway.

This short and simple tutorial assumes you do at least have a basic understanding of `git`.

Follow the steps below in order.

> Unsure what something means? Google it!

> Read an entire step before your start typing.

# Step 0

## Log in
Make sure that you are logged into your GitHub account.

## Get ready
If you have not already done so, make sure that you can connect to GitHub using SSH.

- Make sure that you have a SSH keypair on  your local machine
- Make sure that added your SSH pubkey to your [GitHub account](https://github.com/settings/keys).

# Step 1

## If you are studying by yourself
Fork this repo to you own account.

Continue to step 2.

## If you are part of a group
Pair up (sit next to each other so you can look at both screens).
One student in each pair will fork this repo to their account.
The other student will fork from their fellow student's repo.

> In the following steps, "your fork" refers to the second fork you made.
> You will mostly be working on the machine of the student that forked their fellow student's fork.
> The first fork can later be used to accept all the requests you'll make while practicing.

Continue to step 2.

# Step 2
Clone your fork to your local machine.

# Step 3

Edit the file `text.txt`, then add and commit your changes.

# Step 4

Push your changes back to your repo on GitHub.

# Step 5

Create a merge request for the original repo to get your changes in there (on the main branch).

## If you are part of a group

Check back onto your other machine, the merge request should be there.

# Step 6

On your command line, switch to the `develop` branch.

The file `indev.txt` should now be visible.

# Step 7

Edit `indev.txt`, then add and commit your changes.

# Step 8

Push your changes to your version of the `develop` branch on GitHub.

# Step 9

As before, create a merge request, this time, from your version of the `develop` branch to the original repo's version of the `develop` branch.

## If you are part of a group

Try accepting the two merge requests on the other GitHub account.

- Does the fork of the fork need to do anything once the original fork has accepted the merge requests?
- Go through the steps again, reversing the role of the accounts, can you fork this repo if you've previously forked from a fork of this repo?
