helooooo
# genrate ssh key
  
ssh-keygen -t ed25519 -C "your email"
  
# enter file name, password

# check if ssh agent is running
  
eval "$(ssh-agent -s)"

# add genrated key to agent

ssh-add ./karma1

# open github and find add new ssh key under developer settings

# copy contents of key.pub (here ./karma.pub) to github form and generate the ssh key


#run git clone projectLink

enjoy 
