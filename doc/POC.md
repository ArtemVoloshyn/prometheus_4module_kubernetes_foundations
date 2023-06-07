This is demo link with confirmation of Argocd installation https://asciinema.org/a/590051

GUI access confirmed by screenshot in this folder

Command used to get initial admin password is:

```kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d```