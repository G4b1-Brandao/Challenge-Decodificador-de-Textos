# Decodificador de Textos

Este é um projeto simples de um decodificador de textos que permite criptografar e descriptografar mensagens usando uma chave específica. O projeto é construído com HTML, CSS e JavaScript.
Link do projeto: https://g4b1-brandao.github.io/Challenge-Decodificador-de-Textos/
## Funcionalidades

- **Criptografar**: Transforma um texto normal em um texto criptografado.
- **Descriptografar**: Transforma um texto criptografado de volta ao texto original.
- **Copiar Texto**: Permite copiar o texto resultante para a área de transferência.
- **Tema Claro/Escuro**: Alterna entre os modos de tema claro e escuro.
- **Aviso**: Exibe um aviso para informar que apenas letras minúsculas e sem acentos são permitidas.

## Estrutura do Projeto

- **HTML**: Estrutura básica da página web.
- **CSS**: Estilização da página, incluindo temas claro e escuro.
- **JavaScript**: Funções para criptografar, descriptografar, copiar texto e alternar temas.

## Como Usar

1. **Clonar o Repositório**: Clone o repositório para o seu ambiente local.
    ```sh
    git clone https://github.com/G4b1-Brandao/Challenge-Decodificador-de-Textos.git
    ```

2. **Abrir o Arquivo `index.html`**: Abra o arquivo `index.html` em seu navegador.

3. **Usar o Decodificador**:
    - Digite o texto que deseja criptografar ou descriptografar na área de texto.
    - Clique no botão "Criptografar" para transformar o texto em um formato criptografado.
    - Clique no botão "Descriptografar" para retornar o texto ao seu formato original.
    - Clique no botão "Copiar" para copiar o texto resultante para a área de transferência.

4. **Alternar Tema**:
    - Clique no botão com o ícone de lua para alternar entre os modos de tema claro e escuro.

## Tecnologias Utilizadas

- HTML
- CSS
- JavaScript

## Estrutura de Arquivos

```
decodificador-de-textos/
│
├── assets/
│   ├── images/
│   │   ├── logo-alura.png
│   │   ├── moon-color.png
│   │   └── Ruido.png
│
├── styles.css
├── script.js
└── index.html
```

## Estilo CSS Personalizado

```css
body.dark {
    --background-gradient: linear-gradient(#1354A5 0%, #041832 33.33%, #041832 66.67%, #01080E 100%);
    --text-color: white;
    --button-background: #1875E8;
    --button-hover-background: #1354A5;
    --input-background: #FFF;
    --input-text-color: #1875E8;
    --alerta-color: #FFD700;
}

body.light {
    --background-gradient: linear-gradient(#FFF 0%, #DDD 100%);
    --text-color: black;
    --button-background: #007BFF;
    --button-hover-background: #0056b3;
    --input-background: #EEE;
    --input-text-color: #333;
    --alerta-color: #B22222;
}
```

## Contribuição

Se você deseja contribuir com o projeto, sinta-se à vontade para fazer um fork do repositório e enviar um pull request com suas alterações. Todas as contribuições são bem-vindas!

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

![image](https://github.com/user-attachments/assets/e7be1da4-afa8-4aa8-b6ee-57fcdade0de0)
