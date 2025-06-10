# revisaoProvaM2

## 🧪 Questões
---
### QUESTÃO 1 – Modelagem de Dados Relacional
Considere um sistema universitário que registra cursos, alunos e suas respectivas matrículas. O sistema deve garantir que cada aluno possa se matricular em múltiplas disciplinas, mas uma mesma disciplina também pode ter vários alunos. Além disso, cada disciplina é oferecida por um único professor. O banco de dados relacional deve ser projetado para manter a integridade referencial e evitar redundância de dados.

I. O relacionamento entre alunos e disciplinas deve ser representado por uma tabela associativa contendo chaves estrangeiras de ambas as tabelas.<br>
II. A entidade professor deve possuir chave primária que é referenciada na tabela de disciplinas.<br>
III. Uma disciplina pode ser associada a múltiplos professores, o que justifica a criação de uma tabela adicional.<br>
IV. O uso de constraints como FOREIGN KEY garante que registros referenciados existam nas tabelas originais.<br>

É correto o que se afirma em:<br>
```A) I, II e IV, apenas.```<br>
B) I e III, apenas.<br>
C) II, III e IV, apenas.<br>
D) I, II e III, apenas.<br>
E) Todas as afirmativas estão corretas.<br>

---
### QUESTÃO 2 – Arquitetura Cliente-Servidor com MVC
No desenvolvimento de uma aplicação web baseada em Node.js e Express, o time de desenvolvimento decidiu adotar o padrão arquitetural MVC. A aplicação deve permitir que o cliente interaja via navegador, enviando requisições HTTP para o servidor, que responderá com páginas dinâmicas.

I. O Controller processa requisições e repassa dados para o Model, retornando a resposta ao cliente.<br>
II. O Model interage com a View diretamente para exibir os dados processados.<br>
III. A View representa a saída visual da aplicação e é gerada a partir das informações processadas pelo Controller.<br>
IV. Separar lógica de negócio e interface facilita a manutenção e reuso de código.<br>

É correto o que se afirma em:<br>
```A) I, III e IV, apenas.```<br>
B) I e II, apenas.<br>
C) III e IV, apenas.<br>
D) II, III e IV, apenas.<br>
E) Todas as afirmativas estão corretas.<br>

---
### QUESTÃO 3 – Banco de Dados Não Relacionais
Uma startup desenvolvendo uma aplicação de redes sociais decidiu utilizar um banco de dados do tipo NoSQL para armazenar informações de perfis de usuários, postagens e relações de amizade. A escolha se deu pela flexibilidade de estrutura e pela necessidade de escalar horizontalmente a aplicação com facilidade.

I. Bancos de dados orientados a documentos são ideais para armazenar dados com estrutura variável, como perfis de usuário.<br>
II. Bancos do tipo grafo são adequados para representar relações como "amizade" entre usuários.<br>
III. A consistência eventual é uma característica típica dos bancos NoSQL, diferente dos bancos relacionais.<br>
IV. Em um banco do tipo chave-valor, cada registro precisa estar normalizado em três formas normais.<br>

É correto o que se afirma em:<br>
```A) I, II e III, apenas.```<br>
B) I e IV, apenas.<br>
C) II e III, apenas.<br>
D) I, III e IV, apenas.<br>
E) Todas as afirmativas estão corretas.<br>

---
### QUESTÃO 4 – Requisições Assíncronas com Controllers
Em uma aplicação que utiliza o framework Express.js, o aluno foi encarregado de implementar a lógica do backend. O sistema recebe requisições assíncronas do frontend utilizando a Fetch API e responde com dados obtidos de um banco PostgreSQL. A lógica de cada rota é implementada em controladores assíncronos.

I. O uso de async/await facilita a leitura de código assíncrono em JavaScript.<br>
II. Requisições POST e DELETE podem ser tratadas no mesmo controller desde que a rota esteja definida corretamente.<br>
III. Controllers devem concentrar a lógica de negócio e persistência para simplificar o projeto.<br>
IV. As funções assíncronas exigem tratamento de erros com try/catch para evitar travamentos na aplicação.<br>

É correto o que se afirma em:<br>
```A) I, II e IV, apenas.```<br>
B) II e III, apenas.<br>
C) I, III e IV, apenas.<br>
D) I, II e III, apenas.<br>
E) Todas as afirmativas estão corretas.<br>

---
### QUESTÃO 5 – Anatomia de uma Aplicação em Camadas
Um grupo de desenvolvedores está projetando uma aplicação web corporativa e decidiu utilizar uma arquitetura em camadas para garantir a manutenibilidade e a escalabilidade do sistema. O sistema será dividido entre a camada de apresentação (frontend), a camada de negócios (backend) e a camada de dados (banco de dados). Cada camada terá responsabilidades bem definidas.

I. A camada de apresentação é responsável por interagir com o usuário, exibindo informações e coletando entradas.<br>
II. A camada de negócios aplica as regras funcionais e validações, separando-se da interface e da lógica de persistência.<br>
III. A camada de dados deve encapsular o acesso ao banco, impedindo o acesso direto por outras camadas.<br>
IV. A ausência de camadas intermediárias favorece o acoplamento e reduz a reutilização de componentes.<br>

É correto o que se afirma em:<br>
```A) I, II e III, apenas.```<br>
B) II, III e IV, apenas.<br>
C) I, III e IV, apenas.<br>
D) I, II e IV, apenas.<br>
E) Todas as afirmativas estão corretas.<br>

---
### QUESTÃO 6 – Paradigmas de Programação
Durante uma aula sobre linguagens de programação, foram apresentados diversos paradigmas, como o imperativo, o funcional e o orientado a objetos. Cada paradigma adota uma forma distinta de modelar o comportamento do sistema e manipular os dados.

I. A programação funcional preza pela imutabilidade de dados e evita efeitos colaterais.<br>
II. O paradigma orientado a objetos favorece o encapsulamento e reutilização por meio de herança.<br>
III. A programação imperativa descreve a lógica do programa por meio de comandos sequenciais.<br>
IV. No paradigma funcional, o uso de loops tradicionais como for e while é incentivado em detrimento de funções como map e reduce.<br>

É correto o que se afirma em:<br>
```A) I, II e III, apenas.```<br>
B) II e IV, apenas.<br>
C) I, III e IV, apenas.<br>
D) I, II e IV, apenas.<br>
E) Todas as afirmativas estão corretas.<br>

---
### QUESTÃO 7 – Setup de Ambiente com Node.js, VSCode e Supabase
Ao iniciar o desenvolvimento de um projeto fullstack, uma equipe de estudantes realizou a instalação do Node.js, configurou o editor VSCode com extensões úteis, e utilizou o Supabase como backend. O objetivo era integrar de forma eficiente o frontend com um banco relacional escalável.

I. O VSCode oferece terminal integrado, sugestões automáticas de código e controle de versão integrado.<br>
II. O comando npm install express é utilizado para adicionar o framework Express a um projeto Node.js.<br>
III. O Supabase fornece serviços de autenticação e banco de dados prontos para uso com suporte a SQL.<br>
IV. Após inicializar um projeto Node com npm init -y, não é necessário criar manualmente o package.json.<br>

É correto o que se afirma em:<br>
A) I, II e IV, apenas.<br>
B) I, II e III, apenas.<br>
C) II, III e IV, apenas.<br>
D) I, III e IV, apenas.<br>
```E) Todas as afirmativas estão corretas.```<br>

---
### QUESTÃO 8 – Chave Primária e Estrangeira
Em uma base de dados relacional, o uso adequado de chaves primárias e estrangeiras é essencial para manter a integridade dos dados e garantir que os relacionamentos entre as tabelas sejam consistentes. Um analista júnior precisa revisar o modelo lógico antes da implementação.

I. Uma chave primária identifica unicamente cada linha da tabela e não aceita valores nulos.<br>
II. Uma chave estrangeira estabelece um vínculo entre duas tabelas e pode ter valores nulos em alguns casos.<br>
III. O uso de chaves estrangeiras ajuda a evitar inserções de dados inválidos em colunas que dependem de outras tabelas.<br>
IV. Uma tabela pode conter múltiplas chaves primárias, desde que em colunas diferentes.<br>

É correto o que se afirma em:<br>
```A) I, II e III, apenas.```<br>
B) I e IV, apenas.<br>
C) II e III, apenas.<br>
D) I, III e IV, apenas.<br>
E) Todas as afirmativas estão corretas.<br>

---
### QUESTÃO 9 – Introdução ao Padrão MVC
O padrão de arquitetura MVC visa organizar o código de uma aplicação em três camadas: Model, View e Controller. Essa separação permite dividir tarefas de forma clara, além de tornar o desenvolvimento colaborativo mais eficiente.

I. O Model representa os dados e suas regras de validação e persistência.<br>
II. A View trata da apresentação dos dados ao usuário, podendo ser renderizada dinamicamente com EJS ou Handlebars.<br>
III. O Controller centraliza a lógica de negócio e se comunica tanto com o Model quanto com a View.<br>
IV. É uma boa prática permitir que a View invoque diretamente métodos do banco de dados para maior eficiência.<br>

É correto o que se afirma em:<br>
```A) I, II e III, apenas.```<br>
B) II e IV, apenas.<br>
C) I, III e IV, apenas.<br>
D) I, II e IV, apenas.<br>
E) Todas as afirmativas estão corretas.<br>

---
### QUESTÃO 10 – Estrutura e Semântica do HTML
A criação de páginas web bem estruturadas e acessíveis depende do uso adequado dos elementos HTML, especialmente aqueles introduzidos no HTML5, que trouxeram mais significado semântico ao conteúdo exibido.

I. O uso de ```<article>, <section> e <nav>``` melhora a semântica e a acessibilidade das páginas.<br>
II. A tag ```<div>``` é apropriada para estruturar conteúdo quando não há uma alternativa semântica adequada.<br>
III. A marcação correta de cabeçalhos hierárquicos ajuda na navegação de leitores de tela.<br>
IV. Elementos semânticos são ignorados por mecanismos de busca e servem apenas para estilização visual.<br>

É correto o que se afirma em:<br>
```A) I, II e III, apenas.```<br>
B) II e IV, apenas.<br>
C) I, III e IV, apenas.<br>
D) I, II e IV, apenas.<br>
E) Todas as afirmativas estão corretas.<br>