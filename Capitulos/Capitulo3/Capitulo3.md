<p align="left">(<a href="../../README.md">readme</a>)</p>
<h1 align=center>CAPÍTULO 3</h1>
<h2 align=center>Entendendo Todas as Linguagens para a Entrega do Front-End</h2>

Markdown utilizado para tirar notas dos conteúdos.

---

## TAGS

É possível aninhação! (colocar uma tag dentro da outra)

### Tags Padrão

- Headers
  - **&lt;h1&gt;** | **&lt;h2&gt;** | **&lt;h3&gt;** | **&lt;h4&gt;** | **&lt;h5&gt;** | **&lt;h6&gt;**
    - Há hierarquia, a ordem vai importar, principalmente para os bots de busca
- Parágrafo
  - **&lt;p&gt;**
    - Tag para inserção de parágrafos
- Linha Horizontal
  - **&lt;hr&gt;**
    - Tag para criação de uma nova linha horizontal
- Quebra de Linha
  - **&lt;br&gt;**
    - Tag para quebrar as linhas dos parágrafos
    - Assim que o navegador encontrar esse elemento, o que estiver à direita dele será exibido na linha abaixo
    - O uso vicioso delenão é uma boa prática

### Tags para Formatação de Texto

- Negrito
  - **&lt;b&gt;**
    - 'b' de 'bold'
- Negrito Semântico
  - **&lt;strong&gt;**
    - Tag para aplicar negrito juntamente de um valor semântico (adiciona valor perante as search engines)
- Itálico
  - **&lt;i&gt;**
    - 'i' de 'italic'
- Sublinhado
  - **&lt;u&gt;**
    - Tag 'u' para sublinhar

### Tags para Mídia

- Imagem
  - **&lt;img&gt;**
    - Permite informar, através de atributos, uma imagem para ser incluída
    - ***src*** - Indica o caminho da imagem
    - ***alt*** - Insere um pequeno texto que descreve a imagem e será exibida caso o arquivo não seja mostrado correramente pelo navegador. Ajuda também para pessoas que têm algum tipo de deficiência visual
    - ***title*** - É o texto que será exibido assim que o ponteiro do mouse repousar sobre a imagem. Não é exclusivo do **&lt;img&gt;**, praticamente todos os elementos do HTML podem usar
