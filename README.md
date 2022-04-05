# Simulador de loteria

Este é um projeto que simula uma loteria,
onde o usuário digita 6 números e realiza um
sorteio de outros 6 números, no final é verificado
quantos números ele acertou.

## Tecnologias utilizadas

- **HTML**: estrutura do site
- __CSS__: estilização do site
- *_JS_*: funções do site
- ~~BootStrap~~: Não foi utilizado

### Possíveis melhorias

1. [ ] Subir para GITHubPages
2. [ ] Alterar os Alerts
3. [ ] Utilizar o BootStrap
4. [ ] Deixar responsivo

### ERROS:
Ele não conta o número de acertos! Até o prof tentou concertar mas n deu...

### Prints da tela

| ID | Primeira tela |  Segunda tela  |
|----|---------------|----------------|
| 1  | loteca limpa  |  loteca preenchida|
| 2  |![telaLotecaNPreench](https://user-images.githubusercontent.com/101193963/161781706-1b4097f4-c4d8-4a20-91c3-cb2dc8049df4.png)| ![image](https://user-images.githubusercontent.com/101193963/161782780-6cfd22c6-af06-4fd1-aa58-e66c0dfb5685.png) |

### Função principal

```
function sorteio(){
var numSort =[]
var cont = 0

    while(cont < 6){
      let num = Math.random()*60
      num = Math.ceil(num)

     
       numSort[cont] = num
      console.log(numSort)
      cont++    
     
     
    }
    document.getElementById("sorteados").innerHTML = numSort
   contAcertos()
}

```

### comando git
para iniciar o projeto
```
git init
```

### disponibilizado em
[GITHubPage](https://biularambo.github.io/applibras/)
