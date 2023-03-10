#**CONTEXTO**

#**DEPRESSÃO E HÁBITOS SAUDÁVEIS**

O transtorno depressivo representa um grande problema de saúde pública e é apontado como uma das principais causas de doenças e debilitações segundo a Organização Mundial da Saúde (OMS). A depressão resulta de uma interação complexa de fatores sociais, psicológicos e biológicos e, embora o acesso a diagnósticos e tratamentos esteja aumentando, muitos ainda não possuem acesso ao controle adequado dos sintomas depressivos.

Para garantir um estilo de vida saudável, a OMS recomenda a prática regular de exercícios, bem como a adoção de uma dieta saudável rica em alimentos in natura e com reduzido teor de gordura saturada, sal e açúcares refinados.

Nesta trabalho utilizei dados de uma pesquisa realizada anualmente nos Estados Unidos para avaliar (1) qual o perfil de indivíduos (adultos maiores de 18 anos) com sintomas depressivos nos EUA no período de 2005-2006, e (2) se hábitos saudáveis de alimentação e atividade física estão associados a menores índices de depressão nesta população. 


#**NATIONAL HEALTH AND NUTRITION EXAMINATION SURVEY (NHANES)**

O National Health and Nutrition Examination Survey (NHANES) é uma pesquisa anual conduzida pelo National Center for Health Statistics (NCHS) do Centro de Controle e Prevenção de Doenças (Centers for Disease Control - CDC) para avaliar a saúde e nutrição de adultos e crianças dos Estados Unidos. Dados coletados incluem questões demográficas, socioeconômicas, dietéticas e relacionadas à saúde, com o componente de exame contendo medidas médicas, odontológicas, fisiológicas e exames laboratoriais.

A pesquisa examina uma amostra de cerca de 5.000 pessoas a cada ano, selecionada a partir de amostragem complexa a fim de selecionar uma amostra representativa da população civil não institucionalizada dos EUA. Sendo assim, as análises utilizando este estudo devem ser realizadas utilizando técnicas e ferramentas que levem em conta a amostragem complexa.

Neste trabalho, no entanto, irei assumir que os dados foram obtidos usando uma amostra aleatória da população de interesse e utilizarei técnicas e ferramentas de análise usuais para amostras aleatórias.

#**PATIENT HEALTH QUESTIONNAIRE-9 (PHQ-9)**

O Patient Health Questionnaire-9 (PHQ-9) é um instrumento utilizado para avaliar o grau de depressão em pacientes. O questionário consiste de 9 itens em que os respondentes indicam a frequência (0 = “nenhuma vez”, 1 = “menos de uma semana”, 2 = “uma semana ou mais” e 3 = “quase todos os dias”) de sintomas de depressão nas duas últimas semanas.

O PHQ-9 inclui os seguintes itens para a pergunta “Nas últimas 2 semanas, com que frequência você ficou incomodado por algum dos problemas a seguir?” (0 = “nenhuma vez”, 1 = “menos de uma semana”, 2 = “uma semana ou mais” e 3 = “quase todos os dias”):

1 - Pouco interesse ou pouco prazer em fazer as coisas

2 - Se sentiu para baixo, deprimido(a) ou sem perspectiva

3 - Dificuldade para pegar no sono ou permanecer dormindo ou dormiu mais do que o costume

4 - Se sentiu cansado(a) ou com pouca energia

5 - Falta de apetite ou comeu demais

6 - Se sentiu mal consigo mesmo(a) ou achou que é um fracasso ou que decepcionou sua família ou a você mesmo(a)

7 - Dificuldade para se concentrar nas coisas (como ler o jornal ou ver televisão)

8 - Teve lentidão para se movimentar ou falar (a ponto de outras pessoas perceberem), ou ao contrário, esteve tão agitado(a) que você ficava andando de um lado para o outro mais do que costume

9 - Pensou em se ferir de alguma maneira ou que seria melhor estar morto(a)

O escore total é calculado a partir da soma dos itens 1-9 e varia de 0 a 27, em que maiores valores do escore indicam maiores frequências de sintomas de depressão. Aqueles com pontuação maior ou igual a 5 para o escore total de PHQ-9 são considerados como tendo sintomas leves (5-9), moderados (10-14), moderadamente severos (15-19) e severos de depressão (>= 20).

#**Healthy Eating Index - (HEI)**

O Healthy Eating Index (HEI) é uma medida de qualidade da dieta baseada nas orientações dietéticas do governo federal americano (Dietary Guidelines for Americans). O HEI utiliza diferentes grupos alimentares para o cálculo do escore, variando de 0 a 100, em que maiores valores do escore refletem dietas mais próximas das orientações alimentares em vigor.

O índice é composto por 13 componentes baseados nos grupos alimentares descritos nas recomendações dietéticas. Detalhes dos valores máximos e interpretações estão descritos no quadro abaixo:

<img src="https://i.imgur.com/rFhgCMp.png"></img>


#**Physical Activity Guidelines for Americans (PAGA)**

O Physical Activity Guidelines for Americans (PAG) é emitido pelo Departamento de Saúde e Serviços Humanos (U.S. Department of Health and Human Services (HHS)) e possui recomendações de atividades físicas. Este documento é utilizado em conjunto com as orientações dietéticas para americanos (Dietary Guidelines for Americans) para promover a importância de ser fisicamente ativo e seguir uma dieta saudável.

O PAGA recomenda que adultos se engajem em pelo menos 150 minutos de atividades aeróbicas de intensidade moderada ou 75 minutos de atividades aeróbicas de intensidade vigorosa semanalmente. A partir dos dados coletados do NHANES, é possível calcular o número de minutos de atividades físicas, definido como a total minutos semanais de atividades físicas moderadas + 2*(total minutos de atividades aeróbicas vigorosas).

Abaixo estão os bancos de dados utilizados:

**DEMO_PHQ.csv**: banco de dados contendo 5334 observações de adultos pesquisados no NHANES 2005-2006.

**PAG_HEI.csv**: banco de dados contendo 9424 observações de crianças e adultos pesquisados no NHANES 2005-2006.

Disponíveis em: https://github.com/emmanuelvrm/portifolio/tree/main/Inferencia_Depressao_e_Habitos_Saudaveis/docs





