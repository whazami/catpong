# CatPong

## Overview

This repository represents the implementation of ft_transcendence, a project developed as part of the curriculum at 42 Paris. The aim of this project is to create a web-based version of the game "Pong" that enables users to play against each other and interact in a variety of ways.

The code is not provided as it's the rule of 42Seoul.

You can access the website [here](https://cat-pong.com).

<div align="center">
  <video src="https://github.com/whazami/catpong/assets/44798789/90264a2e-1708-4aa4-a49d-18f8dcd66ee6">
  Your browser does not support videos but you can watch the CatPong's Demo <a href="https://dl.dropboxusercontent.com/scl/fi/hqb4n7u13gp8scrpk2c5r/CatPongDemo.mp4?rlkey=skj7ahit0n518807r1zev9r8o&dl=0">here</a>.
  </video>
</div>

If the video above does not load, click [here](https://dl.dropboxusercontent.com/scl/fi/hqb4n7u13gp8scrpk2c5r/CatPongDemo.mp4?rlkey=skj7ahit0n518807r1zev9r8o&dl=0).

## Features

* Real-time multiplayer gameplay with WebSocket communication
* Ability to rejoin the current game if connection lost or when navigating to another page
* User account creation and authentication system (including 2FA)
* Player ranking and leaderboard
* Real-time users' status, allowing observation of their game if they are currently playing or challenging them if they are available
* User profiles with statistics, achievements, game theme and history
* Manage friendships and blocked users
* Chat functionality (including DMs and Channels) for users to communicate
* Channels types: public, protected (join by password), private (join by invitation)
* Channels roles: owner (can sanction and manage roles), admin (can sanction), member
* Channels sanctions: mute, kick, ban
* Responsive and user-friendly interface design

## Screenshots

<div align="center">
  <img src="screenshots/tfa.png" width="48%" />
  <img src="screenshots/other-profile.png" width="48%" /> 
</div>
<br>
<div align="center">
  <img src="screenshots/challenge.png" width="48%" />
  <img src="screenshots/end-of-game.png" width="48%" /> 
</div>
<br>
<div align="center">
  <img src="screenshots/catpong-team.png" width="48%" />
  <img src="screenshots/create-channel.png" width="48%" /> 
</div>

## Documentation

Note that you can test the endpoints of the API [here](https://api.cat-pong.com) which will directly affect the [deployed](https://cat-pong.com) version. For more information on interacting with the API, please refer to the [endpoint.md](endpoint.md) and [socket.md](socket.md) files.

## Troubleshooting

Note that the client secret for the 42 API changes on a monthly basis. If the .env file in the deployed version of the project is not updated to reflect this, the 'Login with 42' feature may not work.
