# NHL API

This is a fork of the specification at https://github.com/erunion/sport-api-specifications/tree/master/nhl. If this is being actively maintained somewhere else, please let me know.

This provides an [OpenAPI 3.0](https://swagger.io/docs/specification/about/) specification file for the NHL API.

The bulk of this API has been discovered through [@dword4](https://github.com/dword4) and their [nhlapi](https://github.com/dword4/nhlapi) documentation.

## Copyright

> NHL and the NHL Shield are registered trademarks of the National Hockey League. NHL and NHL team marks are the property of the NHL and its teams. © NHL 2018. All Rights Reserved.

## Available endpoints

| Endpoint | Description |
| :--- | :--- |
| `/conferences` | Get all current NHL conferences. |
| `/conferences/{id}` | Get an NHL conference. |
| `/divisions` | Get all current NHL divisions. |
| `/divisions/{id}` | Get an NHL division. |
| `/draft` | Get round-by-round data for current year's NHL Entry Draft. |
| `/draft/{year}` | Get round-by-round data for a specific year's NHL Entry Draft. |
| `/draft/prospects` | Get all NHL Entry Draft prospects. |
| `/draft/prospects/{id}` | Get an NHL Entry Draft prospect. |
| `/franchises` | Get a list of franchises |
| `/franchises/{id}` | Get a specific franchise |
| `/game/{id}/boxscore` | Get the boxscore for an NHL game. |
| `/game/{id}/content` | Get editorials, video replays and photo highlights for an NHL game. |
| `/game/{id}/feed/live` | Get all available data for an NHL game. |
| `/game/{id}/feed/live/diffPatch` | Get all available data for an NHL game after a specific time. |
| `/gameStatus` | Returns a list of game status values |
| `/gameTypes` | Get the possible values of the game type enum. |
| `/people/{id}` | Get an NHL player. |
| `/people/{id}/stats` | Get specific statistics for an NHL player. |
| `/playTypes` | Get play type schemas |
| `/schedule` | Get the NHL game schedule. |
| `/seasons` | Get the NHL seasons |
| `/standings` | Get NHL division standings. |
| `/standings/{type}` | Get NHL standings for a specific standing type. |
| `/standingsTypes` | Get all available NHL standing types. |
| `/statTypes` | Get all available NHL statistic types. |
| `/teams` | Get all NHL teams. |
| `/teams/{id}` | Get an NHL team. |
| `/teams/{id}/roster` | Get an NHL team's roster. |
| `/teams/{id}/stats` | Get all statistics for an NHL team. |
