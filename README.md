<a name="readme-top"></a>

<br />
<div align="center">
  <h1 align="center">:robot: @MAJORLASOR Discord Chat Bot</h1>

  <p align="center">
    <h3>A bot on Discord that responds back.</h3>
    <br />
    <a href="https://github.com/jamesrosal/mjrlsr_discord_bot"><strong>Check out the docs »</strong></a>
    <br />
    <br />
    <a href="#about-the-project">View Preview</a>
    ·
    <a href="https://github.com/jamesrosal/mjrlsr_discord_bot/issues">Report Bug</a>
    ·
    <a href="https://github.com/jamesrosal/mjrlsr_discord_bot/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

A bot on Discord that responds back. Built with Python and Discord's API.

![Discord Bot Example](https://github.com/jamesrosal/mjrlsr_discord_bot/blob/main/public/discord-bot-example.png?raw=true)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- BUILT WITH -->
### Built With

* <img align="left" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="16" /> Python
* <img align="left" src="https://assets-global.website-files.com/6257adef93867e50d84d30e2/636e0a6a49cf127bf92de1e2_icon_clyde_blurple_RGB.png" height="16" /> Discord

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

### Prerequisites
1. Update to Python 3: https://www.python.org/downloads/
2. Join Discord Developers and log in: https://discord.com/developers/applications
3. Click New Application to name and create an application
4. In the navigation, click OAuth2 > General, select the Authorization Method: In-app Authorization, and check off bot and these boxes in the image below:
![OAuth > General - Checkboxes](https://github.com/jamesrosal/mjrlsr_discord_bot/blob/main/public/discord-bot-oauth-general.png?raw=true)
5. Upon creation of a new application, you should have a Token. If not, in the navigation, click Bot, then Reset Token, and copy this token for the next steps

### Installation 
Get the Repository
* In your terminal:
```
cd ~/Desktop
```
* Clone the repo:
```
git clone https://github.com/jamesrosal/mjrlsr_discord_bot.git
```

Running the bot <br>
** I recommend using an IDE (PyCharm or VS Code) to run the scripts in the next steps
1. Use the copied token from the previous steps in the bot.py file, and replace INSERT_TOKEN with your copied token.
2. In your IDE, open main.py and click Run
3. Go to discord.com/developers/applications, and go to your application
4. In the navigation, click OAuth2 > URL Generator, and check off these boxes:
![OAuth > URL 1](https://github.com/jamesrosal/mjrlsr_discord_bot/blob/main/public/discord-bot-oauth-url-1.png?raw=true)
![OAuth > URL 2](https://github.com/jamesrosal/mjrlsr_discord_bot/blob/main/public/discord-bot-oauth-url-2.png?raw=true)
5. Copy the URL below the checkboxes, paste it into your browser, and follow the next few prompts
6. **You should now be able to talk with the bot!**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage
In jr-bot.json, you can add responses based on the user input, using this format:
```
{
    "response_type": "greeting",
    "user_input": ["hello", "hi", "hey", "yo", "aye", "ay", "sup"],
    "bot_response": "sup?",
    "required_words": []
  },
```

![jr-bot.json](https://github.com/jamesrosal/mjrlsr_discord_bot/blob/main/public/discord-bot-json.png?raw=true)

** If a response has a “required_words”, then the specific bot response will go off. For example, if you put “yo” in the “required_words”, then no matter what the bot response will be sup. So something like “yo mama” will include the required word.

In random_responses.py file, you can add random responses. This will output a random response only when the bot doesn’t understand what you are saying.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [x] Connecting Discord API
- [x] Adding Custom Natural Language
- [ ] Adding an LLM Library for more automated conversation

See the [open issues](https://github.com/jamesrosal/mjrlsr_discord_bot/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

James Rosal - [jamesrosal.com](https://jamesrosal.com) - jamesfrosal@gmail.com - [linkedin](https://www.linkedin.com/in/jamesrosal/)

Project Link: [https://github.com/jamesrosal/mjrlsr_discord_bot](https://github.com/jamesrosal/mjrlsr_discord_bot)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
