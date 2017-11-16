

# kult-lunchbot <img src="https://raw.githubusercontent.com/WtfJoke/kult-lunchbot/master/resources/icons/lunchbot_icon_fullbackground.png" width="40" height="40"> 

## Overview
This projects aims to scrape the [WTZ-Homepage](http://wtz-tagungszentrum.de) for current lunch menu.
Afterwards it shouts the scraped information (e.g the menu of today) to a slack channel

## Status
In development for personal usage. Currently the app its not hosted anyhwere and therefore cant be added to your slack channel.

## Requirement
This project needs python 3.6 uses [BeautifulSoup4](https://pypi.python.org/pypi/beautifulsoup4) for scraping website, 
[slack-client](https://github.com/slackapi/python-slackclient) for communicating with slack, [pdfminer.six](https://github.com/pdfminer/pdfminer.six) for pdf text extraction
and [flask](http://flask.pocoo.org/) for providing the [slack-events rest api](https://api.slack.com/events-api) interface.

To install requirements execute:

`pip install -r requirements.txt`



## Add to your slack channel
[![Add to Slack](https://platform.slack-edge.com/img/add_to_slack.png)](https://slack.com/oauth/authorize?scope=bot&client_id=269973088388.270476032388)

