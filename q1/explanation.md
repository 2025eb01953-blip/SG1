# Q1 Explanation

- I ran `whoami` and `groups` to confirm the Linux account identity and the groups associated with it. The output showed that the active user is `codespace` and that the account is attached to several development-related groups.
- I checked the current shell and working directory with `echo "$SHELL"` and `pwd`. The environment is using Bash and the current location is the q1 folder inside the lab workspace.
- I listed the repository contents with `ls -la /workspaces/SG1` to verify the workspace layout. The output confirmed that the required q1 through q5 directories are present.
- I tested network reachability with `curl` to verify external connectivity. The command succeeded, showing that the environment can reach YouTube from the container.
