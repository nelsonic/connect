#Anvil Connect

[![Join the chat at https://gitter.im/anvilresearch/connect](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/anvilresearch/connect?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) [![Slack](http://slackin.anvil.io/badge.svg)](http://slackin.anvil.io/)
 ![Dependencies](https://img.shields.io/david/anvilresearch/connect.svg) ![License](https://img.shields.io/github/license/anvilresearch/connect.svg) ![Downloads](https://img.shields.io/npm/dm/anvil-connect.svg) ![npm](https://img.shields.io/npm/v/anvil-connect.svg)

##What We're Doing 
### We're building a modern authorization server to authenticate your users and protect your APIs.

####You can find professional services and sponsor information on [our website](http://anvil.io).

#### Simplified Security
- Share user accounts between multiple apps and services with Single Sign-On (shared sessions)
- Issue signed JSON Web Tokens to protect your APIs
- Be a federated identity provider with OpenID Connect
- Enable third-party developers using two- and three-legged OAuth 2.0

#### Flexible User Authentication
- Use local passwords, OAuth 1.0, OAuth 2.0, OpenID, Active Directory, and more
- Works out of the box with Google, Facebook, Twitter, GitHub, and a [growing list of providers](https://github.com/christiansmith/anvil-connect/tree/master/providers)
- Custom schemes using virtually any existing Passport.js strategy or your own code

#### Make it yours
- Brand the interface with your own design
- Use middleware hooks for domain specific implementations
- Keep your changes under version control without forking

#### Standard, Interoperable, and Open Source
- Language and platform agnostic
- Implements widely accepted, well-understood protocols
- MIT license



##Get Started

#### Requirements

* Node.js
* npm
* Redis

#### Setup

```bash
# Install the CLI
$ npm install -g anvil-connect

# Make a place for your deployment repository to live
$ mkdir path/to/project
$ cd path/to/project

# Generate a deployment repository
$ nv init

# Install dependencies
$ npm install

# Initialize the local database
$ nv migrate

# Create the first user account
$ nv signup

# Assign a role
$ nv assign <email> authority

# Start the server in development mode
$ nv serve
```

You should now have an OpenID Connect Provider running in development mode.


## Development

We are a growing community of contributors of all kinds, join us!

#### Chat on Gitter or Slack

Come say hello on Gitter or Slack! We love talking shop with Anvil Connect users :)

[![Gitter](https://badges.gitter.im/anvilresearch/connect.svg)](https://gitter.im/anvilresearch/connect) [![Slack](http://slackin.anvil.io/badge.svg)](http://slackin.anvil.io/)
### Weekly Community Meetings

Every Thursday at 9AM PDT / 12PM EDT / 4PM GMT we get together to map out the future of the project, talk through specs, review code, and help each other ship. You're welcome to [join in](https://github.com/anvilresearch/connect/wiki/Weekly-Community-Hangouts-and-Meeting-Notes).

###Pair Programming
We often pair on more challening or new code, hop into Gitter or Slack and join us, or request your own session.

###Need more engagement?
Support and consulting also available, contact us via [the website](http://anvil.io) or by [email](mailto:contact@anvil.io)

## Documentation

* [Documentation](https://github.com/anvilresearch/connect-docs)
* [References](https://github.com/anvilresearch/connect/wiki/References)



## Status

- Used in production since July 2014
- Active development as of March 2015


## MIT License

Copyright (c) 2015 [Anvil Research, Inc.](http://anvil.io)

