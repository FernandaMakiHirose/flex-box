# Posicionando elementos com Flexbox em CSS
## Pré-requisitos
- IDE
- Navegador

## Suporte
Foi projetado como um modelo de layout unidimensional e como um método que pode oferecer distribuição de espaço entre itens em uma interface e recursos de alinhamento.

## Flex Container
É a tag que envolve os itens, será nela que iremos aplicar a propriedade `display: flex`. Transforma todos os seus itens filhos em flex itens. Propriedades relacionadas: 
- flex-direction (faz o direcionamento dos itens em linha ou coluna)
- flex-wrap (quebra de linha)
- flex-flow (é uma abreviação para o direction e o wrap)
- justify-content (alinha os itens de acordo com a direção)
- align-items (alinha os itens de acordo com o eixo do container)
- align-content (alinha as linhas)

![flex](https://user-images.githubusercontent.com/72028645/130623926-0f6b80ca-2ade-4ace-9380-5bc4f2e0a239.png)

## Flex Item
São elementos filhos diretos do Flex Container. E também podem se tornar Flex Container. Propriedades relacionadas:
- flex-grow (define o fator de crescimento)
- flax-basis (define o tamanho inicial do item antes da distribuição)
- flex-shrink (capacidade de redução)
- flex (um item do lado do outro)
- order (ordem de distribuição e listagem dos itens)
- align-self (alinhamento de um item específico)

![container](https://user-images.githubusercontent.com/72028645/130624783-16925f6f-0e0c-4530-b53f-3f399ac53270.png)
