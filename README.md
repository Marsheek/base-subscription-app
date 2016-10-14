# README

This is a base subscription app configured that has had the devise controller and registration views
configured with stripe payments. In order to configure to the desired payment settings refer to https://stripe.com/docs/subscriptions/tutorial

##Design
The design is plain bootstrap and set up with a home page with two different signup buttons and some text.

##Installation
- git clone
- bundle
- rails db:migrate

##Challenges
The app has a subscription payment set up with devise when you register a user.
So in order for this to be achieved the devise controller was edited.  
Ran into issues setting environment variables as I'm using zsh and needed to access the .zshrc file not the .bashrc file to store the environment variables.
