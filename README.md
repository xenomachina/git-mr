`git-mr` creates a GitLab merge request (MR) from the command-line.

It pushes the current branch to a same-named branch on origin, setting GitLab
push-options to create a merge request.

The source branch will be set to be removed on merge, and if there is only
one commit, the MR's title and description will be set from the commit's
message. (Otherwise they are left unset, and you'll need to edit in the
GitLab UI.)

(git pro tip: you can run it as `git mr`, as long as `git-mr` is on your path.)
