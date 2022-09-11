# Aula 04 - Casos de Teste

Assista aos vídeos:

  1. [Como escrever casos de testes funcionais](https://youtu.be/BMeOV1-senE) ✅
  2. [BDD: da especificação a Automação](https://youtu.be/M32rwhjnsRI) ✅

> É **#fundamental** que você assista aos vídeos. É **#opcional** _(embora bem interessante)_ que você faça o exercício.

---

#### _Exercício:_

Elabore cenários simulando testes na funcionalidade de login do Google (exemplo da imagem abaixo). 

![Login](../../assets/login.png)

##### Considerações:

- Pense em fluxos principais e fluxos alternativos;
- Exercite as técnicas de testes apresentada nos vídeos;
- Descreva pelo menos um cenário na estrutura passo a passo, e ao menos um cenário no formato Gherkin.

Não há resposta certa ou errada. 😉

_**Após** fazer o exercício, dá uma conferida no [nosso exemplo](resolucao.md) de resposta._ 

---
_Minhas respostas:_

### Exemplo de cenário passo a passo:

#### Acessar o site do Google

Passos | Descrição                                                                  | Resultado                                 |
1      | ----------------------------------------------                             | ----------------------------------------- |
2      | Acessar a página de login do Google                                        | Devo ser direcionado para a tela de login |
3      | No campo onde menciona "email ou telefone" incluir com a informação válida | Não deve ocorrer erro                     |
4      | Clicar no botão "Proxima"                                                  | Devo ser direcionado para a tela de senha |
5      | No campo "senha" incluir um valor válido                                   | Não deve ocorrer erro                     |
6      | Clicar no botão "Proxima"                                                  | Devo ser direcionado para a aplicação     |


### Exemplo de cenário utilizando Gherkin:

```
Cenário: Efetuar o login no site do Google
Dado que acessei o site
E visualizei a tela de login
Quando preencho o e-mail e senha
Então é possível acessar a aplicação
```

---

👈 [Voltar para aula anterior](../aula03/aula.md)
👈 [Voltar para o índice](../README.md)
