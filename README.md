C:\Users\91987\rev1>git cherry-pick 6cd3c13b9642a0683c2c80852cc7b3ea37b0c8b1^..083bf400d0f64c8a36730fe906d350283c69c9a7
Auto-merging rev2.txt
CONFLICT (add/add): Merge conflict in rev2.txt
error: could not apply 48ebdec... first
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git cherry-pick --continue".
hint: You can instead skip this commit with "git cherry-pick --skip".
hint: To abort and get back to the state before "git cherry-pick",
hint: run "git cherry-pick --abort".

C:\Users\91987\rev1>git add .

C:\Users\91987\rev1>git cherry-pick --continue
[fb3 10c8d16] savefirst
 Date: Mon Mar 4 10:21:24 2024 +0530
 1 file changed, 4 insertions(+), 1 deletion(-)
Auto-merging rev2.txt
CONFLICT (content): Merge conflict in rev2.txt
error: could not apply 083bf40... second
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git cherry-pick --continue".
hint: You can instead skip this commit with "git cherry-pick --skip".
hint: To abort and get back to the state before "git cherry-pick",
hint: run "git cherry-pick --abort".

C:\Users\91987\rev1>git add .

C:\Users\91987\rev1>git cherry-pick --continue
[fb3 bda3491] savesecond
 Date: Mon Mar 4 10:22:02 2024 +0530
 1 file changed, 3 insertions(+)

C:\Users\91987\rev1># expr8
