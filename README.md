# Exercicios_Enum
1) Desenvolva um programa para definir diferentes tipos de disciplinas que são oferecidos para uma turma, garanta que somente tipos definidos sejam utilizados no cadastro de disciplinas. 

 Para tanto, crie uma enumeração chamada "TipoDisciplina" e adicione a ela as constantes que representam os diferentes tipos de disciplinas oferecidas pela escola, como "FPOO", "REDES", "SO", "LM", bem como suas respectivas descrições.

 Escreva uma classe chamada Disciplina a qual possui os atributos periodo, e tipo, implemente os gets e sets necessários bem como um construtor para os atributos das classe. Crie também a classe CadastroDisciplinas a qual possui um ArrayList de Disciplinas.
 Faça os métdos CadastrarDisciplina, RemoverDisciplina, ListarDisciplina.

 Por fim faça uma classe para testar as implementações feitas acima. 
 
------

2) Desenvolva um programa em Java para definir diferentes tipos de livros que são oferecidos em uma biblioteca, garantindo que somente tipos definidos sejam utilizados no cadastro de livros. Assim, escreva uma enumeração (Enum) chamada "TipoLivro" e adicione a ela as constantes que representam os diferentes tipos de livros oferecidos pela biblioteca, como "ROMANCE", "FICCAO_CIENTÍFICA", "AVENTURA", "TUTORIAL", etc.

 Em seguida, utilize tal enumeração para garantir que apenas os tipos de livros definidos sejam utilizados no cadastro de livros. Por exemplo, você pode criar um método na classe de cadastro de livros que recebe como parâmetro um TipoLivro e verificar se ele está entre os tipos de livros oferecidos pela biblioteca antes de realizar o cadastro.

  Além disso, utilize um o ArrayList para armazenar os livros cadastrados na biblioteca. Crie uma classe Livro que tenha atributos como título, autor, editora, ano de publicação, tipo (do tipo TipoLivro) e quantidade de exemplares disponíveis. Em seguida, crie uma classe para gerenciar o acervo da biblioteca, adicionando métodos para cadastrar novos livros, verificar se um livro está disponível, emprestar um livro e devolver um livro.

Ao utilizar a enumeração e o ArrayList, você torna mais fácil a busca e filtragem das informações no sistema, permitindo, por exemplo, que o usuário busque todos os livros de um determinado tipo ou que verifique quais livros estão disponíveis para empréstimo.

Ao fim faça uma classe para testar a implementação desenvolvida.

