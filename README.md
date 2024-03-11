# Phishing para captura de senhas do Facebook ☠️

Primeiro desafio do curso de cibersecurity da DIO - Criação de phishing para captura de senhas do Facebook.

### Ferramentas 🛠️

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: http://www.facebook.com

### Resutados esperados

![image](https://github.com/arend04/cibersecurity-desafio-phishing-DIO/assets/97132124/3f157f4a-2142-44ad-bf24-1d32bac7a89f)

### Dificuldades para realizar o exercício

- O método ``` Site Cloner ``` não funcionou no browser utilizado para testes, sempre retornava ```_user=0``` no campo ```POSSIBLE USERNAME FIELD FOUND:``` .

![image](https://github.com/arend04/cibersecurity-desafio-phishing-DIO/assets/97132124/2a8dec8d-a414-43e3-8d9f-6143508a0400)

### Solução encontrada para a execução do exercício

Reconfigurei o Kali Linux alterando o método de ataque para ```Web Templates``` e escolhi o Google para clonar.

![image](https://github.com/arend04/cibersecurity-desafio-phishing-DIO/assets/97132124/2d4509bf-b7e6-466f-936b-24cded9c7739)

### Resultado

![image](https://github.com/arend04/cibersecurity-desafio-phishing-DIO/assets/97132124/4498ae56-e6e9-4cf2-ad65-b4900d73f21e)



 



