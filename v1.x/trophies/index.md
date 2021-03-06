# Trophies

Game Jolt allows you to add trophies to your games!

Trophies come in four materials: bronze, silver, gold, and platinum. This is to reflect how
difficult it is to achieve a trophy. A bronze trophy should be easy to achieve, whereas a platinum
trophy should be very hard to achieve.

On Game Jolt, trophies are always listed in order from easiest to most difficult to achieve.

You can also tag trophies on the site as "secret". A sercet trophy's image and description is not
visible until a gamer has achieved it.

## URL Endpoint

```
/trophies/
```

## Requests

| Name                                                                              | Description                                         |
| --------------------------------------------------------------------------------- | --------------------------------------------------- |
| [**Fetch**](https://gamejolt.com/game-api/doc/trophies/fetch)                     | Fetches trophies with various attributes.           |
| [**Add Achieved**](https://gamejolt.com/game-api/doc/trophies/add-achieved)       | Add a trophy to a user's list of achieved trophies. |
| [**Remove Achieved**](https://gamejolt.com/game-api/doc/trophies/remove-achieved) | Removes an achieved trophy.                         |

## Remarks

* You can manage trophies for your game from your game's dashboard.

## Version history

| Version | Description                          |
| ------- | ------------------------------------ |
| 1.2     | Added the `Remove Achieved` endpoint |
| 1.0     | First implementation                 |
