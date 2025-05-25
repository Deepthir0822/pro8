sudo adduser [username]

sudo usermod -aG sudo [username]

ssh-keygen

ssh-copy-id [username]@[remote-host]
cat /etc/resolv.conf or hostname -i
ssh ansible@192.168.0.81
sudo apt update
sudo apt install ansible -y
ansible --version
sudo mkdir -p /etc/ansible
sudo nano /etc/ansible/hosts
localhost ansible_connection=local
ansible-inventory --list -y
sudo ansible all -m ping

mkdir maventest1
cd maventest1
archetype:generate \
-DgroupId=com.yourname \
-DartifactId=repo_name \
-DarchetypeArtifactId=maven-archetype-quickstart \
-DinteractiveMode=false

git init
git add .
git commit -m “project created”
git branch -M main
git remote add origin https://github.com/amitdalvik/xyz.git
git push -u origin main
