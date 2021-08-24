# Posicionando elementos com Flexbox em CSS
## Pré-requisitos
- IDE
- Navegador

## Suporte
Foi projetado como um modelo de layout unidimensional e como um método que pode oferecer distribuição de espaço entre itens em uma interface e recursos de alinhamento.

## Flex Container
É a tag que envolve os itens, será nela que iremos aplicar a propriedade `display: flex`. Transforma todos os seus itens filhos em flex itens. Propriedades relacionadas: 
- flex-direction (faz o direcionamento dos itens em linha ou coluna). Por padrão é da esquerda para direita `row`, o `row-reverse` é o sentido oposto, `column` é a ordenação de cima para baixo, `column-reverse` é a ordenação de baixo para cima. 
- flex-wrap (quebra de linha). `nowrap` é o padrão é não quebrar linha, `wrap` permite a quebra de linha, quando um elemento não couber na linha ele vai ser jogado para a próxima linha e `wrap-reverse` é o sentido oposto.
- flex-flow (é uma abreviação para o direction e o wrap). 
- justify-content (alinha os itens de acordo com a direção). O padrão é o `flex-start`, os itens ficam no início do container, `flex-end` no final do container, `center` ao centro do container, `space-between` cria um espaçamento igual entre os elementos, `space-around` o espaçamento do meio são duas vezes maiores que o inicial e final.
- align-items (alinha os itens de acordo com o eixo do container). `center` alinhamento dos itens ao centro, `stretch` padrão, `flex-start`, os itens ficam no início do container, `flex-end` no final do container, `baseline` alinhamento de acordo com a linha base da tipografia dos itens.
- align-content (alinha as linhas). `center` alinhamento dos itens ao centro, `stretch` padrão, `flex-start`, os itens ficam no início do container, `flex-end`, `space-between` cria um espaçamento igual entre os elementos, `space-around` o espaçamento do meio são duas vezes maiores que o inicial e final.

![flex](https://user-images.githubusercontent.com/72028645/130623926-0f6b80ca-2ade-4ace-9380-5bc4f2e0a239.png)

## Flex Item
São elementos filhos diretos do Flex Container. E também podem se tornar Flex Container. Propriedades relacionadas:
- flex-grow (define o fator de crescimento)
- flax-basis (define o tamanho inicial do item antes da distribuição). Valores possíveis: `auto` caso o item não tenha tamanho, este será proporcional ao conteúdo do item, `px`, `%`, `em`, `...` são valores exatos previamente definidos. `0` terá relação com a definição do flex-grow. 
- flex-shrink (capacidade de redução)
- flex (um item do lado do outro)
- order (ordem de distribuição e listagem dos itens)
- align-self (alinhamento de um item específico), `auto` é o valor padrão, `flex-start`, os itens ficam no início do container, `flex-end` no final do container, `center` relativo ao centro de acordo com o eixo, `stretch` ocupa todo o espaço relativo, `baseline` utiliza a linha base da tipografia.

![container](https://user-images.githubusercontent.com/72028645/130624783-16925f6f-0e0c-4530-b53f-3f399ac53270.png)

## Sobre a Autora
Oi, eu sou a Fernanda! Estou aqui para contribuir com meu conhecimento e espero poder ajudar no desenvolvimento profissional de cada um de vocês.

[![Linkedin Badge](https://img.shields.io/badge/-Fernanda_Maki_Hirose-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/fernanda-maki-hirose-801117208/)](https://www.linkedin.com/in/fernanda-maki-hirose-801117208/)  [![Gmail Badge](https://img.shields.io/badge/-femahi2020@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:femahi2020@gmail.com)](mailto:femahi2020@gmail.com)
