# kubectl-alias

```
alias k='kubectl -n $n'
alias kd='kubectl -n $n describe'
alias kg='kubectl -n $n get'
alias kl='kubectl -n $n logs'
alias klf='kubectl -n $n logs -f --since=5m'
alias kpd='kubectl -n $n delete pod'
alias kpdf='kubectl -n $n delete pod --force --grace-period=0'
```

Set the n value as namespace name

Example:

```
n=default
```

Get the pods from default namespace

```
k get po
```
