# masteruah
masteruah
ssh-keygen -t rsa -b 4096 -C "fzamoraperez@gmail.com"
ssh -add $HOME/.ssh/id_rsa
cat $HOME/.ssh/id_rsa
ssh -T git@github.com