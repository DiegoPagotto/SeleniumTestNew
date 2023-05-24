# SeleniumTest
Este repositório contém um projeto que utiliza o JSON Server para emular o backend.

## Configuração
Antes de executar o projeto, é necessário instalar o JSON Server. Certifique-se de ter o Node.js e o npm (Node Package Manager) instalados em seu sistema. Em seguida, execute o seguinte comando para instalar o JSON Server globalmente: 
    
    npm install -g json-server 

## Executando o servidor
Para iniciar o servidor do projeto, siga estas etapas:

1.Navegue até a pasta que contém o arquivo JSON (db.json).
2.Execute o seguinte comando:
    
    json-server --watch db.json
    
Isso iniciará o servidor e ele estará pronto para atender as solicitações emuladas.
