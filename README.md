# pywin32-issue-reproduction
Repo to reproduct pywin32 issue https://github.com/mhammond/pywin32/issues/2558


Steps to Reproduce:
1) Clone this repository: https://github.com/shloktech/pywin32-issue-reproduction
2) Run the command `docker build Dockerfile` in a Azure DevOps pipeline environment
3) It will give error: `No matching distribution found for pywin32==307`
