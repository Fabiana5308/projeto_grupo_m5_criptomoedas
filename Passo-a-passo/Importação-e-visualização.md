# <center> Manual de navegação
---

Neste material você poderá seguir o passo-a-passo de execução de todas as etapas para a visualização dos dados.

- Após fazer o download do arquivo carregue-o no Google Colaboratory.

![01](https://github.com/Fabiana5308/projeto_grupo_m5_criptomoedas/blob/main/Passo-a-passo/0%20Importando%20no%20Colab.png?raw=true)
![02](https://github.com/Fabiana5308/projeto_grupo_m5_criptomoedas/blob/main/Passo-a-passo/0.1%20Abrir%20arquivo.png?raw=true)

- Em seguida clique em "Ambiente de execução" e selecione "Executar tudo".

![03](https://github.com/Fabiana5308/projeto_grupo_m5_criptomoedas/blob/main/Passo-a-passo/0.2%20Depois%20de%20carregar.png?raw=true)

- Feito isto um arquivo ".csv" será gerado e baixado automaticamente.

![04](https://github.com/Fabiana5308/projeto_grupo_m5_criptomoedas/blob/main/Passo-a-passo/0.3.png?raw=true)

- Com este arquivo em sua máquina, abra o programa de de sua preferência para carregar os dados(Sugestão: PgAdmin). Nele crie a seguinte tabela:

CREATE TABLE criptomoedas ( 

    SNo serial PRIMARY KEY, 

    Name varchar(255), 

    Symbol varchar(10), 

    Date timestamp, 

    High numeric, 

    Low numeric, 

    Open numeric, 

    Close numeric, 

    Volume numeric, 

    Marketcap numeric 

); 

![05](https://github.com/Fabiana5308/projeto_grupo_m5_criptomoedas/blob/main/Passo-a-passo/01%20Criando%20tabela.png?raw=true)
![](https://github.com/Fabiana5308/projeto_grupo_m5_criptomoedas/blob/main/Passo-a-passo/01.1%20Tabela%20criada.png?raw=true) 

- Ao tentar importar o banco de dados pode aparecer o seguinte erro. siga os instruções para a solucão. 

![](https://github.com/Fabiana5308/projeto_grupo_m5_criptomoedas/blob/main/Passo-a-passo/02%20Erro%20de%20importa%C3%A7%C3%A3o.png?raw=true)
![](https://github.com/Fabiana5308/projeto_grupo_m5_criptomoedas/blob/main/Passo-a-passo/03%20erro%20de%20caminho.png?raw=true)
![](https://github.com/Fabiana5308/projeto_grupo_m5_criptomoedas/blob/main/Passo-a-passo/04%20erro%20de%20caminho.png?raw=true)
![](https://github.com/Fabiana5308/projeto_grupo_m5_criptomoedas/blob/main/Passo-a-passo/05%20erro%20de%20caminho.png?raw=true)
![](https://github.com/Fabiana5308/projeto_grupo_m5_criptomoedas/blob/main/Passo-a-passo/06%20erro%20de%20caminho.png?raw=true)
![](https://github.com/Fabiana5308/projeto_grupo_m5_criptomoedas/blob/main/Passo-a-passo/07%20erro%20de%20caminho.png?raw=true)
![](https://github.com/Fabiana5308/projeto_grupo_m5_criptomoedas/blob/main/Passo-a-passo/08%20erro%20de%20caminho.png?raw=true)
![](https://github.com/Fabiana5308/projeto_grupo_m5_criptomoedas/blob/main/Passo-a-passo/09%20erro%20de%20caminho.png?raw=true)
![](https://github.com/Fabiana5308/projeto_grupo_m5_criptomoedas/blob/main/Passo-a-passo/10%20erro%20de%20caminho.png?raw=true) 

- Feito isso prossiga com a importação. 

![](https://github.com/Fabiana5308/projeto_grupo_m5_criptomoedas/blob/main/Passo-a-passo/11%20Importando%20dados.png?raw=true)
![](https://github.com/Fabiana5308/projeto_grupo_m5_criptomoedas/blob/main/Passo-a-passo/12%20Mostrando%20o%20caminho%20do%20arquivo.png?raw=true)
![](https://github.com/Fabiana5308/projeto_grupo_m5_criptomoedas/blob/main/Passo-a-passo/13%20Ativar%20cabe%C3%A7alho%20e%20delimitador.png?raw=true)
![](https://github.com/Fabiana5308/projeto_grupo_m5_criptomoedas/blob/main/Passo-a-passo/14%20Dados%20importados.png?raw=true) 

- Após a importação bem-secedida do banco de dados, é hora de conectar ao Power BI. 

![](https://github.com/Fabiana5308/projeto_grupo_m5_criptomoedas/blob/main/Passo-a-passo/15%20Conectando%20Posgres%20no%20Power%20BI.png?raw=true)
![](https://github.com/Fabiana5308/projeto_grupo_m5_criptomoedas/blob/main/Passo-a-passo/16%20Selecione%20a%20op%C3%A7%C3%A3o%20PostegresSQL.png?raw=true)
![](https://github.com/Fabiana5308/projeto_grupo_m5_criptomoedas/blob/main/Passo-a-passo/17%20Informe%20os%20dados%20do%20Postgre.png?raw=true)
![](https://github.com/Fabiana5308/projeto_grupo_m5_criptomoedas/blob/main/Passo-a-passo/18%20Selecione%20e%20carregue%20os%20dados.png?raw=true) 

- E seus dados estarão prontos para começar a visualização.


![](https://github.com/Fabiana5308/projeto_grupo_m5_criptomoedas/blob/main/Passo-a-passo/19%20Pronto%20para%20as%20visualiza%C3%A7%C3%B5es.png?raw=true)
