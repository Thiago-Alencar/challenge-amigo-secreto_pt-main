# Amigo Secreto (Secret Santa)

Uma aplicação web simples para sortear amigos secretos. Este projeto permite que usuários adicionem nomes de participantes e realizem sorteios aleatórios.

## Funcionalidades

- Adicionar participantes à lista
- Visualizar lista de participantes
- Realizar sorteio aleatório
- Interface responsiva e amigável

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla)
- Google Fonts (Inter e Merriweather)

## Como Executar

1. Clone este repositório:
```bash
git clone [URL-DO-REPOSITÓRIO]
```

2. Navegue até o diretório do projeto:
```bash
cd amigo-secreto
```

3. Abra o arquivo `index.html` em seu navegador preferido.

## Estrutura do Projeto

```
amigo-secreto/
├── assets/
│   ├── amigo-secreto.png
│   └── play_circle_outline.png
├── app.js
├── index.html
├── style.css
└── README.md
```

## Como Usar

1. Digite o nome de um participante no campo de texto
2. Clique em "Adicionar" para incluir o participante na lista
3. Repita o processo para adicionar todos os participantes
4. Clique em "Sortear amigo" para realizar o sorteio

## Validações

- Não é possível adicionar nomes vazios
- É necessário ter pelo menos um participante para realizar o sorteio

## Personalização

O projeto utiliza variáveis CSS para cores, permitindo fácil personalização. As principais variáveis estão definidas no início do arquivo `style.css`:

```css
:root {
    --color-primary: #4B69FD;
    --color-secondary: #FFF9EB;
    --color-tertiary: #C4C4C4;
    --color-button: #fe652b;
    --color-button-hover: #e55720;
    --color-text: #444444;
    --color-white: #FFFFFF;
}
```

## Contribuindo

Sinta-se à vontade para contribuir com este projeto. Algumas sugestões de melhorias:

1. Adicionar funcionalidade para remover participantes
2. Implementar persistência de dados (localStorage)
3. Adicionar animação no sorteio
4. Implementar sorteio completo de pares para amigo secreto

## Licença

Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.