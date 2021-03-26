# Machine-Setup
Dotfiles, configurations, scripts and documentation regarding my personal machine setup

## PyCharmSettings
Documentation about my PyCharm configuration and some helpful tools I made. My complete settings are in the [PyCharmSettings repository](https://github.com/DavidTraina/PyCharmSettings), which is managed by the IDE.

### Black Format External Tool
This "external tool" lets you format your projects with [Black](https://black.readthedocs.io/en/stable/) by pressing `Ctrl + \`
- Install Black to your base [conda](https://docs.conda.io/en/latest/index.html) environment (or anywhere else you choose)
  ```bash
  conda activate base 
  pip install black
  whereis black | xclip -sel clip 
  ```
- Open the Black Format external tool and paste the path to the `black` executable into the `Program`
- Optionally remove the `-S` flag based and/or add other options to the command based on you needs
