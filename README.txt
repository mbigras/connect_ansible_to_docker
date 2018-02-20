Connect Ansible to Docker

Example

docker build --tag mbigras/someimage .
docker run -itd --name somecontainer mbigras/someimage
docker exec somecontainer ruby --version
OCI runtime exec failed: exec failed: container_linux.go:296: starting container process caused "exec: \"ruby\": executable file not found in $PATH": unknown
ansible all -m ping
ansible-playbook some.yml
docker exec somecontainer ruby --version
ruby 2.0.0p648 (2015-12-16) [x86_64-linux]

Links

https://just-thor.com/2017/02/how-to-connect-to-docker-from-ansible/