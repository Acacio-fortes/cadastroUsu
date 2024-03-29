<h1>  Automação Robot Framework :robot: + (BDD)  :woman_technologist: :vulcan_salute: </h1>


BDD do caso de teste - Behavior Driven Development (BDD ou ainda, em livre tradução, Desenvolvimento Guiado por Comportamento) é uma abordagem de design de software de forma disciplinada, abordando uma série de conceitos e técnicas sempre com foco no domínio do software.

Caso de Teste 1 – criar um novo cadastro com sucesso<br/>
Essa suite realiza o cadastro de um novo usuário no site 'https://phptravels.com/demo/' <br/>

    Essa suite realiza o cadastro de um usuário novo usuário no site 'https://phptravels.com/demo/'
    Dado que o usuário esteja no site https://phptravels.com/demo/ 
    Quando preencher todos os dados com dados válidos 
    E realizar o calculo da soma e preencher no campo Result 
    E clicar no botão Submit 
    Então o sistema deve apresentar a tela com a mensagem “Thank you!” 
    
<h2> Requisitos para rodar os testes:</h2>

OBS: Certifique-se de que você possui o Robot Framework e a principal biblioteca SeleniumLibrary instalados em seu ambiente de desenvolvimento. Se ainda não os tiver instalado, você pode usar o pip para instalá-los: <br/>

    pip install robotframework 
    pip install robotframework-seleniumlibrary 

Certifique-se de ter o driver do navegador Chrome adequado instalado e configurado no seu sistema. <br/>
    Você pode baixar o ChromeDriver em: https://sites.google.com/a/chromium.org/chromedriver/downloads.

Executando o teste: <br/>

    robot phptravels_teste_gherkin_bdd.robot
    
O Robot Framework executará o script de teste, abrirá o navegador, preencherá os campos, realizará a soma, clicará no botão "Submit" e verificará se a mensagem de obrigatoriedade do campo não preenchido é exibida corretamente. <br/>


OBS: Certifique-se de que o ChromeDriver está configurado corretamente, e a versão do Chrome que você está usando é compatível com o ChromeDriver. Certifique-se também de ter as bibliotecas necessárias instaladas. Se houver erros durante a execução, você pode depurar o script com mensagens de log e ferramentas de depuração do Robot Framework. <br/>

Site utilizado para automação: https://phptravels.com/demo/

<img src="https://github.com/Thalita-fortes/cadastro-usu-erro/assets/78827775/94701707-0cd0-4327-b0b8-a90ad83fdff6" width="650"><br/>

Testes executados com sucesso + Visualizando o log 🤖:

<img src="https://github.com/Thalita-fortes/cadastro-usu-erro/assets/78827775/87e892f6-81c8-4b2c-8ea6-80423a7f849c" width="650"><br/>

 <img src="https://github.com/Thalita-fortes/cadastro-usu-erro/assets/78827775/1aa7f8e6-0663-40fe-b081-e1fa298a4042" width="650"><br/>

Criado por Acacio Fortes <br/>
LinkedIn: https://www.linkedin.com/in/acacio-fortes/ :vulcan_salute:


