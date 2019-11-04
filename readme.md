## Sobre o Projeto

<p>Foi criada uma interface para gerenciamento de tarefas (tasks), portando o sistema consiste em:</p>
<ul>
    <li>Criar Tarefa</li>
    <li>Listar Tarefa</li>
    <li>Atualizar Tarefa</li>
    <li>Apagar Tarefa</li>
    <li>Arquivar uma Tarefa</li>
    <li>Re-ativar uma Tarefa</li>
</ul>
<p>Utilizado o conceito de SPA (Single Page Application)</p>

## Tecnologias Utilizadas
- **Front End**:    Vue.js
- **Back End**:     PHP, Laravel
- **Banco de Dados (Relacional)**:   MySQL
- **Gerenciador de Dependecias**:   NPM, Composer
- **Framework CSS**:   Bulma

## Requisitos

<p>Sistema operacional baseado em Unix/Linux</b></p>
<p>MySQL versão 5.7 ou superior</b></p>
<p>PHP 7.2 ou superior</b></p>
<p>Gerenciador de Dependecias Composer e NPM</b></p>
<p>Git</b></p>

## Utilização

<p>O acesso a aplicação deverá ser feito através do endereço <b>127.0.0.1:8000</b></p>
<p>Para editar o conteúdo de alguma task, é necessário clicar duas vezes sobre o conteúdo da mesma.</p>
<p>É possivel alternar o status da Task clicando no ```checkbox``` que se encontra no cabeçalho da tarefa.</p>

## Instalação

1.  Clonar o repositório
```
$ git clone https://github.com/HadoukenMS/supero_ti.git supero_app
```
2. Acessar a pasta da aplicação
```
$ cd supero_app
```
3. Instalar as dependências com composer e NPM
```
$ composer install
```
```
$ npm install
```
4. Configurar o arquivo ```.env``` com os dados de acesso ao banco de dados.
5. Rodar o cmd ``` $ php artisan migrate ``` para criar as tabelas e registros no banco de dados.
6. Simular um servidor web com o comando ```$ php artisan serve```.

## Criado e mantido por

- **Lucas Vieira (lucsolivier@gmail.com)**

