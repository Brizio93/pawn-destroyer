<head>
   <style>
      .grid-container {
      display: grid;
      grid-template-columns: auto auto auto auto auto auto auto auto;
      background-color: #000;
      padding: 10px;
      }
      .grid-item {
      background-color: rgba(255, 255, 255, 0.8);
      border: 1px solid rgba(0, 0, 0, 0.8);
      font-size: 30px;
      text-align: center;
      }
   </style>
</head>
<body>
   <p id=info></p>
   <img id="handCard1" width="70" height="70">
   <img id="handCard2" src="assets/empty-attack.jpg" width="70" height="70">
   <img id="handCard3" src="assets/empty-attack.jpg" width="70" height="70">
   <div class="grid-container">
      <div class="grid-item">
         <button type="button" onclick="put(2,2)">
         <img id="r2c2" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(2,3)">
         <img id="r2c3" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(2,4)">
         <img id="r2c4" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(2,5)">
         <img id="r2c5" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(2,6)">
         <img id="r2c6" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(2,7)">
         <img id="r2c7" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(2,8)">
         <img id="r2c8" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(2,9)">
         <img id="r2c9" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(3,2)">
         <img id="r3c2" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(3,3)">
         <img id="r3c3" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(3,4)">
         <img id="r3c4" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(3,5)">
         <img id="r3c5" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(3,6)">
         <img id="r3c6" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(3,7)">
         <img id="r3c7" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(3,8)">
         <img id="r3c8" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(3,9)">
         <img id="r3c9" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(4,2)">
         <img id="r4c2" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(4,3)">
         <img id="r4c3" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(4,4)">
         <img id="r4c4" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(4,5)">
         <img id="r4c5" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(4,6)">
         <img id="r4c6" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(4,7)">
         <img id="r4c7" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(4,8)">
         <img id="r4c8" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(4,9)">
         <img id="r4c9" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(5,2)">
         <img id="r5c2" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(5,3)">
         <img id="r5c3" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(5,4)">
         <img id="r5c4" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(5,5)">
         <img id="r5c5" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(5,6)">
         <img id="r5c6" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(5,7)">
         <img id="r5c7" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(5,8)">
         <img id="r5c8" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(5,9)">
         <img id="r5c9" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(6,2)">
         <img id="r6c2" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(6,3)">
         <img id="r6c3" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(6,4)">
         <img id="r6c4" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(6,5)">
         <img id="r6c5" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(6,6)">
         <img id="r6c6" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(6,7)">
         <img id="r6c7" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(6,8)">
         <img id="r6c8" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(6,9)">
         <img id="r6c9" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(7,2)">
         <img id="r7c2" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(7,3)">
         <img id="r7c3" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(7,4)">
         <img id="r7c4" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(7,5)">
         <img id="r7c5" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(7,6)">
         <img id="r7c6" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(7,7)">
         <img id="r7c7" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(7,8)">
         <img id="r7c8" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(7,9)">
         <img id="r7c9" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(8,2)">
         <img id="r8c2" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(8,3)">
         <img id="r8c3" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(8,4)">
         <img id="r8c4" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(8,5)">
         <img id="r8c5" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(8,6)">
         <img id="r8c6" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(8,7)">
         <img id="r8c7" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(8,8)">
         <img id="r8c8" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(8,9)">
         <img id="r8c9" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(9,2)">
         <img id="r9c2" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(9,3)">
         <img id="r9c3" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(9,4)">
         <img id="r9c4" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(9,5)">
         <img id="r9c5" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(9,6)">
         <img id="r9c6" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(9,7)">
         <img id="r9c7" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(9,8)">
         <img id="r9c8" src="assets/empty-pawn.jpg">
         </button>
      </div>
      <div class="grid-item">
         <button type="button" onclick="put(9,9)">
         <img id="r9c9" src="assets/empty-pawn.jpg">
         </button>
      </div>
   </div>
   <script>
      var waitFlag = false;
      var points = 0;
      document.getElementById("info").innerHTML = "Carte rimanenti: 30 - Punteggio: 0";
      var deck = [
        "big-circolar-attack","big-circolar-attack","big-circolar-attack","big-circolar-attack","big-circolar-attack","big-circolar-attack",
        "circolar-attack","circolar-attack","circolar-attack","circolar-attack","circolar-attack","circolar-attack",
        "horizontal-attack","horizontal-attack","horizontal-attack","horizontal-attack","horizontal-attack","horizontal-attack",
        "vertical-attack","vertical-attack","vertical-attack","vertical-attack","vertical-attack","vertical-attack",
        "cross-attack","cross-attack","cross-attack","cross-attack","cross-attack","cross-attack"
      ]
      deck = shuffle(deck);
      var currentCard = deck.pop();
      document.getElementById("handCard1").src = "assets/" + currentCard + ".jpg";
      var freeBoxes = [
        [2,2],[2,3],[2,4],[2,5],[2,6],[2,7],[2,8],[2,9],[3,2],[3,3],[3,4],[3,5],[3,6],[3,7],[3,8],[3,9],
        [4,2],[4,3],[4,4],[4,5],[4,6],[4,7],[4,8],[4,9],[5,2],[5,3],[5,4],[5,5],[5,6],[5,7],[5,8],[5,9],
        [6,2],[6,3],[6,4],[6,5],[6,6],[6,7],[6,8],[6,9],[7,2],[7,3],[7,4],[7,5],[7,6],[7,7],[7,8],[7,9],
        [8,2],[8,3],[8,4],[8,5],[8,6],[8,7],[8,8],[8,9],[9,2],[9,3],[9,4],[9,5],[9,6],[9,7],[9,8],[9,9]
      ];
      freeBoxes = shuffle(freeBoxes);
      var grid = [
      ["sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel"],
      ["sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel"],
      ["sentinel","sentinel","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","sentinel","sentinel"],
      ["sentinel","sentinel","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","sentinel","sentinel"],
      ["sentinel","sentinel","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","sentinel","sentinel"],
      ["sentinel","sentinel","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","sentinel","sentinel"],
      ["sentinel","sentinel","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","sentinel","sentinel"],
      ["sentinel","sentinel","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","sentinel","sentinel"],
      ["sentinel","sentinel","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","sentinel","sentinel"],
      ["sentinel","sentinel","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","sentinel","sentinel"],
      ["sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel"],
      ["sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel"],
      ];
      enemySpawn();
      async function put(row, column) {
        if(grid[row][column]=="empty-pawn" && waitFlag==false) {
          waitFlag = true;
          grid[row][column] = "red-pawn";
          markBox(row, column);
          document.getElementById("r"+row+"c"+column).src = "assets/red-pawn.jpg";
          useAttack(row, column);
          await new Promise(r => setTimeout(r, 500));
          extinguishFlames();
          if(deck.length==0) {
            document.getElementById("info").innerHTML = "Fine del gioco. Punteggio totale: " + points;
            document.getElementById("handCard1").src = "assets/empty-attack.jpg";
          }
          else {
            enemySpawn();
            currentCard = deck.pop();
            document.getElementById("info").innerHTML = "Carte rimanenti: " + deck.length + " - Punteggio: " + points;
            document.getElementById("handCard1").src = "assets/" + currentCard + ".jpg";
            waitFlag = false;
          }
        }
      }
      function useAttack(row, column) {
        if(currentCard=="circolar-attack") {
          circolarAttack(row, column, 1);
        }
        if(currentCard=="big-circolar-attack") {
          circolarAttack(row, column, 2);
        }
        if(currentCard=="horizontal-attack") {
          horizontalAttack(row, column);
        }
        if(currentCard=="vertical-attack") {
          verticalAttack(row, column);
        }
        if(currentCard=="cross-attack") {
          horizontalAttack(row, column);
          verticalAttack(row, column);
        }
      }
      function circolarAttack(row, column, radius) {
        for(var i=row-radius; i<=row+radius; i++) {
          for(var j=column-radius; j<=column+radius; j++) {
            if(!(i==row && j==column) && grid[i][j]!="sentinel") {
              destroyPawn(i,j);
            }
          }
        }
      }
      function verticalAttack(row, column) {
        for(var j=2; j<=9; j++) {
          if(j!=column){
            destroyPawn(row,j);
          }
        }
      }
      function horizontalAttack(row, column) {
        for(var i=2; i<=9; i++) {
          if(i!=row){
            destroyPawn(i,column);
          }
        }
      }
      function destroyPawn(row, column) {
        if(grid[row][column]=="dark-pawn") {
          unmarkBox(row,column);
          points++;
        }
        if(grid[row][column]=="red-pawn") {
          unmarkBox(row,column);
          points--;
        }
        grid[row][column]="fire-pawn";
        document.getElementById("r"+row+"c"+column).src = "assets/fire-pawn.jpg";
      }
      function extinguishFlames() {
        for(var i=2; i<=9; i++) {
          for(var j=2; j<=9; j++) {
            if(grid[i][j]=="fire-pawn"){
              grid[i][j] = "empty-pawn";
              document.getElementById("r"+i+"c"+j).src = "assets/empty-pawn.jpg";
            }
          }
        }
      }
      function enemySpawn() {  //generate up to 3 new enemies in random positions
        var target;
        var row;
        var column;
        for(var i=0; i<3; i++) {
          target = freeBoxes.pop();
          row = target[0];
          column = target[1];
          grid[row][column] = "dark-pawn";
          document.getElementById("r"+row+"c"+column).src = "assets/dark-pawn.jpg";
        }
      }
      function markBox(row, column){
        for(var i=0; i<freeBoxes.length; i++) {
          if(freeBoxes[i][0]==row && freeBoxes[i][1]==column) {
            freeBoxes.splice(i, 1);
          }
        }
      }
      function unmarkBox(row, column){
        freeBoxes.push([row,column]);
        freeBoxes = shuffle(freeBoxes);
      }
      function getRandomInt(min, max) {
        min = Math.ceil(min);
        max = Math.floor(max);
        return Math.floor(Math.random() * (max - min + 1)) + min;
      }
      function shuffle(array) {
        var currentIndex = array.length, temporaryValue, randomIndex;
        while (0 !== currentIndex) {
          randomIndex = Math.floor(Math.random() * currentIndex);
          currentIndex -= 1;
          temporaryValue = array[currentIndex];
          array[currentIndex] = array[randomIndex];
          array[randomIndex] = temporaryValue;
        }
        return array;
      }
   </script>
</body>
