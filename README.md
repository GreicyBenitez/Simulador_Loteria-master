# Projeto Loteria
Um simulador de loteria que os usuarios escolhe seis numeros
e o programa sorteia outros seis numeros e após isso
verifica a quantidade de acertos!!!

## Tecnologias Utilizadas
- **HTML:** _Estrutura do SITE_
- **CSS:** Estilos do SITE
- **JS:** Funções do SITE
- ~~BootStrap~~: Não foi utilizado


### Melhorias Possiveis
1. [X] Subir no github pages
2. [ ] Trocar o Alert por mensagens mais amigaveis (T_T)
3. [ ] Realizar testes para descobrir bugs 👾

### disponivel em:
[GitHubPage]( https://greicybenitez.github.io/Simulador_Loteria-master/)

### Prints da Tela do WebApp

| Tela inicial | Primeira Rodada | 
|--------------|-----------------|
| imagem 1     | imagem 2        |


 ### codigo principal
  ```js:
  function verificaAcertos() {
  let cont = 0
  numDigitados.forEach(function (valor, index) {
    if (numSort.includes(valor)) {
      cont = cont + 1
    }
  })
  document.getElementById("total").innerText = cont
}
  ```
