# Running Combot
#To dev the script
docker run -it --rm --name my-running-script -v <git-repo-root>/combot-plugin:/combotplugin -w /combotplugin combot-container combot tekkenbot.py


#To make
sudo docker build . -t combot-container