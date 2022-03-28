## Tutorial em Português

### **Vamos seguir passo a passo de como criar seu AWS Budget para que você não desperdice dinheiro**


#### 1. Crie a sua conta AWS [aqui](https://aws.amazon.com/pt/)

![](https://i.imgur.com/46ULTwk.png)

#### 2. Após criar a conta e chegar na tela inicial, intitulada de AWS Management Console, utilize a barra de pesquisa no canto superior esquerdo para procurar por "AWS Budgets" e em seguida selecione o serviço

![](https://i.imgur.com/zodi1lh.png)

![](https://i.imgur.com/Fq0908r.png)

#### 3. Ao entrar na tela principal do AWS Budgets você pode alterar a linguagem da página (Seta 1) e criar o seu budget no botão (agora traduzido) "Criar um orçamento"

![](https://i.imgur.com/QJnkuzN.png)

#### 4. Nas telas a seguir você vai criar o seu Orçamento e detalhes de como ser alertado, o passo a passo será por escrito com imagens usadas para exemplo e guia

##### 4.1. Na página tipo de Orçamento, selecione "Custo de Orçamento" e em sequência, próximo

![](https://i.imgur.com/MC0LUpQ.png)

##### 4.2. A próxima página é intitulada "Definir seu Orçamento", e aqui vamos colocar a maior parte das informações relevantes

###### 4.2.1. Na seção "Detalhes" apenas o título pode ser colocado, nomeie como quiser

![](https://i.imgur.com/Jus8epj.png)

###### 4.2.2. Na seção "Definir valor do orçamento" temos mais opções, no caso exemplo é um alerta para **praticamente qualquer gasto ocorrendo na conta**, o único valor que necessitou ser alterado no exemplo foi o valor, e como todos os valores de cobrança da AWS são calculados em dólar, 50 centavos é o bastante

![](https://i.imgur.com/UncbdJG.png)

###### 4.2.3. Na seção "Budget Scope" não é necessário alterar nada, apenas conferir se todos os serviços AWS estão selecionados, já que meu intuito é um alerta de **qualquer gasto**, também é possível ter um alerta para serviços individuais

![](https://i.imgur.com/rbZwOOe.png)

###### 4.2.4. Finalmente, pode apertar o botão "Próximo" para podermos fazer a parte de alertas

![](https://i.imgur.com/pips1GL.png)

##### 4.3. Na página "Configurar Alertas" o objetivo é exatamente esse, permitir que a AWS nos avise caso algum parâmetro de nossa escolha seja engatilhado

Primeiramente confira se o valor orçado está de acordo com o que você colocou (se esquecer o ponto, esses 50 centavos podem virar 50 dólares bem rápido) e na sequência clique em "Adicionar um limite de alerta"

![](https://i.imgur.com/kdPSHCY.png)

###### 4.3.1. Ao selecionar o botão "Adicionar um limite de alerta", a seção a seguir aparece, é necessário selecionar os parâmetros do alerta (no caso do exemplo, 50% do valor orçado) e a preferência de notificação, que no caso foi um email pessoal, caso queira selecionar mais de um email para alerta é necessário separá-los por vírgula

Após isso, caso queira, pode criar outro(s) alerta(s) com o botão "Adicionar limite de alerta)

![](https://i.imgur.com/8q7VlmM.png)

###### 4.3.2. Quando terminar, selecione mais uma vez o botão "Próximo"

![](https://i.imgur.com/pips1GL.png)

##### 4.4. A próxima página se chama "Anexar ações" e pode ser usada para colocar gatilhos para cada alerta, a variedade das ações possíveis é enorme e recomendo um estudo em separado para entender melhor, pois não é o foco deste tutorial

Nesta tela também é possível ver **quantos** alertas estão ativos para esse Orçamento, no caso do exemplo, fiz mais 2, com 75% e 100% respectivamente para demonstração e melhor controle caso necessário, é melhor ter preparo demais do que de menos

![](https://i.imgur.com/PwgZ4Sr.png)

###### 4.4.1. Quando terminar, selecione mais uma vez o botão "Próximo"

![](https://i.imgur.com/pips1GL.png)

##### 4.5. A próxima página se chama "Revisão" e contém o resumo de todas as páginas que nós ajustamos durante o tutorial, quando terminar de revisar, selecione o botão "Criar orçamento" no canto inferior direito

![](https://i.imgur.com/hbUi3mr.png)

#### 5. Está criado o seu primeiro orçamento!

Caso queira, ao selecionar a caixinha branca no lado esquerdo do seu orçamento, o botão "Ações" se torna selecionável, permitindo Editar, Excluir, Copiar e Criar relatório de orçamento

Alternativamente, ao clicar no nome do seu orçamento você é levado para uma tela de detalhes mais extensiva

![](https://i.imgur.com/Ag4tDiD.png)

#### 6. Caso o seu alerta de orçamento seja ativado e você queira saber o que está de cobrando, você pode conferir pelo AWS Cost Explorer, o método para pesquisar essa ferramenta é o mesmo utilizado para o AWS Budgets

Recomendo ao fazer esse tutorial acessar o serviço ao menos uma vez, já que é no primeiro acesso que ele começa a gerar todos os relatórios e esse procedimento pode demorar um pouco, mas uma vez feito, está feito

![](https://i.imgur.com/L6xgm5o.png)



### Tutorial in English (TBD)

#### **Let's go step by step on how to create your own AWS Budget so that you don't end up wasting money**
