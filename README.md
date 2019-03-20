# Roadmap - php7
1. PHP 7 BÁSICO
	- [ ] Sintaxe
	- [ ] Estruturas de Controle e repetição (if, else, for, foreach, while)
	- [ ] functions
	- [ ] Arrays 
	- [ ] Formulários, POST e GET
	- [ ] Cookies e Session
	- [ ] Constantes
2. Projeto Prático
	- [ ] Construir uma aplicação de lista de coisas (Todo List) a serem feitas:
		- Inicialmente deve ser uma lista simples onde seja possível adicionar tarefas. A tarefa deve ter uma descrição e uma situação (feita ou não feita).
		- Deve existir uma tela com a listagem das tarefas.
		- Deve ser possível Remover e Modificar os itens dessa listagem.
	- [ ] Não se preocupe em fazer uma coisa bonita nesse ponto. A intenção no futuro é ir melhorando essa mesma aplicação. Fazer bonito é um PLUS.
	- [ ] Deve ser criado um repositório no github para esse projeto. Ele será atualizado diversas vezes.
3. PHP OO e PHP Intermediário
	- [ ] Classes e Objetos
	- [ ] Métodos
	- [ ] Encapsulamento (public, private e protected)
	- [ ] Métodos mágicos (construct, etc...)
	- [ ] Classes e Métodos Abstratos
	- [ ] Métodos e atributos estáticos
	- [ ] Interfaces
	- [ ] PDO
	- [ ] Namespaces
	- [ ] Erros e Exceções
3. Composer
	- [ ] Autoload
	- [ ] Gerênciador de Dependências: como sugestão, você pode ver sobre alguma biblioteca do PHP para fazer o controle de rotas (router), e aplicar no próximo projeto prático.
4. PHP FIG e PSRs
	- [ ] PHP FIG (Grupo que define convenções para a programação utilizando a linguagem PHP). Veja as PSR-1, PSR-2 e a PSR-4 você já terá visto, o autoload do composer.
	- [ ] http://br.phptherightway.com/ (Site com bastante conteúdo de como fazer do 'jeito certo')
5. Projeto prático
	- [ ] Atualizar o projeto prático com os novos conceitos aprendidos.
		- Aplicar OO no projeto
		- Aplicar PDO no Projeto
		- Aplicar PSR-1 e PSR-2
		- Utilizar o composer para fazer o autoload das classes
		- Você pode ou não usar alguma dependência utilizando o composer
6. Arquitetura MVC
	- [ ] Estude sobre arquitetura MVC, como funciona, qual a ideia, por quê usar, e como criar um projeto com essa arquitetura.
7. Projeto prático
	- [ ] Aplique o padrão de arquitetura MVC no projeto do Todo List
	- [ ] Crie um CRUD de usuários na aplicação.
	- [ ] Deve existir um Menu onde o usuário possa alternar entre o CRUD de usuários e o de tarefas. O usuário terá um e-mail e senha.
	- [ ] Adicionar uma tela de login na aplicação. Não deve ser possível entrar no painel de controle de usuários e tarefas sem estar logado.
	- [ ] A tarefa agora pode possuir ou não, uma data para realização.
8. Clean Code
	- [ ] Ler sobre Clean Code
	- [ ] https://www.youtube.com/watch?v=ummTYjEQC74&list=PLN7yVcqYnDlVrRrIdKntu4fCOlgprpHk5&index=4
9. SOLID
	- [ ] dar uma lida sobre SOLID
10. Object Calisthenics no PHP
	- [ ] https://www.youtube.com/watch?v=IaZC6iKX5J4&index=3&list=PLN7yVcqYnDlVrRrIdKntu4fCOlgprpHk5
	- [ ] Estudar sobre o tema
11. Projeto Prático!
	- [ ] Refatorar seu projeto aplicando os conceitos aprendido de Clean Code, Object Calisthenics e SOLID.
	- [ ] Adiciones mais features que julgar necessárias.
	- [ ] Crie um README de como instalar e configurar o seu projeto para executá-lo.
	- [ ] Faça o deploy da sua aplicação (NÃO USE FTP) utilizando o git em algum serviço de host, e deixa o projeto rodando.
12. Projeto prático!
	- [ ] Agora vamos criar um novo repositório e um novo projeto utilizando o framework laravel. A ideia é fazer a mesma aplicação de Todo List, porém agora separando em dois projetos back-end e front-end. A idéia é construir o back-end (API REST) utilizando o laravel e o front-end utilizando React ou Vue.
	
BÔNUS

- [ ] TESTES AUTOMATIZADOS COM PHPUNIT
- [ ] DOCKER PARA LEVANTAR OS AMBIENTES
- [ ] LIVRO PHP MODERNO (Esse livro é bom depois que você terminar até o passo 10)
