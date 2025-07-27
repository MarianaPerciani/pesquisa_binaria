# Adivinhe o Número (com Pesquisa Binária)

Este é um projeto simples e interativo desenvolvido em Python para demonstrar o funcionamento do algoritmo de pesquisa binária. O programa "adivinha" um número pensado pelo usuário dentro de um intervalo definido, utilizando a lógica da pesquisa binária para chegar ao resultado no menor número de tentativas possível.

## 🚀 Como Funciona

O algoritmo de pesquisa binária é extremamente eficiente para encontrar um item em uma lista ordenada. Ele funciona dividindo repetidamente pela metade a porção da lista que pode conter o item, eliminando assim metade dos elementos restantes em cada passo.

Neste projeto:
1.  O usuário define o tamanho máximo da lista de números.
2.  O programa calcula o número máximo de tentativas necessárias para adivinhar qualquer número dentro desse intervalo, baseado no logaritmo de base 2 do tamanho da lista ($\lceil\log_2(\text{tamanho da lista})\rceil$).
3.  O usuário pensa em um número secreto dentro do intervalo.
4.  O programa faz uma pergunta, sugerindo o número do meio do intervalo atual.
5.  O usuário informa se o número secreto é maior, menor ou igual ao número sugerido.
6.  Com base na resposta, o programa ajusta o intervalo de busca, eliminando a metade irrelevante da lista.
7.  Os passos 4 a 6 se repetem até que o programa acerte o número.

## ✨ Funcionalidades

* Definição dinâmica do tamanho da lista de busca.
* Cálculo automático do número máximo de tentativas (garantindo a eficiência da pesquisa binária).
* Interação simples e guiada com o usuário.
* Demonstração prática da eficiência da pesquisa binária.

## 💻 Como Rodar o Projeto

1.  **Clone o repositório (ou faça o download do arquivo `pesquisa_binaria.ipynb`):**
    ```bash
    git clone [https://github.com/MarianaPerciani/pesquisa_binaria.git]
    cd Adivinhe_o_Numero_Pesquisa_Binaria
    ```

2.  **Abra o notebook Jupyter:**
    Você pode abrir o arquivo `pesquisa_binaria.ipynb` usando Jupyter Notebook, JupyterLab ou Google Colab.

    * **Com Jupyter Notebook/Lab:**
        ```bash
        jupyter notebook pesquisa_binaria3.ipynb
        ```
    * **Com Google Colab:**
        Faça o upload do arquivo `pesquisa_binaria.ipynb` diretamente para o Google Colab.

3.  **Execute as células:**
    Execute as células do notebook sequencialmente para iniciar o jogo. Siga as instruções no console para interagir com o programa.

## 🕹️Exemplo de Interação:

`````
Digite o tamanho da lista que você quer: 1000
Pense em um valor de 1 a 1000.
Aposto que consigo acertar em até 10 tentativas.
Quando estiver pronto para iniciar digite 1: 1
Tentativa 1: Você pensou no número 500?
Se acertei, digite 1.
Se o valor que você pensou é maior, digite 2.
Se o valor que você pensou é menor, digite 3. 3
Tentativa 2: Você pensou no número 250?
... (e assim por diante até acertar)
Uhuuul, acertei em X tentativas!
`````

## 🛠 Tecnologias Utilizadas

* Python

## 🤝 Contribuição

Sinta-se à vontade para contribuir com este projeto! Se você tiver sugestões, melhorias ou encontrar algum bug, por favor, abra uma issue ou envie um pull request.
