<h1>Candy Crush Duplicate</h1>
I am trying to create a 3-match game like Candy Crush, currently the basic functions are done.

Demo GIF
--------
![alt tag](https://github.com/weiqing/3-match-pixijs/blob/master/3-match.gif)

Setup
-----
```bash
$ git clone https://github.com/weiqing/3-match-pixijs.git
$ cd 3-match-pixijs
$ python -m SimpleHTTPServer 8000
```

Then go to latest <b>Chrome</b> browser and open <a>http://localhost:8000/3match.html</a>

Functions
---------
You can use the develop tool by Chrome to call the following functions
```javascript
level.removeSpecificCandy(color)
```
Removes all the candies with certain color(num).

```javascript
level.removeRow(row)
```
Removes a certain row(num).

```javascript
level.removeColumn(column)
```
Removes a certain column(num).

```javascript
var candy = level.candies[x];
level.removeSurroundCandies(candy);
```
Removes a 3x3 candies around input candy.

Progress
--------
Currently finished features:<br/>
`Render sprites on the screen.`<br/>
`User can swap tiles (Improve animation later).`<br/>
`Generate tiles (will not connect more than 3 tiles on a row/col).`<br/>
`Remove matched candies.`<br/>
`Added two sound effects.`<br/>
`Special candies in progress.`<br/>


Tutorial
--------
Referred to the iOS tutorial 
<a>http://www.raywenderlich.com/75270/make-game-like-candy-crush-with-swift-tutorial-part-1</a>


