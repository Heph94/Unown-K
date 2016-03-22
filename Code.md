//Unown Code

size(300,300);
background(255);

//Top Limb
  strokeWeight(2);
  stroke(0);
  fill(50);
  rect(130,70,20,50,10);
  
//Bottom Limb
  stroke(0);
  fill(50);
  rect(130,180,20,50,10);
  
//Top Right limb
  stroke(0);
  fill(50);
translate(width/2, height/2);
rotate(radians(50));
rect(10, -80, 20, 60,10);


//Bottom Right limb
  stroke(0);
  fill(50);
rotate(radians(90));
rect(-30, -80, 20, 60,10);

//Body
translate(width/2, height/2);
rotate(radians(-140));

fill(50);
ellipse (200,20,100,100);
fill(255);
ellipse (200,20,60,60);
noStroke();
fill(0);
ellipse (200,20,25,25);
fill(255);
ellipse (197,17,8,8);


//Details
noStroke();
fill(50);

translate(width/2, height/2);
rotate(radians(50));
ellipse(-40,-155,25,25);
ellipse(-27,-90,12,12);
ellipse(-105,-155,12,12);
