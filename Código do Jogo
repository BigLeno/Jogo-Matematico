Atividade Final da U3 de LOP - Orivaldo Santana - UFRN

Matematic Trick 
Baseado na linguagem javascript
feito no p5.js

// Determinação das primeiras variáveis e/ou valores que se repetem no decorrer da programação

var tela = 1;
var largura = 200;
var altura = 50; 
var xMenu = 50;
var yMenu1 = 85;
var yMenu2 = 145;
var yMenu3 = 205;
var larguraJogo = 50;
var alturaJogo = 30;
var xJogo = 100;
var yJogo1 = 115;
var yJogo2 = 145;
var yJogo3 = 175;
var yJogo4 = 205;
var yJogo5 = 235;



function setup() {
    createCanvas(300, 300);
}
function draw() {
  textStyle(BOLDITALIC)
    // Tela de Menu
    if (tela == 1){
      background(220);
      textAlign(CENTER);
      textSize(26);
      // Menu com três opções
      // Iniciar o Jogo
      // botão 1
      if ( mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu1 && mouseY < yMenu1 + altura ) {
        stroke(20);
        fill(200);
        rect(xMenu, yMenu1, largura, altura, 15);  
      }
      
      fill(20);
      noStroke();
      text("Iniciar", 150, 120);
      
      // Tutorial
      // botão 2
      if ( mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu2 && mouseY < yMenu2 + altura ) {
        stroke(20);
        fill(200);
        rect(xMenu, yMenu2, largura, altura, 15);
      }
      
      fill(20);
      noStroke();
      text("Tutorial", 150, 180);
      
      fill(20);
      noStroke();
      text("Matematic trick", 150, 60);
      
      // Informações do Jogo
      // botão 3
      if ( mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu3 && mouseY < yMenu3 + altura ) {
        stroke(20);
        fill(200);
        rect(xMenu, yMenu3, largura, altura, 15);
        if (mouseIsPressed){ tela = 4 }  
      }
      fill(20);
      noStroke();
      text("Informações", 150, 240);
      
    }
  
    // Jogo em Ação
    else if (tela == 2){
      background(220);
      
        //Pergunta #1
        textAlign(CENTER);
        textSize(14);
        text("Basendo-se em seus conhecimentos,", 150, 55);
        text("resolva o que se pede:", 150, 70);
        text("5 - (15 + 4) + 21 = ? ", 150, 105);
      
        //Alternativa #1
      //a
       if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo1 && mouseY < yJogo1 + alturaJogo){
        stroke(220);
        fill(200);
        rect(xJogo, yJogo1, larguraJogo, alturaJogo);
      }
        textSize(14);
        textAlign(CENTER);
        fill(0);
        noStroke();
        text("A) 25", 125, 135);
      
      //b
      if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo2 && mouseY < yJogo2 + alturaJogo){
        stroke(220);
        fill(200);
        rect(xJogo, yJogo2, larguraJogo, alturaJogo);
      }
        textSize(14);
        textAlign(CENTER);
        fill(0);
        noStroke();
        text("B) -7", 125, 165);
      
      //c
      if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo3 && mouseY < yJogo3 + alturaJogo){
        stroke(220);
        fill(200);
        rect(xJogo, yJogo3, larguraJogo, alturaJogo);
      }
        textSize(14);
        textAlign(CENTER);
        fill(0);
        noStroke();
        text("C) 15", 125, 195);
        
      //d
      if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo4 && mouseY < yJogo4 + alturaJogo){
        stroke(220);
        fill(200);
        rect(xJogo, yJogo4, larguraJogo, alturaJogo);
      }
        textSize(14);
        textAlign(CENTER);
        fill(0);
        noStroke();
        text("D) -21", 125, 225);
      
      //e
      if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo5 && mouseY < yJogo5 + alturaJogo){
        stroke(220);
        fill(200);
        rect(xJogo, yJogo5, larguraJogo, alturaJogo);
      }
        textSize(14);
        textAlign(CENTER);
        fill(0);
        noStroke();
        text("E) 7", 125, 255);
      
      // Desenvolvimento do botão de pausa
      
      if(mouseX > 9 && mouseX < 9 + 20 && mouseY > 7 && mouseY < 7 + 20){
        stroke(220);
        fill(200);
        rect(9, 7, 20, 20);
      }
      textSize(14);
      fill(0);
      noStroke();
      text("||", 15, 20);
      
    }
  
    // Tutorial
    else if(tela == 3){
      background(220);
      fill(20);
      textSize(15);
      noStroke();
      textAlign(LEFT);
      text("Cada Fase têm sua peculiaridade:", 20, 40, 260, 260);
      
      textSize(12);
      text("º A fase 1  gira  em torno  de  um  jogo  com   caráter matemático, baseando-se em operações simples de soma e subtração.", 40, 65, 260, 260);
      
      textSize(12);
      text("º A fase 2  gira  em  torno  de  um  jogo com caráter matemático, aumentando um pouco mais o nível das  operações  e  adicionando outras delas, como divisão e multiplicação. ", 40, 115, 260, 260);
      
      textSize(12);
      text("º A fase 3  gira  em  torno  de  um  jogo  com caráter matemático, aumentando mais ainda o nível das operações e adicionando  outras delas, como potenciação e radiciação. ", 40, 180, 260, 260);
      
      // Desenvolvimento do botão de saída da tela de Tutorial
      
      if(mouseX > 9 && mouseX < 9 + 20 && mouseY > 7 && mouseY < 7 + 20){
        stroke(20);
        fill(200);
        rect(10, 5, 20, 20);
      }
      
      fill(20);
      textSize(12);
      noStroke();
      text("X", 15, 20);
      
      // Enumerador de página
      fill(20);
      textSize(12);
      textAlign(CENTER);
      noStroke();
      text("página 1", 150, 280);
      
      // botão de mudança de página
      if(mouseX > 260 && mouseX < 260 + 20 && mouseY > 265 && mouseY < 265 + 20){
        stroke(20);
        fill(200);
        rect(260,265, 20, 20);
      }
      
      fill(20);
      noStroke();
      textSize(15);
      text(">", 270, 280);
      
  }
  
    // Informações
    else if(tela == 4) {
      background(220);
      fill(20);
      textSize(14);
      noStroke();
      textAlign(LEFT);
      text("      O Jogo está baseado   na   grande   dificuldade   da    maioria dos alunos brasileiros.   A    matemática,   quando   não   totalmente   compreendida   em suas bases teóricas (soma,subtração, divisão e multiplicação), tem seu desenvolvimento prejudicado à posteriori, pois os conceitos    dependem   uns dos outros indiretamente, tende a ser complicada e complexa demais para indivíduos que não lidem muito bem com números", 20, 40, 260, 260);
      
    // Desenvolvimento do botão de saída da tela de informações.
      
      if(mouseX > 9 && mouseX < 9 + 20 && mouseY > 7 && mouseY < 7 + 20){
        stroke(20);
        fill(200);
        rect(10, 5, 20, 20);
      }
      
      fill(20);
      textSize(12);
      noStroke();
      text("X", 15, 20);
      
      // Enumerador de página
      fill(20);
      textSize(12);
      textAlign(CENTER);
      noStroke();
      text("página 1", 150, 280);
      
      // botão de mudança de página
      if(mouseX > 260 && mouseX < 260 + 20 && mouseY > 265 && mouseY < 265 + 20){
        stroke(20);
        fill(200);
        rect(260,265, 20, 20);
      }
      
      fill(20);
      noStroke();
      textSize(15);
      text(">", 270, 280);

}     
  
    // Tela de Pausa 1
    else if(tela == 5){
      
      fill(240);
      textAlign(CENTER);
      textSize(26);
      
      // Botão que volta ao jogo
      
      if ( mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu1 && mouseY < yMenu1 + altura ) {
        stroke(20);
        fill(200);
        rect(xMenu, yMenu1, largura, altura, 15);
      }
      
      fill(20);
      noStroke();
      text("Voltar", 150, 120);
      
      // Botão que volta ao menu iniciar
      
      if (mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu2 && mouseY < yMenu2 + altura) {
        stroke(20);
        fill(200);
        rect(xMenu, yMenu2, largura, altura, 15);

      }
        
      fill(20);
      noStroke();
      text("Menu inicial", 150, 180);
      
    }
  
    // Tela de escolha da fase  
    else if (tela == 6){
    background(220);
    textSize(26);
    textAlign(CENTER);
    
    // botão da fase 1
    if ( mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu1 && mouseY < yMenu1 + altura ) {
        stroke(20);
        fill(200);
        rect(xMenu, yMenu1, largura, altura, 15);  
      }
    
    // botão da fase 2
     if ( mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu2 && mouseY < yMenu2 + altura ) {
        stroke(20);
        fill(200);
        rect(xMenu, yMenu2, largura, altura, 15);  
      }
  
    // botão da fase 3
     if ( mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu3 && mouseY < yMenu3 + altura ) {
        stroke(20);
        fill(200);
        rect(xMenu, yMenu3, largura, altura, 15);  
      }
    
    // botão de saída da tela de escolha de fases
    if(mouseX > 9 && mouseX < 9 + 20 && mouseY > 7 && mouseY < 7 + 20){
        stroke(20);
        fill(200);
        rect(10, 5, 20, 20);
        if(mouseIsPressed){ tela = 1}
      }
      
    
    
      fill(20);
      noStroke();
      textSize(12)
      text("X", 20, 20);
      
    
    
      fill(20);
      noStroke();
      textSize(22);
      text("Jogo 1", 150, 120);
    
    
    
      fill(20);
      noStroke();
      textSize(22);
      text("Jogo 2", 150, 180);
    
    
    
      fill(20);
      noStroke();
      textSize(22);
      text("Jogo 3", 150, 240);
    
      fill(20);
      noStroke();
      textSize(18);
      text("Escolha qual fase quer jogar:", 150, 60);
  
  
  }
  
    // Página 2 do Tutorial
    else if( tela == 7){
    background(220);
    textAlign(LEFT);
    textSize(12);
    noStroke();
    fill(20);
    text("    Em cada fase, o jogador terá de superar  uma   série    de   desafios  que  levam  em   conta  o nível da fase e o conteúdo nela contido.", 20, 40, 260, 260);
    text("    Desafios aleatórios e consecutivos,  de   maneira     que   o   jogador consiga possa   realmente   ser   desafiado a aprender algo   novo   ou,  simplesmente, relembrar algum conceito   que já havia, a muito, esquecido,   em   decorrência   do   não   uso  ou de sua simplicidade", 20, 100, 260, 260);
  
      // Botão de saída da tela 2 do tutorial
    if(mouseX > 9 && mouseX < 9 + 20 && mouseY > 7 && mouseY < 7 + 20){
        stroke(20);
        fill(200);
        rect(10, 5, 20, 20);
      }
      
      fill(20);
      textSize(12);
      noStroke();
      text("X", 15, 20);
    
      // Enumerador de página
      fill(20);
      textSize(12);
      textAlign(CENTER);
      noStroke();
      text("página 2", 150, 280);
    
      // Botão de mudança de página
       if(mouseX > 10 && mouseX < 10 + 20 && mouseY > 265 && mouseY < 265 + 20){
        stroke(20);
        fill(200);
        rect(10,265, 20, 20);
      }
      
      fill(20);
      noStroke();
      textSize(15);
      text("<", 20, 280);
    
  }
  
    // Página 2 das Informações
    else if( tela == 8){
    background(220);
    textAlign(LEFT);
    textSize(14);
    noStroke();
    fill(20);
    text("    Foram retirados as referências de sites como 'Exame.', baseei-me também, no próprio site do p5.js e, não menos importante, nos ensinamentos do professor Orivaldo e a monitora Dayana. ", 20, 40, 260, 260);
      
      // Botão de saída da página
       if(mouseX > 9 && mouseX < 9 + 20 && mouseY > 7 && mouseY < 7 + 20){
        stroke(20);
        fill(200);
        rect(10, 5, 20, 20);
      }
      
      fill(20);
      textSize(12);
      noStroke();
      text("X", 15, 20);
    
      // Enumerador de página
      fill(20);
      textSize(12);
      textAlign(CENTER);
      noStroke();
      text("página 2", 150, 280);
    
      // Botão de mudança de página
       if(mouseX > 10 && mouseX < 10 + 20 && mouseY > 265 && mouseY < 265 + 20){
        stroke(20);
        fill(200);
        rect(10,265, 20, 20);
      }
      
      fill(20);
      noStroke();
      textSize(15);
      text("<", 20, 280);
      
    }
  
    // Página 2 da fase 1
    else if( tela == 9 ) {
     background(220);
      
        //Pergunta #2
        textAlign(CENTER);
        textSize(14);
        text("Basendo-se em seus conhecimentos,", 150, 55);
        text("resolva o que se pede:", 150, 70);
        text("7 + 49 - 21 + 2 = ? ", 150, 105);
      
        //Alternativa #2
       if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo1 && mouseY < yJogo1 + alturaJogo){
        stroke(220);
        fill(200);
        rect(xJogo, yJogo1, larguraJogo, alturaJogo);
      }
        textSize(14);
        textAlign(CENTER);
        fill(0);
        noStroke();
        text("A) 15", 125, 135);
      
      if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo2 && mouseY < yJogo2 + alturaJogo){
        stroke(220);
        fill(200);
        rect(xJogo, yJogo2, larguraJogo, alturaJogo);
      }
        textSize(14);
        textAlign(CENTER);
        fill(0);
        noStroke();
        text("B) 37", 125, 165);
      
      if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo3 && mouseY < yJogo3 + alturaJogo){
        stroke(220);
        fill(200);
        rect(xJogo, yJogo3, larguraJogo, alturaJogo);
      }
        textSize(14);
        textAlign(CENTER);
        fill(0);
        noStroke();
        text("C) 79", 125, 195);
        
      if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo4 && mouseY < yJogo4 + alturaJogo){
        stroke(220);
        fill(200);
        rect(xJogo, yJogo4, larguraJogo, alturaJogo);
      }
        textSize(14);
        textAlign(CENTER);
        fill(0);
        noStroke();
        text("D) -14", 125, 225);
      
      if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo5 && mouseY < yJogo5 + alturaJogo){
        stroke(220);
        fill(200);
        rect(xJogo, yJogo5, larguraJogo, alturaJogo);
      }
        textSize(14);
        textAlign(CENTER);
        fill(0);
        noStroke();
        text("E) 49", 125, 255);
      
      // Desenvolvimento do botão de pausa
      
      if(mouseX > 9 && mouseX < 9 + 20 && mouseY > 7 && mouseY < 7 + 20){
        stroke(220);
        fill(200);
        rect(9, 7, 20, 20);
      }
      textSize(14);
      fill(0);
      noStroke();
      text("||", 15, 20);
    
    
    
    
    
    }
  
    // Tela de Pausa 2
    else if(tela == 10){
      
      fill(240);
      textAlign(CENTER);
      textSize(26);
      
      // Botão que volta ao jogo
      
      if ( mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu1 && mouseY < yMenu1 + altura ) {
        stroke(20);
        fill(200);
        rect(xMenu, yMenu1, largura, altura, 15);
      }
      
      fill(20);
      noStroke();
      text("Voltar", 150, 120);
      
      // Botão que volta ao menu iniciar
      
      if (mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu2 && mouseY < yMenu2 + altura) {
        stroke(20);
        fill(200);
        rect(xMenu, yMenu2, largura, altura, 15);

      }
        
      fill(20);
      noStroke();
      text("Menu inicial", 150, 180);
      
    }
  
    // Página 3 da fase 1
    else if( tela == 11 ) {
     background(220);
      
        //Pergunta #3
        textAlign(CENTER);
        textSize(14);
        text("Basendo-se em seus conhecimentos,", 150, 55);
        text("resolva o que se pede:", 150, 70);
        text("72 - 18 + 32 - 12 = ? ", 150, 105);
      
        //Alternativa #3
       if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo1 && mouseY < yJogo1 + alturaJogo){
        stroke(220);
        fill(200);
        rect(xJogo, yJogo1, larguraJogo, alturaJogo);
      }
        textSize(14);
        textAlign(CENTER);
        fill(0);
        noStroke();
        text("A) 35", 125, 135);
      
      if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo2 && mouseY < yJogo2 + alturaJogo){
        stroke(220);
        fill(200);
        rect(xJogo, yJogo2, larguraJogo, alturaJogo);
      }
        textSize(14);
        textAlign(CENTER);
        fill(0);
        noStroke();
        text("B) 64", 125, 165);
      
      if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo3 && mouseY < yJogo3 + alturaJogo){
        stroke(220);
        fill(200);
        rect(xJogo, yJogo3, larguraJogo, alturaJogo);
      }
        textSize(14);
        textAlign(CENTER);
        fill(0);
        noStroke();
        text("C) 91", 125, 195);
        
      if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo4 && mouseY < yJogo4 + alturaJogo){
        stroke(220);
        fill(200);
        rect(xJogo, yJogo4, larguraJogo, alturaJogo);
      }
        textSize(14);
        textAlign(CENTER);
        fill(0);
        noStroke();
        text("D) -22", 125, 225);
      
      if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo5 && mouseY < yJogo5 + alturaJogo){
        stroke(220);
        fill(200);
        rect(xJogo, yJogo5, larguraJogo, alturaJogo);
      }
        textSize(14);
        textAlign(CENTER);
        fill(0);
        noStroke();
        text("E) 74", 125, 255);
      
      // Desenvolvimento do botão de pausa
      
      if(mouseX > 9 && mouseX < 9 + 20 && mouseY > 7 && mouseY < 7 + 20){
        stroke(220);
        fill(200);
        rect(9, 7, 20, 20);
      }
      textSize(14);
      fill(0);
      noStroke();
      text("||", 15, 20);
    
    
    
    
    
    }
  
    // Tela de Pausa 3
    else if(tela == 12){
      fill(240);
      textAlign(CENTER);
      textSize(26);
      
      // Botão que volta ao jogo
      
      if ( mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu1 && mouseY < yMenu1 + altura ) {
        stroke(20);
        fill(200);
        rect(xMenu, yMenu1, largura, altura, 15);
      }
      
      fill(20);
      noStroke();
      text("Voltar", 150, 120);
      
      // Botão que volta ao menu iniciar
      
      if (mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu2 && mouseY < yMenu2 + altura) {
        stroke(20);
        fill(200);
        rect(xMenu, yMenu2, largura, altura, 15);

      }
        
      fill(20);
      noStroke();
      text("Menu inicial", 150, 180);
      
    }
  
  // Página 4 da fase 1
    else if( tela == 13 ) {
     background(220);
      
        //Pergunta #4
        textAlign(CENTER);
        textSize(14);
        text("Basendo-se em seus conhecimentos,", 150, 55);
        text("resolva o que se pede:", 150, 70);
        text("25 + 12 + 37 - 102 = ? ", 150, 105);
      
        //Alternativa #4
       if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo1 && mouseY < yJogo1 + alturaJogo){
        stroke(220);
        fill(200);
        rect(xJogo, yJogo1, larguraJogo, alturaJogo);
      }
        textSize(14);
        textAlign(CENTER);
        fill(0);
        noStroke();
        text("A) 176", 125, 135);
      
      if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo2 && mouseY < yJogo2 + alturaJogo){
        stroke(220);
        fill(200);
        rect(xJogo, yJogo2, larguraJogo, alturaJogo);
      }
        textSize(14);
        textAlign(CENTER);
        fill(0);
        noStroke();
        text("B) 64", 125, 165);
      
      if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo3 && mouseY < yJogo3 + alturaJogo){
        stroke(220);
        fill(200);
        rect(xJogo, yJogo3, larguraJogo, alturaJogo);
      }
        textSize(14);
        textAlign(CENTER);
        fill(0);
        noStroke();
        text("C) -27", 125, 195);
        
      if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo4 && mouseY < yJogo4 + alturaJogo){
        stroke(220);
        fill(200);
        rect(xJogo, yJogo4, larguraJogo, alturaJogo);
      }
        textSize(14);
        textAlign(CENTER);
        fill(0);
        noStroke();
        text("D) -28", 125, 225);
      
      if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo5 && mouseY < yJogo5 + alturaJogo){
        stroke(220);
        fill(200);
        rect(xJogo, yJogo5, larguraJogo, alturaJogo);
      }
        textSize(14);
        textAlign(CENTER);
        fill(0);
        noStroke();
        text("E) 74", 125, 255);
      
      // Desenvolvimento do botão de pausa
      
      if(mouseX > 9 && mouseX < 9 + 20 && mouseY > 7 && mouseY < 7 + 20){
        stroke(220);
        fill(200);
        rect(9, 7, 20, 20);
      }
      textSize(14);
      fill(0);
      noStroke();
      text("||", 15, 20);
    
    
    
    
    
    }
  
  // Tela de Pausa 4
    else if(tela == 14){
      fill(240);
      textAlign(CENTER);
      textSize(26);
      
      // Botão que volta ao jogo
      
      if ( mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu1 && mouseY < yMenu1 + altura ) {
        stroke(20);
        fill(200);
        rect(xMenu, yMenu1, largura, altura, 15);
      }
      
      fill(20);
      noStroke();
      text("Voltar", 150, 120);
      
      // Botão que volta ao menu iniciar
      
      if (mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu2 && mouseY < yMenu2 + altura) {
        stroke(20);
        fill(200);
        rect(xMenu, yMenu2, largura, altura, 15);

      }
        
      fill(20);
      noStroke();
      text("Menu inicial", 150, 180);
      
    }
  
  // Página 5 da fase 1
    else if( tela == 15 ) {
     background(220);
      
        //Pergunta #5
        textAlign(CENTER);
        textSize(14);
        text("Basendo-se em seus conhecimentos,", 150, 55);
        text("resolva o que se pede:", 150, 70);
        text("12 + 27 + 66 - 48 = ? ", 150, 105);
      
        //Alternativa #5
       if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo1 && mouseY < yJogo1 + alturaJogo){
        stroke(220);
        fill(200);
        rect(xJogo, yJogo1, larguraJogo, alturaJogo);
      }
        textSize(14);
        textAlign(CENTER);
        fill(0);
        noStroke();
        text("A) 57", 125, 135);
      
      if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo2 && mouseY < yJogo2 + alturaJogo){
        stroke(220);
        fill(200);
        rect(xJogo, yJogo2, larguraJogo, alturaJogo);
      }
        textSize(14);
        textAlign(CENTER);
        fill(0);
        noStroke();
        text("B) 71", 125, 165);
      
      if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo3 && mouseY < yJogo3 + alturaJogo){
        stroke(220);
        fill(200);
        rect(xJogo, yJogo3, larguraJogo, alturaJogo);
      }
        textSize(14);
        textAlign(CENTER);
        fill(0);
        noStroke();
        text("C) -42", 125, 195);
        
      if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo4 && mouseY < yJogo4 + alturaJogo){
        stroke(220);
        fill(200);
        rect(xJogo, yJogo4, larguraJogo, alturaJogo);
      }
        textSize(14);
        textAlign(CENTER);
        fill(0);
        noStroke();
        text("D) 58", 125, 225);
      
      if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo5 && mouseY < yJogo5 + alturaJogo){
        stroke(220);
        fill(200);
        rect(xJogo, yJogo5, larguraJogo, alturaJogo);
      }
        textSize(14);
        textAlign(CENTER);
        fill(0);
        noStroke();
        text("E) 46", 125, 255);
      
      // Desenvolvimento do botão de pausa
      
      if(mouseX > 9 && mouseX < 9 + 20 && mouseY > 7 && mouseY < 7 + 20){
        stroke(220);
        fill(200);
        rect(9, 7, 20, 20);
      }
      textSize(14);
      fill(0);
      noStroke();
      text("||", 15, 20);
    
    
    
    
    
    }
  
  // Tela de Pausa 5
    else if(tela == 16){
      fill(240);
      textAlign(CENTER);
      textSize(26);
      
      // Botão que volta ao jogo
      
      if ( mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu1 && mouseY < yMenu1 + altura ) {
        stroke(20);
        fill(200);
        rect(xMenu, yMenu1, largura, altura, 15);
      }
      
      fill(20);
      noStroke();
      text("Voltar", 150, 120);
      
      // Botão que volta ao menu iniciar
      
      if (mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu2 && mouseY < yMenu2 + altura) {
        stroke(20);
        fill(200);
        rect(xMenu, yMenu2, largura, altura, 15);

      }
        
      fill(20);
      noStroke();
      text("Menu inicial", 150, 180);
      
    }
  
  // Tela de Perdeu
    else if( tela == 17) {
     background(220);
     textAlign(CENTER);
     textSize(32);
     text("Game Over", 150, 100)
      
      
    if ( mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu2 && mouseY < yMenu2 + altura ) {
        stroke(20);
        fill(200);
        rect(xMenu, yMenu2, largura, altura, 15);
      }
      
      fill(20);
      noStroke();
      textSize(26);
      text("Voltar ao menu", 150, 180);
    
    
    
    
    }
  
  // Tela Passou fase 1
    else if ( tela == 18 ){
      background(220);
     textAlign(CENTER);
     textSize(32);
     text("Parabéns!", 150, 100);
      textSize(16);
      text("Você superou a primeira fase.", 150, 130)
      
    if ( mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu2 && mouseY < yMenu2 + altura ) {
        stroke(20);
        fill(200);
        rect(xMenu, yMenu2, largura, altura, 15);
      }
      
      fill(20);
      noStroke();
      textSize(26);
      text("Voltar ao menu", 150, 180);
      
    }
  
  // Tela em desenvolvimento
    else if ( tela == 19 ){
      background(220);
     textAlign(CENTER);
     textSize(20);
     text("O jogo ainda está", 150, 100);
      text("em desenvolvimento", 150, 120);
      text("Em breve", 150, 140);
      text("novidades virão", 150, 160);
     
    if ( mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu3 && mouseY < yMenu3 + altura ) {
        stroke(20);
        fill(200);
        rect(xMenu, yMenu3, largura, altura, 15);
      }
      
      fill(20);
      noStroke();
      textSize(26);
      text("Voltar ao menu", 150, 240);
      
    }
  
    }      
    
function mouseReleased() {
  //Tela 1 Botões
  if (tela == 1) {
    
    //localizador
    console.log("Tela 1!");
    
    //botão Iniciar
    if (mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu1 && mouseY < yMenu1 + altura) { tela = 6; }
    
    //botão Tutorial
     if ( mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu2 && mouseY < yMenu2 + altura) { tela = 3; }
    
    //botão Informações
    if ( mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu3 && mouseY < yMenu3 + altura ) { tela = 4; }
  } 
  
  //Tela 6 Botões
  else if (tela == 6) {
    
    //localizador
    console.log("Tela 6!");
    
    //botão fase 1
    if (mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu1 && mouseY < yMenu1 + altura) { tela = 2; }
    
    //botão fase 2
    if ( mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu2 && mouseY < yMenu2 + altura ) { tela = 19; }
    
    //botão fase 3
    if ( mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu3 && mouseY < yMenu3 + altura ) { tela = 19; }

  }
  
  //Tela 2 Botões
  else if(tela == 2){
    
    //localizador
    console.log("Tela 2!");
    
    //botão de pausa
    if(mouseX > 9 && mouseX < 9 + 20 && mouseY > 7 && mouseY < 7 + 20){ tela = 5; }
    
    //botão correto
    //e
    if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo5 && mouseY < yJogo5 + alturaJogo){ tela = 9; }
    
    //botão incorreto
    //a
    if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo1 && mouseY < yJogo1 + alturaJogo){ tela = 17; }
    
    //b
    if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo2 && mouseY < yJogo2 + alturaJogo){ tela = 17; }
    
    //c
    if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo3 && mouseY < yJogo3 + alturaJogo){ tela = 17; }
    
    //d
     if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo4 && mouseY < yJogo4 + alturaJogo){ tela = 17; }
  
  }
  
  //Tela 5 Botões
  else if(tela == 5){
    
    //localizador
    console.log("Tela 5!");
    
    //botão voltar
    if ( mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu1 && mouseY < yMenu1 + altura ) { tela = 2; }
    
    //botão menu inicial
     if (mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu2 && mouseY < yMenu2 + altura) { tela = 1; }
    
  }
  
  //Tela 3 Botões
  else if(tela == 3){
    
    //localizador
    console.log("Tela 3!");
    
    //Botão de retorno para o menu inicial
    if(mouseX > 9 && mouseX < 9 + 20 && mouseY > 7 && mouseY < 7 + 20){ tela = 1; }
    
    //Botão de mudança de página
    if(mouseX > 260 && mouseX < 260 + 20 && mouseY > 265 && mouseY < 265 + 20){ tela = 7; }
    
  }
  
  //Tela 7 Botões
  else if(tela == 7){
    
    //localizador
    console.log("Tela 7!");
    
    //Botão de retorno para o menu inicial
    if(mouseX > 9 && mouseX < 9 + 20 && mouseY > 7 && mouseY < 7 + 20){ tela = 1; }
    
    //Botão de mudãnça de página
    if(mouseX > 10 && mouseX < 10 + 20 && mouseY > 265 && mouseY < 265 + 20){ tela = 3; }
  }
  
  //Tela 4 Botões
  else if(tela == 4){
    
    //localizador
    console.log("Tela 4!");
    
    //Botão de retorno para o menu inicial
    if(mouseX > 9 && mouseX < 9 + 20 && mouseY > 7 && mouseY < 7 + 20){ tela = 1; }
    
     // botão de mudança de página
    if(mouseX > 260 && mouseX < 260 + 20 && mouseY > 265 && mouseY < 265 + 20){ tela = 8; }
  }
  
  //Tela 8 Botões
  else if(tela == 8){
    
    //localizador
    console.log("Tela 8!");
    
    // Botão de saída da página
    if(mouseX > 9 && mouseX < 9 + 20 && mouseY > 7 && mouseY < 7 + 20){ tela = 1; }
    
    // Botão de mudança de página
    if(mouseX > 10 && mouseX < 10 + 20 && mouseY > 265 && mouseY < 265 + 20){ tela = 4; }
    
  }
  
  //Tela 2 Botões
  else if(tela == 9){
    
    //localizador
    console.log("Tela 9!");
    
    //botão de pausa
    if(mouseX > 9 && mouseX < 9 + 20 && mouseY > 7 && mouseY < 7 + 20){ tela = 10; }
    
    //botão correto
    //b
    if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo2 && mouseY < yJogo2 + alturaJogo){ tela = 11; }
  
    //botão errado
    //a
    if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo1 && mouseY < yJogo1 + alturaJogo){ tela = 17; }
    
    //c
    if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo3 && mouseY < yJogo3 + alturaJogo){ tela = 17; }
    
    //d
     if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo4 && mouseY < yJogo4 + alturaJogo){ tela = 17; }
  
    //e
    if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo5 && mouseY < yJogo5 + alturaJogo){ tela = 17; }
    
    
  }
  
  //Tela 10 Botões
  else if(tela == 10){
    
    //localizador
    console.log("Tela 10!");
    
    //botão voltar
    if ( mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu1 && mouseY < yMenu1 + altura ) { tela = 9; }
    
    //botão menu inicial
     if (mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu2 && mouseY < yMenu2 + altura) { tela = 1; }
    
  }
  
  //Tela 11 Botões
  else if(tela == 11){
    
    //localizador
    console.log("Tela 11!");
    
    //botão de pausa
    if(mouseX > 9 && mouseX < 9 + 20 && mouseY > 7 && mouseY < 7 + 20){ tela = 12; }
    
    //botão correto
    //e
    if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo5 && mouseY < yJogo5 + alturaJogo){ tela = 13; }
    
    //botão incorreto
    //a
    if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo1 && mouseY < yJogo1 + alturaJogo){ tela = 17; }
    
    //b
    if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo2 && mouseY < yJogo2 + alturaJogo){ tela = 17; }
    
    //c
    if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo3 && mouseY < yJogo3 + alturaJogo){ tela = 17; }
    
    //d
     if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo4 && mouseY < yJogo4 + alturaJogo){ tela = 17; }
    
    
  }
  
  //Tela 12 Botões
  else if(tela == 12){
    
    //localizador
    console.log("Tela 12!");
    
    //botão voltar
    if ( mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu1 && mouseY < yMenu1 + altura ) { tela = 11; }
    
    //botão menu inicial
     if (mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu2 && mouseY < yMenu2 + altura) { tela = 1; }
    
  }
  
  //Tela 13 Botões
  else if(tela == 13){
    
    //localizador
    console.log("Tela 13!");
    
    //botão de pausa
    if(mouseX > 9 && mouseX < 9 + 20 && mouseY > 7 && mouseY < 7 + 20){ tela = 14; }
    
    //botão correto
    //d
     if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo4 && mouseY < yJogo4 + alturaJogo){ tela = 15; }
    
    //botão incorreto
    //a
    if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo1 && mouseY < yJogo1 + alturaJogo){ tela = 17; }
    
    //b
    if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo2 && mouseY < yJogo2 + alturaJogo){ tela = 17; }
    
    //c
    if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo3 && mouseY < yJogo3 + alturaJogo){ tela = 17; }
    
    //e
    if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo5 && mouseY < yJogo5 + alturaJogo){ tela = 17; }
    
  }
  
  //Tela 14 Botões
  else if(tela == 14){
    
    //localizador
    console.log("Tela 14!");
    
    //botão voltar
    if ( mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu1 && mouseY < yMenu1 + altura ) { tela = 13; }
    
    //botão menu inicial
     if (mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu2 && mouseY < yMenu2 + altura) { tela = 1; }
    
  }
  
  //Tela 15 Botões
  else if(tela == 15){
    
    //localizador
    console.log("Tela 15!");
    
    //botão de pausa
    if(mouseX > 9 && mouseX < 9 + 20 && mouseY > 7 && mouseY < 7 + 20){ tela = 16; }
    
    //botão correto
    //a
    if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo1 && mouseY < yJogo1 + alturaJogo){ tela = 19; }
    
    //botão incorreto
    //b
    if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo2 && mouseY < yJogo2 + alturaJogo){ tela = 17; }
    
    //c
    if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo3 && mouseY < yJogo3 + alturaJogo){ tela = 17; }
    
    //d
     if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo4 && mouseY < yJogo4 + alturaJogo){ tela = 17; }
    //e
    if(mouseX > xJogo && mouseX < xJogo + larguraJogo && mouseY > yJogo5 && mouseY < yJogo5 + alturaJogo){ tela = 17; }
  }
  
  //Tela 16 Botões
  else if(tela == 16){
    
    //localizador
    console.log("Tela 16!");
    
    //botão voltar
    if ( mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu1 && mouseY < yMenu1 + altura ) { tela = 15; }
    
    //botão menu inicial
     if (mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu2 && mouseY < yMenu2 + altura) { tela = 1; }
    
  }
  
  //Tela 17 botões
  else if(tela == 17) {
    //localizador
    console.log("Tela 17!");
    
     if ( mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu2 && mouseY < yMenu2 + altura ) { tela = 1; }
    
    
  }
  
   //Tela 18 botões
  else if(tela == 18) {
    //localizador
    console.log("Tela 18!");
    
     if ( mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu2 && mouseY < yMenu2 + altura ) { tela = 1; }
    
    
  }
  
  //Tela 19 botões
  else if(tela == 19) {
    //localizador
    console.log("Tela 19!");
    
     if ( mouseX > xMenu && mouseX < xMenu + largura && mouseY > yMenu3 && mouseY < yMenu3 + altura ) { tela = 1; }
    
    
  }
  
  
}
