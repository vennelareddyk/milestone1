# milestone1
steps included:
1. install the 'wsl' using wsl --install commond in command prompt/ power shell
2. Then install the docker window and signup the docker window before that restart the computer
3.Now install the the gitbash for windows
4.And type the command cvat inorder to open the cvat. the commands are as follows
git clone https://github.com/opencv/cvat
cd cvat
docker-compose up -d
winpty docker exec -it cvat_server bash -ic 'python3 ~/manage.py createsuperuser'
enter the username and password
Make sure the docker window is ruuning parallel.
now we can find that cvat is ruuning and is shiwn in docker window.
Installation is done .
