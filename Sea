
var ship,ship_running;
var ground,groundImage
function preload(){
ship_running= loadAnimation("ship-1.png","ship-2.png","ship-3.png","ship-4.png");
groundImage= loadImage("sea.png");
}
function setup(){
createCanvas(400,400);



ground=createSprite(0,0,200,400);
ground.addImage("ground",groundImage);
ground.x = ground.width /2;
ground.velocityX = -4;




ship=createSprite(200,200,20,50);
ship.addAnimation("running",ship_running);
ship.scale=0.5

}

function draw() {
  if (ground.x < 0) {
    ground.x = ground.width / 2;
  }
  background("blue");
  drawSprites();
}