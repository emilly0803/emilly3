
for (let i = 0; i < contadores.length; i++) {
  let tempo = calculaTempo(tempos[i]);

  document.getElementById("dias" + i).textContent = tempo[0];
  document.getElementById("horas" + i).textContent = tempo[1];
  document.getElementById("min" + i).textContent = tempo[2];
  document.getElementById("seg" + i).textContent = tempo[3];
}
