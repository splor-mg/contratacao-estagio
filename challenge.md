## Resultado esperado:

* Um repositório git, hospedado no [GitHub](https://github.com/), com scripts e conjunto de dados gerados.
* Um vídeo curto (~2–3 minutos) apresentando seu repositório, explicando o que você fez, o que você não fez, o que funcionou e o que não funcionou. Por favor, utilize [https://loom.com/](https://loom.com/) ou um software similar. Gostaríamos de avaliar suas habilidades de apresentação, então manter a câmera ligada será uma vantagem.

## Desafio

* Escreva um script para obter um arquivo CSV normalizado e reproduzível com os dados de *Road Safety Facts and Figures* (Fatos e Números sobre Segurança Viária) na União Europeia.
* Inclua tanto o script quanto o conjunto de dados resultante.
* A documentação deve estar incluída no arquivo README.md e precisa ser clara e fácil de seguir.
* O repositório no [GitHub](https://github.com/) deve incluir as respostas a [estas perguntas](questionario.md).
* **Fique tranquilo(a)**, o mais importante será entender seu processo de desenvolvimento e não a finalização por completa de todas atividades aqui solicitadas.

## Mais detalhes:

* Utilize a seguinte página da Wikipedia [Road safety in Europe](https://en.wikipedia.org/wiki/Road_safety_in_Europe) e extraia os dados da tabela [European Union Road Safety Facts and Figures](https://en.wikipedia.org/wiki/Road_safety_in_Europe#:~:text=European%20Union%20Road%20Safety%20Facts%20and%20Figures).
* O arquivo CSV resultante deve incluir apenas as seguintes colunas: Country (País), Year (Ano), Area (Área), Population (População), GDP per capita (PIB per capita), Population density (Densidade populacional), Vehicle ownership (Propriedade de veículos), Total road deaths (Total de mortes no trânsito), Road deaths per Million Inhabitants (Mortes no trânsito por milhão de habitantes).
* Os dados devem estar ordenados pela coluna “Road deaths per Million Inhabitants”.
* Queremos ver o script criado para isso, e ele deve ser em Python, para que você possa demonstrar seu conhecimento nessa linguagem de programação.
* Seu repositório git deve incluir todas as dependências de forma padrão, para que possa ser executado em um ambiente de CI/CD.
* Por favor, utilize bibliotecas simples e nativas sempre que possível, em vez de frameworks.

## Itens bônus:

* Transforme seu repositório em um [Data package](https://datapackage.org/overview/introduction/) — aqui está um [breve guia](https://framework.frictionlessdata.io/docs/guides/describing-data.html).
* Construa um gráfico a partir dos dados para apresentar algum insight interessante. Fique à vontade para explorar a visualização.
* Certifique-se de que seu gráfico esteja publicado no GitHub Pages ou em outro local, para que possamos visualizá-lo.
