## FlappyBird is LIVE!

FlappyBird is an animated mathematically coded game. Built on JAVA, this game addicts it's user to keep on scoring as the levels increase with time and concentration.

This game however is not designed properly but is made to run by visualising shapes and colors.
The code is explaned below.

# Packages and libraries used:



```markdown
import java.awt.Color;
import java.awt.Graphics;
import java.awt.event.ActionEvent;
import java.awt.event.ActionListener;
import java.awt.event.KeyEvent;
import java.awt.event.KeyListener;
import java.awt.event.MouseEvent;
import java.awt.event.MouseListener;
import javax.swing.JFrame;
import javax.swing.JPanel;
import javax.swing.Timer;
import java.awt.Dimension;
import java.awt.Font;
import java.util.Random;
```
# Building the UI

```markdown
 g.setColor(Color.RED);
        g.fillOval(locX,locY,WIDTH,HEIGHT);
        g.setColor(Color.GREEN);
        g.fillRect(0,4,1300,20);
        g.setColor(Color.GREEN);
        g.fillRect(0,710,1300,20);
        g.setColor(Color.BLUE);
        g.fillRect(rX,rY,40,40);
        g.setColor(Color.BLUE);
        g.fillRect(rX1,rY1,40,40);
        g.setColor(Color.BLUE);
        g.fillRect(rX2,rY2,40,40);
        g.setColor(Color.GREEN);
        
 ```
# Checking states and levels


```markdown
public void changeStateUp(int pointerX){
        if(pointerX==1)velY=(-1)*speedY;
        if(pointerX==2)velY1=(-1)*speedY1;
        if(pointerX==3)velY2=(-1)*speedY2;}
    public void changeStateDown(int pointerY){
        if(pointerY==1)velY=speedY;
        if(pointerY==2)velY1=speedY1;
        if(pointerY==3)velY2=speedY2;}

 ```



