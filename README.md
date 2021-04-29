ERROR:
I edited ~/.ssh/config file like this:
Host github-10gen
    HostName github.com
    User git
    IdentityFile ~/.ssh/new_key_file
    IdentitiesOnly yes
I set remote url like this:
git remote set-url origin git@github-10gen:10gen/ops-manager-cloudfoundry
Trying
git push origin dev
but getting error:
ssh: Could not resolve hostname github-10gen: Name or service not known
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
