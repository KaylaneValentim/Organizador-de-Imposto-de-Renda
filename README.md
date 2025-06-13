# Organizador-de-Imposto-de-Renda

- Desafio de projeto do BootCamp "Santander - Excel com Inteligência Artificial". Foi desenvolvida uma planilha que reúne e organiza informações importantes para o processo de declaração de imposto de renda. Ela é constituída por um painel de navegação, botões e três abas.

## PRIMEIRA ABA: DADOS DO TÍTULAR
- Área criada para o preenchimento de dados de pessoa física.

<ins>Descrição:<ins>

Neste campo, o usuário pode inserir as informações pessoais necessárias para a declaração do imposto. Cada uma é devidamente formatada segundo é requerido pelos dados. Principalmente, o CPF, CEP, número de celular e telefone. 

## SEGUNDA ABA: INFORMES DE RENDIMENTO BANCÁRIOS
- Espaço destinado para inclusão dos rendimentos obtidos.
  
<ins>Descrição:<ins>

Uma tabela de apoio foi feita para que os códicos dos bancos fossem colocados na aba. Com a validação de dados, esses códicos foram restringidos, o que garante que não haja a modificação deles, assim como a alteração das instituições financeiras. Vale ressaltar, que também é possível incluir o valor de cada rendimento e anexos de extratos bancários. Em célula denominada "TOTAL", é calculado atráves da fórmula de "SOMA" todos esses valores. O que permite a vizualização do resultado final dessa soma.


## NOTAS BANCÁRIAS
- Extratos das entradas das receitas mensais do usuário.

<ins>Descrição:<ins>

Tabela que reúne as datas, categorias e valores de entrada de cada receita do usuário. As categorias criadas foram
"HOLERITES, FREELANCE e CNPJ" por meio da validação de dados.

## PAINEL DE NAVEGAÇÃO
- No canto esquerdo de cada aba, há um menu interativo formado por uma logo, título e três botões principais. Sendo esses, o **"TÍTULAR,"INFORMES" e "NOTAS"**, respectivamente. Ao serem clicados, direcionam o usuário para a página desejada.
  
- Além disso, existem outros botões com o mesmo intuito, como os de "ANTERIOR" e "PRÓXIMO". O primeiro permite que o usuário retorne para as abas que foram passadas, enquanto o segundo move para as seguintes.

- Desse modo, o menu garante uma navegação de forma dinamica e prática.

