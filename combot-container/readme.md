# Running Combot
*To build*
```sudo docker build . -t combot-container```

*To dev the script from git repo home*
```docker run -it --rm --name my-running-script -v "$PWD/combot-plugin":/combot-plugin -w /combot-plugin combot-container python tekkenbot.py```