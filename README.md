# Slack it
Copyright Fumitaka Nakamura, 2020

1. Prerequisites
Install following modules if you don't have some or all of them in your environment.
(e.g. just type `sudo pip3 install slack` for example).

- slack
- flask

2. Create app

Visit [https://api.slack.com/apps](https://api.slack.com/apps)  and create your app by clicking [Create New App] button.

App Name: The name of your app
Development Slack Workspace: Target Slack workspace

3. OAuth setting
Move to your app page and select 'OAuth & Permissions' in the left pane.
Fill `localhost:5000/finish_auth` in 'Redirect URLs' and [Add] it.
