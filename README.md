# Agência de Viagem
- Bárbara Bruna D'Áustole Gelape
- Douglas Fernandes de Carvalho Jardim
- Simone Antunes da Cruz Macedo
- Thomas Henrique Lousada
- Valéria Aparecida Santos

## Instituto de Informática e Ciências Exatas – Pontifícia Universidade Católica de Minas Gerais (PUC MINAS)
Belo Horizonte – MG – Brasil
barbaragelape@gmail.com, douglasfcj@hotmail.com, simonecruz.m@gmail.com, 1181893@sga.pucminas.br, valeria.santos.1327230@sga.pucminas.br

## Resumo. 
Escrevam aqui o resumo. O resumo deve contextualizar rapidamente o trabalho, descrever seu objetivo e, ao final, mostrar algum resultado relevante obtido (até 10 linhas).

# 1. Introdução 
A introdução deve apresentar de dois a quatro parágrafos de contextualização do trabalho. Na contextualização, o grupo de trabalho deve dizer do que se trata o trabalho, em que área ou contexto se insere. A contextualização deve ser desenvolvida de algo mais genérico para algo mais específico. A citação de pesquisas quantitativas é bem aceita aqui (corretamente referenciadas).
Em seguida, a equipe de trabalho deve detalhar o problema que o projeto pretende resolver, descrevendo sua motivação.
O grupo deverá escolher um contexto pertencente à lista de temas postados pelas professoras. Uma vez escolhido o contexto de negócio, o mesmo deverá ser estudado e detalhado pelo grupo por meio de pesquisa.

# 1.1. Objetivos geral e específicos 
O grupo deve escrever um pequeno parágrafo ou frase com o objetivo geral do trabalho. O objetivo deve ser bem direto, específico e definido com verbos de ação (elaborar, modelar, propor, avaliar, comparar,  etc).
Apresentem também, pelo menos, dois objetivos específicos dependendo de onde o grupo de trabalho concentrará sua prática investigativa ou aprofundará o trabalho.

# 1.2. Justificativas 
Mostrem também as justificativas para o desenvolvimento do trabalho e evidenciem alguma contribuição ou benefício do trabalho para o desafio proposto.

# 2. Participantes do processo de negócio
Identifiquem hipoteticamente os diferentes perfis dos Stakeholders (participantes do processo) chave do sistema. Procurem caracterizar os diferentes papéis desempenhados no(s) processo(s) relacionados ao tema escolhido pelo grupo. Cada papel desempenha funções diferentes no(s) processo(s).

![Stakeholders_imagem](https://user-images.githubusercontent.com/89228013/130331623-7a58189c-464f-42ae-8ef8-e148a1ee24d0.JPG)

# 3. Modelagem do processo de negócio

# 3.1. Análise da situação atual (AS-IS)
Com o tema do projeto definido, escolham alguns processos neste contexto de negócios. Para ilustrar potenciais ganhos com a automatização, imaginem processos manuais, ineficientes e/ou com muitas idas e vindas, gerando assim retrabalho.
Identifiquem e descrevam os problemas existentes nesta situação fictícia indesejada. 
Colem aqui a modelagem dos processos atuais (modelo AS-IS) realizada com o apoio da ferramenta baseada em BPM utilizada na disciplina.

# 3.2.  Modelagem dos processos aprimorados (TO-BE) 
Tendo identificado os gargalos do modelo AS-IS, apresentem uma descrição da proposta de solução, buscando maior eficiência com a introdução da tecnologia. Abordem também os limites dessa solução e seu alinhamento com as estratégias e objetivos do contexto de negócio escolhido. 
Colem aqui a modelagem da solução proposta (modelo TO-BE) realizada com o apoio da ferramenta baseada em BPM utilizada na disciplina.
Cada processo identificado deve ter seu modelo TO-BE específico. Descrevam as oportunidades de melhoria de cada processo da solução proposta. 

# 4. Projeto da arquitetura de dados da solução proposta

# 4.1. Diagrama de Entidades e Relacionamentos (DER)
O desenvolvimento da solução proposta requer a existência de bases de dados que permitam efetuar os cadastros de dados e controles associados aos processos identificados, assim como recuperações.
Utilizando a notação do DER (Diagrama de Entidades e Relacionamentos), elaborem um modelo, na ferramenta visual indicada na disciplina, que contemple todas as entidades e atributos associados às atividades dos processos identificados. Deve ser gerado um único DER que suporte todos os processos escolhidos, visando assim uma base de dados integrada. O modelo deve contemplar também o controle de acesso de usuários (partes interessadas dos processos) de acordo com os papéis definidos nos modelos do processo de negócio.

Colem aqui o DER confeccionado.

# 4.2. Impactos da implementação em um banco de dados NoSQL
Avaliem e descrevam as possibilidades, riscos e impactos do emprego de um banco de dados NoSQL para implementação da solução proposta.

# 4.3. Modelo relacional
Após a validação do DER, deve-se fazer seu mapeamento para o modelo relacional de banco de dados, observando-se as regras de normalização. Deve ser gerado um único modelo relacional que contemple todos os processos identificados. O modelo relacional deve ser diagramado na ferramenta visual indicada na disciplina. 
Colem aqui o modelo relacional elaborado.

# 5. Relatórios analíticos
Considerando as necessidades de informações das diversas partes interessadas nos processos eleitos, desenvolvam, com o apoio da ferramenta empregada na disciplina, relatórios úteis para o controle dos processos e a tomada de decisão.
Cada processo identificado deve possuir, no mínimo, um relatório analítico associado. Os relatórios devem utilizar os recursos de filtros, agregadores, agrupadores e ordenação disponibilizados pela ferramenta.
Cada relatório desenvolvido deve ter sua imagem apresentada aqui juntamente com a descrição de seus objetivos.  

 # 5.1. Associação de comandos SQL com relatórios analíticos
Após o desenvolvimento dos relatórios analíticos com o suporte da ferramenta empregada na disciplina, realizem um processo de engenharia reversa e codifiquem os comandos SQL-DML (selects) que produzem os relatórios automaticamente gerados. Preencham o formulário abaixo com esses comandos.
Nome do Relatório Analítico	Comando SQL-DML (SELECT)
	
	
	
	

# 6. Indicadores de desempenho
Com uma visão mais estratégica, identifiquem, a partir dos relatórios analíticos, indicadores chave de processo (KPIs – Key Process Indicator) que permitam um acompanhamento integrado dos vários processos eleitos. 
Detalhem,  na tabela abaixo, pelo menos cinco indicadores de desempenho identificados. Esses indicadores de desempenho devem ser descritos por meio de medidas estatísticas, conforme exemplo abaixo.
Indicador	Objetivo	Descrição	Fórmula de cálculo	Fontes de dados	Perspectiva
Percentual de reclamações	Avaliar quantitativamente as reclamações	Percentual de reclamações em relação ao total de atendimentos	(∑ reclamações)/(qte total de atendimentos)  *100	Tabela reclamações	Aprendizado e Crescimento
Taxa de Requisições abertas	Melhorar a prestação de serviços medindo a porcentagem de requisições	Mede % de requisições atendidas na semana	(nº req finalizadas)/(nº req abertas) *100	Tabela requisições	Processos internos
Taxa de entrega de material	Manter controle sobre os materiais que estão sendo entregues 	Mede % de material entregue dentro do mês	(qte materiais entregues)/(qte materiais solicitados)*100	Tabela pedidos	Clientes

# 7. Conclusão
Apresentem aqui a conclusão do trabalho que deve conter uma síntese dos principais resultados obtidos com a melhoria dos processos, uma discussão das limitações da solução proposta e sugestões de novas linhas de estudo. 

# REFERÊNCIAS
Como um projeto de software não requer revisão bibliográfica, a inclusão das referências não é obrigatória. No entanto, caso vocês desejem incluir referências relacionadas às tecnologias, padrões, ou metodologias empregadas no trabalho, relacione-as de acordo com a ABNT.
Verifiquem no link abaixo como devem ser as referências no padrão ABNT:
http://www.pucminas.br/imagedb/documento/DOC_DSC_NOME_ARQUI20160217102425.pdf
