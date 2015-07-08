int x =0;
int dx =1;

void setup()
{
  size(500,500);
}
void draw()
{
  background(0);
fill(x*2,x,x*2);
rectMode(CENTER);
rect(50,25,100,25);
rect(15,100,30,175);
rect(50,100,100,25);
rect(50,175,100,25);
triangle(110,12.5,140,12.5,170,187.5);
triangle(140,12.5,170,187.5,170,120);
triangle(170,187.5,170,120,200,12.5);
triangle(170,187.5,200,12.5,230,12.5);
rectMode(CENTER);
rect(290,25,100,25);
rect(255,100,30,175);
rect(290,100,100,25);
rect(290,175,100,25);
rect(375,100,30,175);
triangle(390,12.5,390,62.5,460,187.5);
triangle(460,187.5,460,137.5,390,12.5);
rect(475,100,30,175);
stroke (x*2,x,x*2);
if (x>100)
{
  dx=-dx;
}
if (x<0)
{
  dx=-dx;
}
x=x+dx;
}
