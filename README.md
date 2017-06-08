# Karel Problem 1
Assignment
import stanford.karel*;
public class PickUpNewspaperKarel extends SuperKarel{
  public void run(){
    move();
    move();
    turnRight();
    move();
    turnLeft();
    move();
    pickBeeper();
    turnAround();
    move();
    move();
    move();
    turnRight();
    move();
   }
  /** 
    *Turns Karel 180degrees.
    */
    public void turnAround(){
      turnLeft();
      turnLeft();
    }
  /**
    *Turns Karel to the right.
    */
    public void turnRight(){
      turnLeft();
      turnLeft();
      turnLeft();
     }
    }
