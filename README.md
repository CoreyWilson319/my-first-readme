# my-first-readme
Repo explaining README.md



~
## Steps to Install on local computer
1. Go to [repo](https://github.com/SEI-ATL/tic-tac-toe)
 on Github profile
2. `fork` and `clone` repo
3. Clone to local machine
```text
git clone https://github.com/SEI-ATL/tic-ta-toe.git
```
4. Go to `tic-tac-toe` directory
5. Open `index.html` in browser
```text
xdg-open index.html
```

```javascript
const handleWin = (letter) => {
  gameIsLive = false;
  if (letter === "x") {
    statusDiv.innerHTML = `${letterToSymbol(letter)} has won!`;
  } else {
    statusDiv.innerHTML = `<span>${letterToSymbol(letter)} has won!</span>`;
  }
};
```

```css
.grid {
    background-color: salmon;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(3, 1fr);
    gap: 15px;
    margin-top: 50px;
}
```

```html
<div class="grid">
    <div class="box" id="box-1"></div>
    <div class="box" id="box-2"></div>
    <div class="box" id="box-3"></div>
    <div class="box" id="box-4"></div>
    <div class="box" id="box-5"></div>
    <div class="box" id="box-6"></div>
    <div class="box" id="box-7"></div>
    <div class="box" id="box-8"></div>
    <div class="box" id="box-9"></div>
</div>

```

| Functions | Description |
| ------------ | ------------ |
| `handleWin()` | Handle the win of either player |
| `checkGameStatus()` | Check the status after each turn |

#Variables
|Variables|Value|
|---|---|
|windCondX(1-8)| Holds an array for each box that must have a character in order to win|
|windCondO(1-8)| Holds an array for each box that must have a character in order to win|
|clearButton| Holds the button from the html as the variable|


pickup on line 178
|Functions|Act|
|---|---|
|checkXWin| Checks if the boxes have a value of true and if 3 are true that would win an alert should say who won|
|checkOWin| Checks if the boxes have a value of true and if 3 are true that would win an alert should say who won|
|click|Every time a box is clicked the players will switch off and win conditions are checked to see if there is a winner|
|clear|When clear button is clicked all boxes are set to a blank string
|setO|Is what is used to play an O|
|setX|Is what is used to place an X|
|clickForWin|Displays a message if there has been a winner|