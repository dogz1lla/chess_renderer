![example](imgs/example.png)

# Description
Chess state rendering in browser using paper.js.

# To run
* run `npm install paper` inside of the directory
* run `./run_server.sh` to start a simple python http server (otherwise JS will refuse to load the
imgs)
* go to `http://localhost:8000/index.html` in the browser

# TODO
- [x] render the board
- [x] add piece svgs
- [x] render the initial configuration
- [x] create a text element that shows absolute mouse position (dynamic)
- [x] create a text element that shows in-board-coordinates mouse (dynamic)
- [x] refactor the Piece class and logic to include the board idx inside the instance
- [ ] write the logic to calc the diff between the current pieces array and the one from server fen
- [ ] implement piece capture
