# Horário do Dia ☀️🌙

Atividade de estudo com HTML, CSS e JavaScript que exibe uma mensagem de horário e muda a imagem e a cor de fundo conforme o período do dia.

Exercício desenvolvido a partir das aulas de JavaScript do **Curso em Vídeo**, com ilustrações para manhã, tarde e noite.

## Ilustrações

| Manhã | Tarde | Noite |
| :---: | :---: | :---: |
| <img src="fotomanha.png" alt="Ilustração da manhã" width="220"> | <img src="fototarde.png" alt="Ilustração da tarde" width="220"> | <img src="fotonoite.png" alt="Ilustração da noite" width="220"> |

## Como funciona

Ao carregar a página, a função `carregar()` exibe a hora local do dispositivo e seleciona o visual correspondente:

- **Manhã:** das 0h às 11h.
- **Tarde:** das 12h às 17h.
- **Noite:** a partir das 18h.

A hora local é consultada ao abrir a página. Recarregue para atualizar o horário. O layout se adapta à largura da tela e as imagens têm largura máxima de 300 pixels.

## Tecnologias e conceitos praticados

- **HTML5:** estrutura da página.
- **CSS3:** cores, alinhamento, bordas e sombras.
- **JavaScript:** funções, condições (`if` e `else`), manipulação do DOM e objeto `Date`.

## Acesse o site

[Ver o exercício Horário do Dia](https://barbarasoaress.github.io/atividade-horario/)

## Como executar

1. Baixe o repositório em **Code → Download ZIP** e extraia os arquivos, ou clone-o:

   ```bash
   git clone https://github.com/barbarasoaress/atividade-horario.git
   ```

2. Abra o arquivo `index.html` no navegador.

Não é necessário instalar dependências. Mantenha o HTML, o CSS, o JavaScript e as imagens na mesma pasta.

## Arquivos

| Arquivo | Função |
| --- | --- |
| `index.html` | Página principal do exercício |
| `estilo.css` | Estilos da página |
| `script.js` | Lógica dos períodos do dia |
| `fotomanha.png` | Imagem da manhã |
| `fototarde.png` | Imagem da tarde |
| `fotonoite.png` | Imagem da noite |

## Créditos

Atividade realizada por [Bárbara Soares](https://github.com/barbarasoaress), com base no exercício do **Curso em Vídeo**. Ilustrações geradas com auxílio de inteligência artificial.
