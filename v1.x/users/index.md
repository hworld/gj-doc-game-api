# Users

Your games will not authenticate users by using their username and password. Instead, users have a
token to verify themselves along with their username.

Passing in the username and token can sometimes interrupt the flow of your game, so Game Jolt makes
the effort to automatically pass your game the username and token whenever possible.

* Java Applets are automatically passed the the username and token in Applet Parameters.
* Flash games are automatically passed the username and token in flashvars.
* It works similarly with Unity Webplayer and Silverlight games.
* Downloadable games running through the Game Jolt Client are passed the username and token in an automatically generated file: `.gj-credentials`, placed next to the game's executable.
	Definitely check that out!

## URL Endpoint

```
/users/
```

## Requests

| Name                                                       | Description                           |
| ---------------------------------------------------------- | ------------------------------------- |
| [**Auth**](https://gamejolt.com/game-api/doc/users/auth)   | Verfies a username-token combination. |
| [**Fetch**](https://gamejolt.com/game-api/doc/users/fetch) | Fetches user information.             |

## Example Uses

* Display users' profiles in your game.
* Let the user log in and use other services with their username-token combination.

## Remarks

* Usernames only contain alphanumeric characters, hyphens, and underscores.

## Version history

| Version | Description          |
| ------- | -------------------- |
| 1.0     | First implementation |
