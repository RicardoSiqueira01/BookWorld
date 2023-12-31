# Especificação de Projeto

## Personas
### Maria Oliveira
![Maria Oliveira](https://github.com/RicardoSiqueira01/BookWorld/assets/106103247/82d675d6-2443-4b08-9feb-9f186488efc3)

Idade: 35 anos

Gênero: Feminino

Área de Ocupação: Professora

Gostos: Maria adora ler romances históricos e clássicos. Ela também aprecia poesia e literatura contemporânea.

Por que quer um site como o BookWorld: Maria deseja um site como o BookWorld para descobrir novas obras literárias dentro de seus gêneros favoritos e compartilhar suas recomendações com outros leitores. Ela busca uma plataforma onde possa participar de discussões significativas sobre livros e conhecer pessoas com gostos semelhantes.

Frustrações com outros sites: Maria fica frustrada com sites que não oferecem recomendações personalizadas ou que não possuem uma comunidade ativa de leitores. Ela também acha difícil encontrar uma plataforma onde possa interagir com outros leitores de forma fácil e envolvente.

Motivação: Maria está motivada a utilizar o BookWorld para expandir sua biblioteca pessoal, descobrir novos autores e encontrar pessoas com quem possa compartilhar sua paixão pela literatura.

### Ana Silva
![Ana Silva](https://github.com/RicardoSiqueira01/BookWorld/assets/106103247/2f1ae8e7-8b7d-4b57-a5b5-50e6d693085a)

Idade: 22 anos

Gênero: Feminino

Área de Ocupação: Estudante universitária

Gostos: Ana adora ler livros de suspense e mistério. Ela também gosta de explorar romances contemporâneos e livros de não-ficção relacionados à psicologia.

Por que quer um site como o BookWorld: Ana deseja um site como o BookWorld para encontrar novos livros de suspense e mistério que ainda não conhece. Ela busca uma plataforma onde possa participar de discussões animadas sobre seus livros favoritos e compartilhar suas descobertas literárias com outros leitores. Além disso, Ana quer ter acesso a resenhas e recomendações confiáveis para tomar decisões informadas sobre suas próximas leituras.

Frustrações com outros sites: Ana se frustra com sites que não fornecem recomendações personalizadas de acordo com seus gostos específicos. Ela também acha difícil encontrar um espaço online onde possa interagir com outros leitores e receber sugestões relevantes para seus interesses. Além disso, a falta de análises detalhadas e opiniões dos leitores a deixa insegura ao escolher novos livros para ler.

Motivação: A motivação de Ana é utilizar o BookWorld para ampliar seu repertório de livros de suspense e mistério, descobrir novos autores nesse gênero, compartilhar suas opiniões sobre suas leituras e encontrar recomendações personalizadas que atendam aos seus gostos específicos. Ela também está motivada a se conectar com outros leitores apaixonados por esses gêneros, trocar ideias e participar de discussões envolventes sobre os livros que mais gosta.

### André Costa
![André Costa](https://github.com/RicardoSiqueira01/BookWorld/assets/106103247/0bc50d24-e305-486b-b978-ca4b59ee584c)

Idade: 45 anos

Gênero: Masculino

Área de Ocupação: Executivo de Vendas

Gostos: André aprecia livros de negócios, desenvolvimento pessoal e biografias de líderes empresariais.

Por que quer um site como o BookWorld: André busca um site como o BookWorld para expandir seu conhecimento e aprimorar suas habilidades profissionais. Ele deseja encontrar recomendações de livros relevantes para sua área de atuação e ter a oportunidade de se conectar com outros profissionais interessados em desenvolvimento de carreira.

Frustrações com outros sites: André fica frustrado com sites que têm poucas opções de busca para livros de negócios e que não possuem uma comunidade ativa de leitores voltados para o mundo corporativo. Ele também não gosta de plataformas que não oferecem análises detalhadas e avaliações de livros relevantes para suas necessidades profissionais.

Motivação: A motivação de André é utilizar o BookWorld para encontrar livros que o ajudem a se destacar em sua área profissional, trocar experiências com outros executivos e se manter atualizado com as últimas tendências do mundo dos negócios.

## Histórias de Usuários
|EU COMO (PERSONA)|QUERO/PRECISO...(FUNCIONALIDADE)|PARA...(MOTIVO/VALOR)|
| --- | --- | --- |
|Maria Oliveira|Maria Oliveira deseja uma interface intuitiva e fácil de usar no BookWorld. Ela quer um design limpo e organizado, com uma barra de pesquisa proeminente para que possa encontrar rapidamente livros de seu interesse.|Facilitar a utilização|
|Maria Oliveira|Maria também valoriza a presença de filtros de pesquisa avançados, permitindo que ela refine sua busca por gênero, autor e avaliações dos leitores.|Para facilitar suas pesquisas de livros|
|Maria Oliveira|Além disso, ela gostaria de ver recomendações personalizadas na página inicial, com base em seus interesses e histórico de leitura.|Para o site ser mais eficiente e mostrar o que quero ver|
|Maria Oliveira|Quero que o BookWorld forneça avaliações confiáveis e análises aprofundadas para ajudá-la a tomar decisões informadas.|O motivo é garantir que cada leitura seja uma experiência enriquecedora e satisfatória, selecionando livros de alta qualidade e evitando decepções literárias.|
|André Costa|Ele busca um layout responsivo que seja otimizado para uso em dispositivos móveis, permitindo que ele acesse o site facilmente em seu smartphone durante suas viagens de negócios.|Para utilizar o site onde e quando quiser|
|André Costa|Ele gostaria de ter a opção de salvar seus livros favoritos em uma lista de leitura.|Para eu acessar com mais velocidade os meus livros|
|Ana Silva|Ela busca uma estrutura clara de categorias e subcategorias, para que possa explorar diferentes gêneros literários de forma rápida e intuitiva. |Facilitar a navegação.|
|Ana Silva|Valorizo uma página de detalhes do livro que apresente sinopses, informações sobre o autor e avaliações dos leitores.|Para obter mais informações sobre o livro que tive interesse.|

## Requisitos
### Requisitos Funcionais 
|ID|Descrição do Requisito|PRIORIDADE|
| --- | --- | --- |
|RF-001|Recomendações de livros na página inicial, com base em: preferências de gêneros e autores favoritos|Alta|
|RF-002|Deve haver um mecanismo de pesquisa de livros na homepage.|Alta|
|RF-004|Um filtro de pesquisa com: gênero, autor e avaliações dos leitores|Média|
|RF-005|Deve haver um espaço para que os leitores avaliem os livros e escrevam suas análises|Média|
|RF-006|Salvar os livros favoritos|Médio|

### Requisitos Não-Funcionais
|ID|Descrição do Requisito|PRIORIDADE|
| --- | --- | --- |
|RNF-001|Uma interface intuitiva com design limpo e organizado, que seja responsiva para aparelhos móveis|Alta|
|RNF-002|O site deve ser publicado em um ambiente acessível publicamente na Internet (Repl.it, GitHub Pages, Heroku)|Alta|
|RNF-003|O site deve ter bom nível de contraste entre os elementos da tela em conformidade|Média|
|RNF-004|O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Microsoft Edge)|Alta|

## Restrições
|ID|Restrição|
| --- | --- |
|RE-001|O aplicativo deve se restringir às tecnologias básicas da Web no Backend|

## Diagrama de Casos de Uso
![Caso de uso BookWorld](https://github.com/RicardoSiqueira01/BookWorld/assets/106103247/a8ecd423-adb9-4a50-ad74-8165389c3dee)
