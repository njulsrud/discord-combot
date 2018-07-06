# Running Combot
#To dev the script
docker run -it --rm --name my-running-script -v <git-repo-root>/combot-plugin:/combot-plugin -w /combot-plugin python:3 combot tekkenbot.py


#To make
sudo docker build . -t combot