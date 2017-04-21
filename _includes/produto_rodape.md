{% assign tel = site.data.empresa.tel[0] %}

## Para comprar este produto:

 <a href="#contato" data-btn="" onclick="ga('send', 'event', 'Contato', 'Abrir formulário', '{{ page.title }}');">Faça um pedido</a>

Ou pelo telefone: [{{ tel.title }}](tel:{{ tel.number }}).
