# Mines
package  {
    import flash.display.Sprite;
    import flash.events.MouseEvent;
    public class minesweeper_game extends Sprite {
        public var zones:Array;
        public var board:Sprite;
        public var boardWidth:int;
        public var boardHeight:int;
        public var numberOfMines:int;
        public function Main() {            //constructor----
            zones = new Array();
            board = new Sprite();
            boardWidth = 15;
            boardHeight = 15;
            numberOfMines = 30;
        }   //end of constructor
    }   //end of class
}   //end of package
