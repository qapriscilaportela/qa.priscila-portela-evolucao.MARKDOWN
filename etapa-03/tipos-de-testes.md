
TESTE FUNCIONAL 
Teste funcional é basicamente testar as funções do sistema, testar requisitos e especificações do sistema. Testa se aquilo que está documentado é realmente o que o sistema entrega, e se o que ele entrega age conforme o esperado. Verifica o que ele faz.

Teste CAIXA PRETA
São testes focados em entrada e saída de dados e não fazem nenhuma referência a estrutura interna. 

Temos alguns testes específicos para caixa preta, o primeiro deles é> 

Partição de equivalência 
é a técnica para nos auxiliar na quantificação de casos de teste, tendo em base as regras de negócio, usamos para encontrar faixas de valores a serem testadas.
Temos duas formas de organizar os dados, partição validos e partição inválidos, e cada elemento deve pertencer a apenas uma partição.
Podendo ser aplicadas em vários níveis de teste, aceite, sistema, integração..

Análise de valor limite
é uma extensão do particionamento de equivalência, os maiores casos de problemas estão  nos valores limites, quando acaba a partição valida e começa a invalidar. Geralmente é usada quando incluem intervalo de números. 

Tabela de decisão 
baseada no requisito, para decidir quais são os resultados esperados para cada conjunto de entrada que temos, é a melhor técnica para regras complexas, pois é eficiente em revelar combinações de entradas diferentes que podem levar a diferentes saídas.

Teste de transição de estado
Verifica mudanças no estado de um ‘software’, pois componentes podem responder de maneira diferente a um evento, dependendo das condições atuais. Temos 3 bases específicas que compõe esta categoria,  estado, transição e evento.
Conforme o objetivo do teste podemos testar componentes, classes e objetos.

Teste de caso de uso
Para cada cenário de caso de uso devera ter uma descrição de caso de teste, é descrição de interação entre utilizadores e sistema, devem conter sequencias de etapas que descrevem as interações entre o ator e o sistema.

TESTE CAIXA BRANCA
Se preocupa com a estrutura interna do ‘software’, podem ser usadas em todos os níveis de testes, e é mais usada ao nível de componente, nos testes de caixa branca não analisamos especificações e sim o código fonte.

Teste e cobertura de instruções
Esta técnica testa as instruções executáveis do código. O objetivo deste teste é cobrir caminhos, linhas e declarações do código.

Teste e cobertura de decisão
verifica as decisões diferentes no código e as instruções executadas a partir dela, se o teste de decisão deu 100% automaticamente o de instrução também será 100%, mas não ao contrário.
Nos casos de teste com instrução IF, testamos saída com resultado verdadeiro e outro falso.
Nas instruções CASE é necessário ter casos de testes para todos os possíveis resultados, incluindo o padrão.


DIFERENÇA ENTRE CAIXA PRETA E CAIXA BRANCA 
A Principal diferença entre, testes de caixa preta e branca são que>
Nos testes de Caixa Preta, verifica as operações e ações de uma aplicação, é baseado nos requisitos do cliente, trabalha no comportamento da ação, baseado em requisitos de negócio.
Quando falamos em teste de Caixa Branca ou estrutural, falamos da estrutura interna no ‘software’, sendo um teste mais complexo, pois testamos cada caminho e resposta a diferentes entradas, são escritos com base no documento de projeto detalhado, otimiza o código e ajuda a identificar erros ocultos e o seu foco e verificar se o caminho do código funciona ou não.
![Alt text](../../../../../Downloads/Estrat%C3%A9gia%20de%20Marketing%20(1).jpg)
![Alt text](Imagem%20caixa%20branca%20e%20preta.png)

fonte https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcQtdDlflwvAxPPQ_J5riojB1xx-TgTkBUQbMwBHweERyLuL3vAf


-- TESTE NÃO FUNCIONAL
verifica como o sistema se comporta, exige uma definição clara do que pode acontecer, O teste não funcional é baseado no requisito de desempenho. Podemos testar a performance, segurança, usabilidade... 
O teste não funcional, deve ser realizado em todos os níveis de testes, pois a descoberta tardia de erros não funcionais pode ser perigosa para o sucesso do ‘software’. 

Teste de Instalação e Configuração
baseasse em verificar o comportamento do sistema em diferentes configurações de ‘software’ e ‘hardware’, facilidade ou não de instalação e configuração.


Teste de Segurança
Avaliar a vulnerabilidade de segurança do ‘software’ em diferentes tipos de ataques de segurança, auxilia na criação de plano de contingência, para saber quais medidas a serem tomadas em casos de ataques, são vários tipos de testes não funcionais possíveis de serem realizados para testar a segurança, devem ser escolhidos os tipos conforme o que querem testar.

 
Teste de Usabilidade
O sistema deve ser de fácil entendimento e compreensão na manipulação do utilizador, este teste é feito em conjunto com reais utilizadores do sistema.

Teste de Performance
Teste que avalia a rapidez, robustez, velocidade de resposta, para termos o real desempenho em alta carga de trabalho, e considerando o seu comportamento em circunstâncias normais, o objetivo e garantir que o ‘software’ não apresente problemas ou indisponibilidades quando trabalhado em alta concorrência. 

DIFERENÇAS ENTRE TESTES FUNCIONAIS E NÃO FUNCIONAIS
A principal diferença entre os testes funcionais e não funcionais é que o funcional verifica o que o sistema faz, testa funções do sistema, com base nos requisitos e funções, e o teste não funcional testa como o sistema faz, como se comporta e é baseado em requisitos de desempenho.
Testes funcionais tem as seguintes características> testa o que o produto faz, testa operações e ações, realizado manualmente, testa de acordo com requisitos do cliente, temos os seguintes tipos>  unidade, integração, sistema e aceitação
Teste não funcional> feito com base na expectativa do cliente e nos requisitos de desempenho, tempo de resposta e velocidade do ‘software’ com condições especificas, testa a vulnerabilidade a ataques, e incluem testes como> usabilidade, segurança, desempenho, recuperação, volume... 






