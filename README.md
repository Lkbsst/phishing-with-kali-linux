# phishing-with-kali-linux

Este projeto é de cunho educacional.
Segue o passo a passo para a utilização da ferramenta <strong>setoolkit<strong>

### Entrar com usuario root
  
  - abra o terminal e digite
  - sudo su
 
### Iniciar a ferramenta setoolkit
 
  - setoolkit

###  Selecionar as seguintes opções:

  - Social-Engineering Attacks
  - Web Site Attack Vectors
  - Credential Harvester Attack Method
  - Site Cloner

 Selecione o IP da maquina receptora -> ela ira servir como um servidor <sub>(pode manter o ip da maquina que está usando para o ataque)</sub>
 
 Por fim selecione a URL que irá ser clonada para o site fake

 ## Resultado

 Ele retornara as entradas que foram colocadas no site fake e com isso você tera sua flag

 ![image](https://github.com/Lkbsst/phishing-with-kali-linux/assets/131914485/aba9b330-960b-4036-ace8-e9424faf7c22)

 ## Nota: 
 Na parte de seleção de URL poderás escolher o site que melhor encaixa para sua engenharia social, tudo vai depender do alvo.
 Em minha passagem pelo projeto testei com alguns sites, este do teste em questão foi com a pagina do Linkedin.

 ### Possiveis problemas

 Pode ser que encontre alguma dificuldade em receber o log, por exemplo as entradas de usuário e senha não aparecerem ou aparecerem coisas desconexas no lugar.
 Uma forma que encontrei para resolver e que funcionou comigo foi seguir os passos do seguinte repositório:
 https://github.com/lucaspicinini/phishing-with-kali-linux
 

