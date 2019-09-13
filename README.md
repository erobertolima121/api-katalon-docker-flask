# api-katalon-docker-flask
Project using Katalon for Rest API Test Automation - Docker imagem Flask API

- Realizar o build da imagem da API Flask em: 
- Realizar pull para repositório local
- Abrir o projeto no Katalon atrevés da opção "Open Project"
- Rodar a suite, caso de teste, ou teste utilizando a opção "Run e Verify"
 
 Para rodar a suíte de teste através da linha de comando utilizar:
 
 - Acessar o workspace local do Katalon. Ex: C:\Users\Name_User\Katalon Studio\ExampleFlask
 - Abrir o prompt de comando e rodar o seguinte comando:
 
 katalon -noSplash  -runMode=console -consoleLog -projectPath="C:\Users\EIOLBMR\Katalon Studio\ExampleFlask\ExampleFlask.prj" -retry=0 -testSuitePath="Test Suites/SuiteContent" -executionProfile="default" -browserType="Chrome"
