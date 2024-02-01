# Teamworks Theme by Vincenzo Meschi

The Teamworks theme is a custom theme by Vincenzo Meschi, based on the Copenhagen theme. It is designed to be responsive and accessible.
Learn more about customizing Zendesk Guide [here](https://support.zendesk.com/hc/en-us/sections/206670747).

The Teamworks theme for Help Center consists of:
- [Manifest file](#manifest-file)
- [Set of templates](#templates)
- [Stylesheet and JavaScript files](#stylesheet-and-javascript)
- [Assets folder](#assets).

## Getting Started
Before you can use this theme, you need to set up your environment:

1. Install Ruby 2.6.9 on your machine.
2. Set up Ruby environment variables by adding these lines to your shell profile file (`.bashrc`, `.bash_profile`, or `.zshrc` depending on your system):
'''
export PATH="$HOME/.rbenv/bin:$PATH"
eval "$(rbenv init -)"
'''
3. Set Ruby 2.6.9 as your default version:
'''
rbenv global 2.6.9
'''
4. Install ZAT
https://developer.zendesk.com/documentation/apps/zendesk-app-tools-zat/installing-and-using-zat/

5. Run Zendesk theme preview:
'''
zat theme preview
'''

5. Enter the following when prompted:
- name of your Zendesk sub-domain
- username formatted as `{username}@teamworks.com/token`
- your API key

## How to use
This is the latest version of the Teamworks theme available for Guide. 
You can use your favorite IDE to develop themes and preview your changes locally in a web browser using [ZCLI](https://github.com/zendesk/zcli/). For details, read the [zcli themes](https://github.com/zendesk/zcli/blob/master/docs/themes.md) documentation.


