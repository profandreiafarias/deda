let xBolinha = 300;
let yBolinha = 200;
let diametro = 15;
let raio = diametro / 2;
let velocidadeXBolinha = 5;
let velocidadeYBolinha =5;
let xRaquete = 5;
let yRaquete = 150;
let xRaqueteOponente = 585;
let yRaqueteOponente = 150;
let raqueteLargura = 10;
let raqueteAltura =90
let colidiu = false;
let velocidadeYOponente;
let meusPontos = 0;
let pontosOponente = 0;
let ponto;
let trilha;
let raquetada;

function preload(){
  trilha = loadSound("trilha.mp3");
  ponto = loadSound("ponto.mp3");
  raquetada = loadSound("raquetada.mp3");
}

function setup() {
  createCanvas(600, 400);
  trilha.loop();
}

function draw() {
  background(0);
  mostraBolinha();
  mostraMinhaRaquete(xRaquete,yRaquete);
  mostraRaqueteOpnonente(xRaqueteOponente,yRaqueteOponente);
  movimentaBolinha();
  movimentaMinhaRaquete();
  movimentaRaqueteOponente();
  verificaColisaoBorda();
  verificaColisaoRaquete(xRaquete,yRaquete); 
  verificaColisaoRaquete(xRaqueteOponente, yRaqueteOponente);
  incluirPlacar();
  marcaPonto();
 }
  function mostraBolinha(){
    fill("red");
    circle(xBolinha,yBolinha,diametro);
  }
    
  function mostraMinhaRaquete(x,y){
    fill("green");
    rect(x,y,raqueteLargura,raqueteAltura);          
  }
  function mostraRaqueteOpnonente(x,y){
    rect(x, y, raqueteLargura, raqueteAltura);
  }
  function movimentaBolinha(){
  xBolinha += velocidadeXBolinha;
  yBolinha += velocidadeYBolinha;
    
  }
  function verificaColisaoBorda(){
     if (xBolinha + raio > width || xBolinha < 0) {
    velocidadeXBolinha *= - 1;       
  }  
    if (yBolinha + raio > height || yBolinha < 0){
    velocidadeYBolinha *= - 1;     
     }
  }
  function movimentaMinhaRaquete(){
    if(keyIsDown(87)){
     yRaquete -= 10;
    }
    
     if(keyIsDown(83)){
     yRaquete += 10;
  }
  }    
function movimentaRaqueteOponente(){
  if(keyIsDown(UP_ARROW)){
     yRaqueteOponente -= 10;
    }
  
  if(keyIsDown(DOWN_ARROW)){
     yRaqueteOponente += 10;
 }
 } 

function verificaColisaoRaquete(x,y){
  colidiu = collideRectCircle(x,y, raqueteLargura, raqueteAltura, xBolinha, yBolinha,raio);
  if(colidiu){
    velocidadeXBolinha *= -1;
    raquetada.play();
  }
}
 function incluirPlacar(){
   stroke("red");
   textAlign(CENTER);
   textSize(16);
   fill("white");
   
   //placar meusPontos
   fill("orange");
   rect(135,10,35,20);
   fill(255);
   text(meusPontos,150,26);
   
   //placar pontosOponente
   fill("orange");
   rect(430,10,35,20);
   fill(255);
   text(pontosOponente,450,26);
 }
function marcaPonto(){
 if (xBolinha > 590){
   meusPontos += 01;
   ponto.play();
 } 
  if(xBolinha < 10){
    pontosOponente += 01;
    ponto.play();
  }
}
