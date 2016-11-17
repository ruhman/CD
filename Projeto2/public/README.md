
## Currículo
Esse projeto foi criado pelo Marcelo Terreiro Prado para a disciplina de Co-Design de Aplicativos e está aberto a sugestões e modificações.

**Preview**: [inserir link]

*Esse projeto é baseado no https://github.com/blackrockdigital/startbootstrap-creative*

---

### Getting Started
Você precisará realizar alguns passos para começar a montar o seu currículo.

1. Instalar Node.JS - essa ferramenta permitirá que instale as dependências necessárias para rodar o projeto.

  * Se tiver Mac ou Linux, siga esse vídeo: https://docs.npmjs.com/getting-started/installing-node.
  * Caso possua Windows, baixe por aqui: https://nodejs.org/en/download/

2. Clone esse repositório ou baixe em ZIP pelo Github: https://github.com/MarceloPrado/CoDesignCurriculo/.
3. Pelo terminal, navegue até o diretório baixado e execute o seguite comando: ``` npm install ```
    * Caso encontre algum erro, pesquise no Google e solucione-o.
4. Depois de executar com sucesso o terceiro passo, execute o seguinte comando, dentro do diretório baixado/clonado: ```gulp```

---

### Modifique à vontade
O currículo foi projetado para ser de qualquer pessoa. Para modificá-lo, siga as dicas abaixo. ** O código está bem comentado! ** Por isso, é só ir com calma, modificando aquilo que deseja.

**Para alterar a foto que fica debaixo do nome:**

 Abra o arquivo *style.less* e encontre o seletor ```header```. Altere a propriedade ```background-image``` para a que deseja.

**Para alterar os ícones:**
* Encontre um ícone aqui: http://fontawesome.io/icons/
  * Substitua o nome do ícone pelo encontrado. Exemplo: ```<i class="fa fa-4x fa-code text-primary sr-icons"></i>``` para ```<i class="fa fa-4x fa-bank text-primary sr-icons"></i>.```. Isso substituiria o ícone do código por um ícone de um banco.

**Para modificar as fotos do Portfolio:**

**Importante:** cada projeto tem que ter pelo menos duas fotos: foto *box* e foto *header*
1. **Foto box**: exporte uma foto no tamanho 650x350. Essa foto será usada na página inicial do seu curículo, naquele retângulo que fica colorido ao colocar o mouse em cima.
1. **Foto header**: essa é a foto principal do projeto que aparecerá na página dele.

**Para alterar as cores:**

 Abra o arquivo *variables.less* e troque as cores. Para outros objetos, troque as cores manualmente no arquivo *style.less*.

**Para adicionar um novo trabalho no portfolio:**

1. Copie o código do arquivo ```projeto.html``` para um novo arquivo html.
  * Faça as modificações que desejar
2. Procure pela seção ```portfolio```. Copie um bloco de código de um trabalho e altere para as informações do seu novo trabalho.
---
