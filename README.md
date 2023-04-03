## ✨ Projeto desenvolvido para estudo do HTML 5, promovido pelo programa START da Capgemini e elaborado pela ProWay ✨

🗒️Dicionário de tags

📌 Estruturais e semânticas:

   • < html > : É a tag raiz de um documento HTML. Ela é usada para identificar o início e o fim do documento HTML e tudo o que está contido no documento deve estar dentro dessa tag. 

   • < head > : Identifica a seção do cabeçalho de uma página HTML, fora do < body >. Ele contém informações não visíveis para os usuários, como metadados, links para arquivos CSS e JavaScript, o título da página e etc. É uma seção obrigatória em qualquer página HTML e não deve conter conteúdo visível.

   • < body > : Referente a seção do corpo do conteúdo de uma página HTML. Ele contém todo o conteúdo visível na página, como texto, imagens, vídeos, formulários e outras informações que os usuários podem interagir. Tudo o que é exibido na página da web é colocado dentro dessa tag.

   • < main > : É usada para identificar a seção principal do conteúdo de uma página HTML. Ela geralmente engloba todo o conteúdo da página, exceto o cabeçalho (header), rodapé (footer) e navegação (nav).

   • < header > : Utilizada para identificar o cabeçalho de uma página HTML,geralmente uma seção do conteúdo. Ele pode conter o logotipo do site, o nome do site e elementos de navegação. É usado para separar visualmente a seção do conteúdo principal da página. É uma seção opcional e seu conteúdo é visível para os usuários.

   • < article > : É uma tag usada para identificar um conteúdo independente e autônomo em uma página HTML. Pode ser uma postagem de blog, notícia, artigo ou qualquer outro conteúdo que possa ser publicado ou distribuído separadamente. De uma maneira simples(para iniciantes), "tudo que for repetitivo e tiver contexto/significado próprio, utiliza-se article."

   • < nav > : Essa rag identifica uma seção de navegação de uma página HTML. Ele geralmente contém links para outras páginas do site ou seções da página atual. Elementos dentro dessa tag não são reconhecidos pelos mecanismos de busca do google.

   • < aside > : Identifica o conteúdo relacionado, mas não essencial, a uma página HTML. Ele geralmente contém informações adicionais ou links para outras páginas relacionadas. Muito utilizado para anexar propagandas ao site. 

   • < div > : É usada para agrupar elementos em uma seção de conteúdo comum e fornecer uma maneira de estilizar e manipular o conteúdo em conjunto. Ela não possui um significado próprio e é frequentemente usada como um contêiner genérico em HTML, ou seja, um bloco de conteúdo É uma tag estrutural e deve ser usada com menor frequência, por não possuir significado semântico.

   • < span > : Identifica pequenos trechos de texto dentro de uma página HTML que podem precisar de estilo ou manipulação em JavaScript. Ele não tem um efeito visual padrão, mas pode ser estilizado usando CSS. 

   • < footer > : Usada para identificar o rodapé de uma página HTML. Ele geralmente contém informações de contato, direitos autorais e links para outras páginas do site. É usado para separar visualmente a seção do conteúdo principal da página.

   • < section > : É uma tag usada para identificar uma seção de conteúdo tematicamente relacionada em uma página HTML. Ele é usado para dividir o conteúdo em seções significativas e pode ser usado dentro de um elemento < article > ou < main >.

   • < br/ > : Tag de quebra de linha em HTML. Não requer uma tag de fechamento.

📌 Cabeçalho e marcação:

   • < h1 >, < h2 >, < h3 >, < h4 >, < h5 >, < h6 > : São utilizadas para definir os títulos e subtítulos em uma página HTML, sendo que o < h1 > é o título principal e os demais são títulos e subtítulos secundários, em ordem decrescente de importância. É importante ter dentro da < section > e do < article >.
  
   • < br /> : A tag é usada para inserir uma quebra de linha em um documento HTML. É uma tag vazia, ou seja, não tem um elemento de fechamento correspondente, e é frequentemente usada para separar linhas de texto, ou para inserir um espaço vertical em uma página da web.

📌 Link:

   • < a > : É usada para criar um link ou hiperlink em uma página da web. Ela permite que você crie um link para outra página da web, para um arquivo em seu próprio site ou para uma seção diferente da mesma página.

📌 Lista:
   
   • < ol > : É utilizada para criar uma lista ordenada, ou seja, uma lista que tem itens numerados. Dentro da tag < ol >, você pode criar quantas tags < li > quiser para adicionar itens à lista. 

   • < ul > : A tag < ul > é usada para criar uma lista não ordenada, ou seja, uma lista que tem itens que não são numerados. Assim como na tag < ol >, os itens são criados usando a tag < li >. 

   • < li > : É usada para definir cada item da lista, seja ela ordenada ou não. Pode conter qualquer conteúdo HTML, como texto, imagens, links e outras tags HTML.

📌 Tabelas, Mesas e outros:

   • < table > : É usada para criar a estrutura básica da tabela. Dentro dessa tag, você precisa definir outras tags que irão compor a tabela, como < thead >, < tbody >, e < tfoot >.

   • < caption > : É utilizada para adicionar um título ou legenda à tabela. Essa tag deve ser colocada logo após a tag de abertura da tabela.

   • < tbody > : A tag < tbody > é usada para definir o corpo da tabela, ou seja, onde as linhas e células da tabela são definidas. Essa tag pode ser usada várias vezes, se você quiser dividir a tabela em várias seções. 

   • < tr > : A tag é usada para definir uma linha na tabela. Dentro dessa tag, você precisa definir as células da linha usando a tag < td > ou a tag < th >, que são explicadas abaixo. 

   • < td > : É usada para definir uma célula na tabela. Essa tag deve ser usada dentro da tag < tr >.

   • < th > : Utilizada para definir um cabeçalho de coluna na tabela. Essa tag deve ser usada dentro da tag < tr > e dentro da tag < thead >.

   • < thead > : É usada para definir o cabeçalho da tabela, ou seja, a parte superior da tabela que contém informações importantes, como títulos de colunas. É importante notar que a tag só pode ser usada apenas uma vez em cada tabela.

   • < tfoot > : Utilizada para definir o rodapé da tabela, ou seja, a parte inferior da tabela que contém informações adicionais, como totais ou notas. É importante notar que a tag só pode ser usada apenas uma vez em cada tabela.

📌 Para arquivos:

   • < img/ > : É usada para incluir imagens em uma página web. A tag é auto-fechada. 

   • < figure > : A tag é usada para agrupar elementos, como imagens, gráficos, ilustrações e diagramas, para que possam ser referenciados como uma unidade, destacando-os no conteúdo.

   • < figcaption > : : A tag é usada dentro da tag < figure > para adicionar uma legenda à figura. 

   • < picture > : É usada para fornecer várias fontes de imagem para um elemento < img > dependendo da resolução da tela do dispositivo que está sendo usado para visualizar a página. Essa tag é usada juntamente com a tag < source >.

   • < source > : Utilizada dentro da tag < picture > para fornecer várias fontes de imagem para um elemento < img >. É possível fornecer várias fontes de imagem em diferentes formatos e resoluções e o navegador selecionará automaticamente a fonte de imagem adequada com base na resolução da tela do dispositivo que está sendo usado para visualizar a página.

📌 Para formulário:

   • < form > : A tag é usada para criar formulários em uma página da web, agrupando elementos interativos de entrada de dados e definindo um meio para enviá-los ao servidor para processamento. Ela tem vários atributos que especificam como os dados do formulário são enviados e para onde são enviados.
   
      · method GET e POST : O atributo "method" é usado para especificar o método HTTP que será usado para enviar os dados do formulário ao servidor. Existem dois métodos principais suportados pelo atributo "method": "GET" e "POST".  
         → GET: É usado para enviar os dados do formulário como uma string de consulta anexada à URL da página. Isso significa que os dados são visíveis na barra de endereço do navegador e podem ser armazenados em caches de histórico e de navegação. O método GET é comumente usado para pesquisas e para solicitações de leitura de dados.
         → POST: É usado para enviar os dados do formulário no corpo da solicitação HTTP, que não é visível na barra de endereço do navegador. Isso torna o método POST mais seguro para enviar dados confidenciais, como senhas e informações de cartão de crédito. O método POST é comumente usado para submissões de formulário que alteram o estado do servidor, como criação de conta ou envio de informações de pagamento.
      · action : Atributo usado para especificar a URL do servidor que processará os dados do formulário quando ele for enviado.

   • < input /> :  É usada para criar campos de entrada de dados em um formulário HTML.

      · type: Especifica o tipo de campo de entrada.
      · value: Especifica o valor padrão do campo de entrada, como texto, senha, checkbox, etc.
      · name: Especifica o nome do campo de entrada, que é usado para identificar o campo quando os dados do formulário são enviados para o servidor.
      · placeholder: Especifica uma mensagem de orientação para os usuários

   • < textarea > : Utilizada para criar campos de texto de várias linhas em um formulário HTML. Ela permite que os usuários digitam textos mais longos, como comentários ou mensagens.

   • < select > : A tag < select > é usada para criar uma lista de opções em um formulário HTML, permitindo que os usuários escolham uma ou várias opções em uma lista suspensa. Ela é geralmente usada em conjunto com a tag < option >.

   • < option > : É usada em conjunto com a tag < select > para definir uma opção em uma lista suspensa.

   • < datalist > : A tag < datalist > é usada para fornecer uma lista de sugestões para um campo de entrada de texto, geralmente usado em conjunto com a tag < input > e o atributo "list". Ela fornece uma lista de opções para o usuário escolher enquanto digita no campo de entrada.

   • < button > : É usada para criar um botão em um formulário HTML, permitindo que os usuários acionem ações como enviar um formulário, limpar um campo de entrada ou executar um script JavaScript. O atributo "type" pode ser usado para especificar o tipo de botão, como "submit", "reset" ou "button".

   ❤