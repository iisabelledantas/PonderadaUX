# Ponderada UX - Acessibilidade e Usabilidade

## 1. Contextualização

&nbsp;&nbsp;&nbsp;&nbsp; O projeto "Borbulha" refere-se a elaboração de uma plataforma web com o objetivo de gerar uma onda massiva de transformação através do voluntariado, o VTM- Voluntariado Transformador Massivo, em parceria com a Parceiros Voluntários. Assim, a plataforma deverá unificar pessoas interessadas no voluntariado, bem como organizações sociais.

&nbsp;&nbsp;&nbsp;&nbsp; Nessa lógica, a plataforma será baseada em uma rede social, na qual, entre outras funcionalidades, os usuários poderão compartilhar suas experiências no voluntariado, bem como em ações que estão realizando no momento e necessitam de ajuda. Desse modo, as telas que serão abordadas abaixo têm esse propósito. 
 

## 2. Expor critério de avaliação e avaliar a tela “antes” (tela atual do projeto)

### 2.1. Acessibilidade

&nbsp;&nbsp;&nbsp;&nbsp; Tendo em vista a importância de construir um produto que seja acessível para a maior quantidade de pessoas possíveis escolheu-se incorporar uma funcionalidade que torna a aplicação WEB um pouco mais acessível. Nesse sentido, os botões que são imagens em nosso código irão conter textos de descrição, sendo que essa funcionalidade não foi adicionada na primeira aplicação WEB.

&nbsp;&nbsp;&nbsp;&nbsp; Segue abaixo o atual código:

``` html
<button>
    <img src="/assets/images/frontend/icons/bolha.png">
</button>  

<button>
    <img src="/assets/images/frontend/icons/compartilhar.png">
</button> 
```

## 3. Descrever mudanças e apresentar a tela com a nova proposta (mockup).

### 3.1. Acessibilidade

&nbsp;&nbsp;&nbsp;&nbsp; Para a incorporação da funcionalidade citada acima com a finalidade que pessoas com deficiência visual consigam saber sobre o que se trata um botão que utiliza imagem serão utilizadas os recursos 'aria-label' e 'alt' do html. Assim, o 'aria-label' proporciona uma descrição para elementos interativos e o 'alt' é um atributo utilizado em elementos de imagens com o objetivo de fornecer um texto alternativo que descreve o conteúdo da imagem.

&nbsp;&nbsp;&nbsp;&nbsp; Assim, segue o código com as devidas alterações:

```html
<button aria-label="Curtir publicação - borbulhar">
    <img src="/assets/images/frontend/icons/bolha.png" alt=" Curtir - bolha">
</button>  

<button aria-label="Compartilhar publicação">
    <img src="/assets/images/frontend/icons/compartilhar.png" alt="Compartilhar">
</button> 
```

## 4. Explicar como as mudanças melhoram a usabilidade ou acessibilidade do projeto.

&nbsp;&nbsp;&nbsp;&nbsp; Por fim, por meio da implementação dos recursos 'aria-label' e 'alt' do html pessoas com alguma deficiência visual que utilizam leitores de tela para navegar em plataformas WEB não terão grandes dificuldades de compreensão dos botões de imagens. Assim, permitindo que a plataforma "Borbulha" seja um pouco mais inclusiva.
