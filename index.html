let jogador;
let alimentos = [];
let arvores = [];
let lixos = [];

let pontos = 0;
let tempo = 60;
let estado = "inicio";

function setup() {
  createCanvas(900, 500);

  jogador = {
    x: width / 2,
    y: height - 70,
    tamanho: 40
  };

  for (let i = 0; i < 5; i++) {
    alimentos.push(criarAlimento());
  }

  for (let i = 0; i < 3; i++) {
    arvores.push(criarArvore());
  }

  for (let i = 0; i < 4; i++) {
    lixos.push(criarLixo());
  }
}

function draw() {

  if (estado == "inicio") {
    telaInicio();
    return;
  }

  if (estado == "fim") {
    telaFim();
    return;
  }

  desenharCenario();

  tempo -= deltaTime / 1000;

  if (tempo <= 0) {
    estado = "fim";
  }

  moverJogador();

  desenharJogador();

  mostrarAlimentos();
  mostrarArvores();
  mostrarLixos();

  fill(0);
  textSize(24);
  text("Pontos: " + pontos, 20, 35);

  text("Tempo: " + ceil(tempo), 20, 70);
}

function desenharCenario() {

  background(135, 206, 235);

  fill(90, 180, 90);
  rect(0, height / 2, width, height / 2);

  fill(230, 200, 80);
  rect(0, height / 2 + 60, width, 40);

  fill(255, 255, 0);
  ellipse(800, 80, 80);
}

function moverJogador() {

  if (keyIsDown(LEFT_ARROW)) {
    jogador.x -= 5;
  }

  if (keyIsDown(RIGHT_ARROW)) {
    jogador.x += 5;
  }

  if (keyIsDown(UP_ARROW)) {
    jogador.y -= 5;
  }

  if (keyIsDown(DOWN_ARROW)) {
    jogador.y += 5;
  }

  jogador.x = constrain(jogador.x, 20, width - 20);
  jogador.y = constrain(jogador.y, 20, height - 20);
}

function desenharJogador() {

  fill(50, 100, 255);
  ellipse(jogador.x, jogador.y, jogador.tamanho);

  fill(255, 220, 180);
  ellipse(jogador.x, jogador.y - 25, 25);
}

function mostrarAlimentos() {

  for (let i = alimentos.length - 1; i >= 0; i--) {

    let a = alimentos[i];

    fill(255, 200, 0);
    ellipse(a.x, a.y, 25);

    if (dist(jogador.x, jogador.y, a.x, a.y) < 30) {
      pontos += 10;
      alimentos[i] = criarAlimento();
    }
  }
}

function mostrarArvores() {

  for (let i = arvores.length - 1; i >= 0; i--) {

    let a = arvores[i];

    fill(120, 70, 20);
    rect(a.x - 5, a.y, 10, 20);

    fill(0, 180, 0);
    ellipse(a.x, a.y, 30);

    if (dist(jogador.x, jogador.y, a.x, a.y) < 30) {
      pontos += 15;
      arvores[i] = criarArvore();
    }
  }
}

function mostrarLixos() {

  for (let i = lixos.length - 1; i >= 0; i--) {

    let l = lixos[i];

    fill(120);
    rect(l.x, l.y, 20, 20);

    if (dist(jogador.x, jogador.y, l.x, l.y) < 30) {
      pontos -= 10;
      lixos[i] = criarLixo();
    }
  }
}

function criarAlimento() {
  return {
    x: random(50, width - 50),
    y: random(120, height - 50)
  };
}

function criarArvore() {
  return {
    x: random(50, width - 50),
    y: random(120, height - 50)
  };
}

function criarLixo() {
  return {
    x: random(50, width - 50),
    y: random(120, height - 50)
  };
}

function telaInicio() {

  background(100, 180, 255);

  textAlign(CENTER);

  fill(0);
  textSize(38);
  text("AGRINHO 2026", width / 2, 120);

  textSize(24);
  text("Agro Forte, Futuro Sustentável", width / 2, 180);

  textSize(20);
  text("Colete alimentos e plante árvores", width / 2, 240);

  text("Evite a poluição", width / 2, 280);

  text("Pressione ESPAÇO para começar", width / 2, 360);
}

function telaFim() {

  background(50, 150, 100);

  textAlign(CENTER);

  fill(255);

  textSize(40);
  text("Fim de Jogo!", width / 2, 150);

  textSize(30);
  text("Pontuação: " + pontos, width / 2, 230);

  if (pontos >= 200) {
    text("Você criou um futuro sustentável!", width / 2, 300);
  } else {
    text("Continue cuidando do campo e da natureza!", width / 2, 300);
  }

  textSize(22);
  text("Pressione R para jogar novamente", width / 2, 380);
}

function keyPressed() {

  if (estado == "inicio" && key == " ") {
    estado = "jogo";
  }

  if (estado == "fim" && (key == "r" || key == "R")) {
    reiniciar();
  }
}

function reiniciar() {

  pontos = 0;
  tempo = 60;

  alimentos = [];
  arvores = [];
  lixos = [];

  for (let i = 0; i < 5; i++) {
    alimentos.push(criarAlimento());
  }

  for (let i = 0; i < 3; i++) {
    arvores.push(criarArvore());
  }

  for (let i = 0; i < 4; i++) {
    lixos.push(criarLixo());
  }

  estado = "jogo";
}
