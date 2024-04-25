# Criar um ambiente PySpark e Jupyter Labs (pip, poetry, etc), implementando Delta Lake e
<p>Utilizaremos o Jupyter Lab para fazer as execuções</p>

## Integrantes
<p>ARTHUR DE LUCA HONORATO</p>
<p>GABRIEL CANARIN SALAZAR</p>
<p>JOÃO EDUARDO MILAK FARIAS</p>
<p>NAUM MARCIRIO</p>

## Criar uma pasta
<p>mkdir pyspar-delta</p>

## Entrar no caminho da pasta
<p>cd pyspark-delta</p>

## Iniciar um ambiente em poetry
<p>poetri init</p>

## Intalar o pyspark, deltaspark e o jupyterlab
<p>poetry add pyspark==3.4.2 delta-spark==2.4.0 jupyterlab</p>

## Entrar dentro do ambiente criado
<p>poetry shell</p>

## Iniciar o ambiente jupyter para desenvolver
<p>jupyter-lab</p>

## Dentro do ambiente crie um notebook e uma pasta chamada RAW
![image](https://github.com/GabrielCanarin/AS-C-DL-E-AI/assets/126838860/64e7c588-ca82-4d0f-a6f6-67e1a8531be0)

## Fazer a importação do delta e do pyspark
![image](https://github.com/GabrielCanarin/AS-C-DL-E-AI/assets/126838860/0f42b80c-a880-450e-ba72-c5ec29c0451d)

## Criação de uma Spark Session, ativar algumas extensões e colocar o .jar na versao 2.4.0 do delta
![image](https://github.com/GabrielCanarin/AS-C-DL-E-AI/assets/126838860/05582920-7c6e-46db-b4b4-3c14a130f6e3)

## Foi criado um data frame para demostração, com a coluna id, nome, estado, status e limite de credito
![image](https://github.com/GabrielCanarin/AS-C-DL-E-AI/assets/126838860/0743892e-b6ce-4493-b9ec-2c87c82def62)

## Demonstração do data frame
![image](https://github.com/GabrielCanarin/AS-C-DL-E-AI/assets/126838860/46f28c38-72f1-4dd9-bc31-3edf3fb2cfe0)
![image](https://github.com/GabrielCanarin/AS-C-DL-E-AI/assets/126838860/aa230fd1-9da3-4143-a64b-a8c004c00940)

## Gerar um delta table a partir deste data frame na paste
![image](https://github.com/GabrielCanarin/AS-C-DL-E-AI/assets/126838860/de94e8d6-7579-4c7b-9160-4e9d717a8c12)
<p></p>

## Execução de um cenário na tabela Cliente
## Simular novos dados
![image](https://github.com/GabrielCanarin/AS-C-DL-E-AI/assets/126838860/f3e4b5bc-4642-4726-8726-18e56f3c8aab)
![image](https://github.com/GabrielCanarin/AS-C-DL-E-AI/assets/126838860/7bec871f-8e03-4d00-a9a7-ad98038f3bdb)

## Criar outra delta table
![image](https://github.com/GabrielCanarin/AS-C-DL-E-AI/assets/126838860/be29650c-8879-4c31-baf0-31ca8a2e9baf)
![image](https://github.com/GabrielCanarin/AS-C-DL-E-AI/assets/126838860/3f75b27b-ef2a-496e-b4b8-d5c23780cb0f)

## Fazer updata/merge com as duas delta tables
![image](https://github.com/GabrielCanarin/AS-C-DL-E-AI/assets/126838860/2b0b3a64-5f88-49c8-8b5d-444b3dfaa2e9)
![image](https://github.com/GabrielCanarin/AS-C-DL-E-AI/assets/126838860/96042ee4-6ae5-4157-9950-5f65f6970285)



