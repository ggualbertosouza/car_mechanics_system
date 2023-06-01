# car_mechanics_system

Aprendendo usar Django de forma efetiva criando sistema de uma automecânica, com base nos vídeos do canal Pythonando - https://www.youtube.com/watch?v=pNlHlhWDpV0&list=PL3gEA6Xsr_enTjEeyAyLrqdJmEFM8FvwM

Etapas do aprendizado e criação:

  Criando ambiente:
    - Criar repositório no GitHub, clonar na minha máquina.
    - Criar ambiente virtual em python e instalar instância do Django.
    - Criar projeto Django, "mechanic"

  Dentro do projeto:
    - Criar app inicial "clientes" (instalar app dentro de "settings" do projeto "mechanic")
    - Criar primeira url usada no projeto "clientes/", consequentemente, criar view dentro do app e arquivo "urls".
    - Criar pasta "templates" do projeto, onde fica armazenado os arquivos static e html base do projeto.                                # "base.html" - É o html que vai se repetir em todas as páginas.
    - Apontar caminho dos arquivos static e de media que o projeto vai receber dentro de "setting" do projeto.                           #  importar biblioteca OS 
    - Criar pasta templates dentro do app clientes, porseguinte, html da página clientes.                                                #  extender html base para a página clientes{% extends %}
    - Apontar os devidos caminhso do html, css e JS usados, tanto no app quanto no projeto.
    - Criar as devidas funções da página, principalmente nos botões.
    - Criar lógica que as requisições do tipo "POST" armazene o valor preenchido no formulário às devidas variáveis.                          
    
    
    
  JavaScript 
    Functions
      - Botão "Adicionar um carro":
        .Criar variável que pegue classe usada no css na DIV específica,                        container = document.getElementById('form-carro')
        .Criar variável que tenha o texto de html que desejo colocar na div,                    html = "<br>  <div class='row'> <div clas..............
        .criar lógica que jogue o html criado dentro da DIV.                                    container.innerHTML += html    ("+=" incrementa novo valor a variável)
          
