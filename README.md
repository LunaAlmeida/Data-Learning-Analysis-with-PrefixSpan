# Algoritmo PrefixSpan da biblioteca SPMF com Python
Esse trabalho utiliza a implementação do PrefixSpan da biblioteca SPMF para fazer análise de dados de log de alunos da plataforma Moodle.

## Bibliotecas a serem instaladas
Utilize *pip install -r requirements.txt* para instalar todas as bibliotecas necessárias para o projeto.

Para que esse código seja utilizado é necessário que se utilize um ambiente linux.

Primeiramente crie um ambiente virtual python.

No site https://data-mining.philippe-fournier-viger.com/tutorial-how-to-call-spmf-from-python/ siga as instruções para instalar o spmf.jar. Após instalar o framework ele deve ser colocado na pasta do seu ambiente virtual em include e spmf. Como na imgaem:
 
 ![image](https://github.com/LunaAlmeida/Data-Learning-Analysis-with-PrefixSpan/assets/62681460/cf403209-e4e2-48be-a58d-40f159708d72)

# Como utilizar o código
Insira o caminho para a pasta que contém seus dados de log do Moodle juntamente com os dados de nota dos alunos, nos campos indicados na imagem
![image](https://github.com/LunaAlmeida/Data-Learning-Analysis-with-PrefixSpan/assets/62681460/30a1084a-e6ba-454d-a0b7-ac82915bfedf)

É necessário apontar o local em que as sequências resultantes foram salvas, que no caso é feito na variável 'resultado' na imagem abaixo:
![image](https://github.com/LunaAlmeida/Data-Learning-Analysis-with-PrefixSpan/assets/62681460/cabef094-1a83-4be8-a214-a666bfd74e68)

Após ter realizado os passos é possível ver o resultado das sequências encontradas como na imagem abaixo:
![image](https://github.com/LunaAlmeida/Data-Learning-Analysis-with-PrefixSpan/assets/62681460/ea83125b-5bb1-4e7b-8aac-97e0216afdf6)


