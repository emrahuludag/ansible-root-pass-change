# ansible-root-pass-change
How to change root password with ansible


```
ansible-playbook main.yml -kK --ask-vault-pass -e username=testuser

```

**without vault**

``` 
ansible-playbook main.yml -kK -e password=test123 -e username=testuser

```