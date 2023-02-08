# Quantum Circuits

Este repositório armazena os circuitos quânticos, desenvolvidos em Python com a ferramenta Qiskit, oriundos da Iniciação Científica sobre Protocolos de Roteamento Quântico no laboratório do GERCOM da UFPA. Para facilitar a sua visualização e também terem sua funcionalidade e objetivos explicados, utilizarei o Jupyter. 

## Pré-requisitos mínimos

Para que os códigos rodem, é preciso instalar algumas bibliotecas. A seguir, listarei o mínimo necessário, porém, caso algum código solicite outras, avisarei no ínicio do mesmo. Ademais, recomenda-se a criação de um ambiente virtual para instalação das bibliotecas, mas pode ser feito sem. 
Para instalar o Qiskit, basta digitar os seguintes comandos no terminal:

```
pip install qiskit
```
e em seguida:

```
pip install qiskit[visualization]
```

Algumas outras bibliotecas são necessárias, mas são instaladas automaticamente com os comando à cima. Porém, caso isso não aconteça com `numpy` e `matplotlib`, você pode instalá-las através dos comandos:

```
pip install numpy && pip install matplotlib
```

### Se preferir

Você também pode baixar o arquivo `requeriments.txt`, que é um `pip freeze`, e dentro do diretório onde se encontra o arquivo, executar no seu terminal:

```
pip install -r requeriments.txt
```

## Notas

Este repositório deve agrupar alguns códigos introdutórios e sobre a informação quântica no geral, no entanto, seu foco está no viés das redes quânticas. Todo o material aqui exposto teve como fonte o site oficial do [Quiskit](//qiskit.org), você pode conferir mais sobre estes e outros assuntos lá.
