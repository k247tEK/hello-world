# hello-world

###### Hello-World Public<br>repository<br>k.

### how-to - ssh Connect to Github

~~~
eval `ssh-agent -s`

ssh-add -l -E sha256

ssh-add ~/.ssh/k247tEK/id_rsa
enter pass...

ssh-add -l -E sha256
4096 SHA256:xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx user@email.com (RSA)

ssh -T git@github.com
Hi k247tEK! You've successfully authenticated, but GitHub does not provide shell access.

git config --list
~~~

### how-to - create id_rsa & id_rsa.pub

~~~
cd ~/.ssh/[user]
ssh-keygen -o -t rsa -b 4096 -C "[user]@email.com"
###### Note: use pass to protect key..... ######
~~~

---
#EOF