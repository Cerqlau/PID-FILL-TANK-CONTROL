# PID LEVEL TANK CONTROL ⚡️💡💻

Este projeto de controle PID de um nivel dedicado para discilpina de controle de sistemas industriais. Nele está disponibilizado o código do projeto para ser utilizado com o simulador PLCSIM do Simatic Manager e Factory IO. Ele utiliza servidor OPC entre as aplicações para realizar a comunicação. 

A linguagem utilizada para programação foi a STL (Standard Template Library), uma versão da Siemens similar a listra de instruções da linguagem assembly. O projeto foi desenvolvido para fins de estudo e por este motivo foram utilizados conceitos de mirroring e POO. 

## 🚀 Começando

Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local (virtual) para fins de desenvolvimento e teste.

Os arquivos do projeto e documentos utilizados se encontram no repositório

### 📋 Pré-requisitos

```
=> Sistema operacional Windows

=> Versões: 7,8,10,11
=> Simatic Manager 5.6
=> PLCSIM 
=> Factory IO
=> VMWARE WORKSTATION 15 (Opicional)

```

### 🔧 Pré-configurações

Certifique-se de executar o programa como Admininstrador para uma melhor compatibilidade. É recomendado a instalação do programa em uma máquina virtual. A utilizada neste projeto foi a VMWARE WORKSTATION 15

### ⚙️ Executando o programa

1- Inicialize o programa Simatic Manager 5.6;

2- Vá na aba "Files" selecione a opção "Retrieve";

3- Selecione o arquivo "S7_PID_FactoryIO_T_Level.zip" desejado para carregá-lo;

4- Abra o S7-PLCSIM;

5- No Simatic Manager 5.6 selecione o ícone de "Download" para transferir todo o conteúdo do programa para o S7-PLCSIM;

6- Para importar a cena para o Factory IO, copie e cole o arquivo "Level Control_PID.factoryio" dentro da pasta "C:\Users\Administrator\Documents\Factory IO\My Scenes";

7- Abra o Programa Factory IO e selecione OPEN > MY SCENES e Selecione a cena que acabou de importar.

8- Com a cena aberta pressione "F4" para abrir a aba Driver; 

9 - Selecione S7-PLCSIM e Conectar para estabelecer a comunicação OPC; 

10 - No programa S7-PLCSIM selcione o modo "Run" 

11 - Na cena aberta do Factory IO selecione ícone "PLAY" para iniciar a simulação. 

## 📝 Nota

1- O Controlador PID realiza a verificação da proporção necessária para o enchimento ou esvaziamento completo do tanque através do Set point; 

2- O botão Stop ou Emergência cancela o circuito. Que só poderá ser reiniciado após o reiniciação do sistema através do botão Reset; 

3 - O Botão Reset possui a lógica de reinicialização forçada caso seja mantido pressioando por 3 segundos;

4 - O controloador permite um pequeno offset em sua lógica;

5 - O sistema retorna a condição de Stand BY após 3 segundos após alcançado o Set Point; 

6 - A qualquer momento o set point pode ser alterado que resultando no acompanhamento do controle PID;

7 - As vezes a comunicação OPC gera erros neste caso reinicie a simulação no botão reset;

## 🦾 Technologia

=> STL Siemens 
=> OPC UA

## 📦 Desenvolvimento

Lauro Cerqueira

LinkdIn: https://www.linkedin.com/in/lauro-cerqueira-70473568/

Instagram : @laurorcerqueira

## 📄 Licença

Este projeto está sob a licença MIT - veja o arquivo [LICENSE.md](https://github.com/usuario/projeto/licenca) para detalhes.

## 🎁 Distribuição

* Conte a outras pessoas sobre este projeto 📢
* Convide alguém da equipe para uma cerveja 🍺 
* Obrigado publicamente 🤓.

