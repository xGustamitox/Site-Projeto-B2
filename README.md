# Site-Projeto-B2
# 
### Aluno: Gustavo Batista Bissoli
### Turma: CC1MB
### Funções usados no JavaSCript:
 ### Códigos responsáveis pela função de passar as imagens automaticamente, em um intervalo de 2 segundos.
 $('.slider-principal').slick({
  dots: true,
  infinite: true,
  speed: 300,
  slidesToShow: 1,
  centerMode: true,
  variableWidth: true,
  autoplay: true,
  autoplaySpeed: 2000
});
 ### Códigos responsáveis pelo envio do cadastro.
 function fn(){
    alert("Cadastro Enviado");
  
}
function clear(){
  alert("Cadastro Limpo");
}

