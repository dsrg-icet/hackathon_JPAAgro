# Hackathon JPA Agro 2021

> 22 e 23 de Fevereiro
 
## A empresa e o problema
 
A empresa JPA AGRO é uma plataforma que conecta empresas que produzem e clientes que consomem. A empresa está no mercado há mais de 10 anos e entre suas principais parcerias estão empresas de confinamentos, granjas, fábricas de ração, cooperativas, entre outros. Hoje passam pela JPA Agro mais de 140 milhões por ano e a expectativa é que esse valor chegue a 500 milhões nos próximos 10 anos.
A empresa iniciou suas atividades com serviço de representação de farelo de soja, amendoim e de algodão. Com o passar dos anos a empresa agregou as operações de comércio e fomento. Essas três operações se resumem em duas palavras: plataforma de conexão. Hoje a empresa aumentou seu catálogo de produtos e apresenta um amplo mix de produtos, todos transportados por meio de empresas parceiras que têm como princípio a excelência em logística. São mais de 30 produtos, divididos em farelos, caroços e cascas e óleos, além da polpa cítrica.
A polpa cítrica é o “carro-chefe” da empresa. É um produto derivado da laranja e utilizado como fonte de energia na dieta de ruminantes, principalmente como substituto do milho. A principal região produtora de polpa no país é o estado de São Paulo.
Hoje o maior desafio é o fechamento dos contratos anuais, por meio dos quais o produto é comprado no início do ano a preço fixado e conectado ao consumidor final ao longo desse mesmo ano, sendo o  preço de venda variável de acordo com o mercado, principalmente o de milho. Diversas variáveis afetam direta e indiretamente o preço de venda e uma maior previsibilidade de sua variação em curto prazo tornaria a tomada de decisão mais acertada. 

## A base de dados 

Para a resolução do problema serão disponibilizados dados de preços de venda de Polpa Cítrica fornecida pela JPA Agro no período de 2014 a julho de 2019. 

## Métrica de avaliação

As soluções de predição de preços de venda apresentadas serão avaliadas em termos de RMSE (Root Mean Square Error) para cada um dos próximos 30 dias (mês de agosto de 2019), a partir da última data do conjunto de dados disponibilizado.

> A equipe vencedora será a que obter o menor valor RMSE.

## Entrega das soluções

O envio da solução deverá ser feito por equipe e via e-mail (dsrg.icet@ufla.br) dentro do prazo estipulado. Em hipótese alguma serão consideradas soluções enviadas fora do prazo.
A solução deverá ser composta pelos seguintes arquivos, que serão enviados como anexo ao e-mail:
- Código comentado (extensão .py ou .r, com procedimentos de instalação de bibliotecas ou pacotes, quando aplicável)
- Descrição da arquitetura da solução (em pdf). Use o template LaTeX disponibilizado na pasta ```template_paper```. 
- Valores preditos (30 valores reais, com arredondamento em duas casas decimais, separados por ponto-e-vírgula, em um arquivo txt, referentes à predição de 30 dias à frente)

## Linguagens de programação

- Python 3.* ou R
- Indicar bibliotecas ou pacotes da linguagem que foram utilizados com procedimento de instalação. 

## Regras de participação

As equipes deverão ser compostas por no máximo 4 integrantes. Cada integrante deve ser estudante regular de graduação ou pós-graduação de qualquer curso da UFLA ou estagiário de pós-doutorado vinculado a qualquer programa de pós-graduação.
As equipes devem realizar a inscrição pelo formulário disponível em: https://forms.gle/uRqaViuf8FfbWC148

## Cronograma

> Para que sua equipe seja elegível para a premiação, você deve submeter a solução até as 23:59 do dia
23/02/2021. Envios fora do prazo não serão ranqueados!

| Data - Horário | Descrição |
|----------------------------|----------------------------|
| 08/02/2021 | Início do período de inscrições das equipes | 
| 19/02/2021 | Fim do período de inscrições das equipes | 
| 22/02/2021 – 00h00 | Liberação do conjunto de treinamento no site do DSRG (https://www.workshopdsufla.com.br/) | 
| 23/02/2021 - 23h59 | Término do prazo para envio da solução, para o e-mail dsrg.icet@ufla.br | 
| A partir de 25/02/21 | Divulgação da equipe campeã |

