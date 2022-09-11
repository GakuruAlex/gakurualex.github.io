# Battleship game

Battleship game is a web application that generates three ships and places them on a grid and then a player attempts to sink all the ships in the lowest number of guesses as possible.

## Installation

fork the repo and clone it.
run the server
```bash
npm install
cd into json-server-template
cd db
json-server --watch db.json

npm run dev
```
## Technologies
Project is created with:
* Html
* JavaScript
*json server
## Usage

```js
generateShipLocations()

# generates random locations for the ships


 isSunk(ship)
# Checks whether a ship is sunk by if and only if the number of hits for a ship are equal to 3


# makeRequest(url)
makes a get request and returns some resource --a joke or a value in the server


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.



## License
[MIT](https://choosealicense.com/licenses/mit/)