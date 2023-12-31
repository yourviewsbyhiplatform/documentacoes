# Instalação padrão - Bloco dos testemunhos
## Requisitos
Antes de prosseguir com a instalação do bloco dos testemunhos, é essencial que você tenha completado alguns passos preliminares fundamentais para garantir uma integração bem-sucedida e eficiente.


 ### Instalação do App Yourviews na Vtex Io

Um dos requisitos obrigatórios é possuir o app da yourviews instalado na sua loja vtexio, para isso, acesse o link abaixo para seguir com o passo a passo de instalação:  [https://github.com/yourviewsbyhiplatform/documentacoes/blob/master/Instalac%CC%A7a%CC%83o%20do%20App%20Yourviews%20na%20Vtex%20Io.md](https://github.com/yourviewsbyhiplatform/documentacoes/blob/master/Instalac%CC%A7a%CC%83o%20do%20App%20Yourviews%20na%20Vtex%20Io.md)

Ao seguir estes passos, você estará preparado para instalar e configurar o bloco na VTEX IO de maneira eficaz, aproveitando ao máximo as funcionalidades oferecidas.
 ## Instalação
 ### Nome do bloco
Conhecido como `yv-testimonials`, desempenha um papel crucial na experiência de compra online. Esse bloco é especificamente projetado para apresentar as avaliações e opiniões dos clientes sobre a loja, após a conclusão de uma compra. 
### Localização do bloco
O bloco de testemunhos é geralmente inserido no bloco pai da VTEX **store.home**, que normalmente corresponde à página home da loja.

    "yv-testimonials"

![Instalação do bloco Exemplo](https://i.imgur.com/9D2gnoQ.png)

Embora o bloco de testemunhos seja comumente inserido na página inicial isso não quer dizer que você obrigatoriamente deverá inseri-lo na página home do site, é apenas o usual. Fique a vontade para incluir o componente onde quiser.

### Exemplo
```diff
// home.jsonc
"store.home": {
    "blocks": [
      ...
     "yv-testimonials"
    ]
  },
```

### Finalização
**Pronto!**


O bloco dos testemunhos foi instalado com sucesso!
![Instalação do bloco Exemplo](https://i.imgur.com/uHUeqls.png)

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEzNzM4Njc3NDldfQ==
-->