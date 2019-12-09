when i tried to use git in anaconda on windows, and pushed my work to github.
i had to enter my password and username although i had used ssh.
the following tips
```
bash: /dev/tty: No such device or address
error: failed to execute prompt script (exit code 1)
```
i found one solution but don't know why
change the remote url like this
```
git remote set-url origin https://<username>:<password>@github.com/<username>/<repo_name>.git
```
