# chatbot

# Intenções utilizadas>
{"intents":[
  { "tag": "saudacao",
    "patterns":["Ola","Opa","Oi", "tudo bem"],
    "responses": ["Oi","Olá"]
  },
  { "tag": "despedida",
    "patterns":["valeu","tchau","Obrigado","tks"],
    "responses": ["Até breve","Falou"]
  },
  { "tag": "data_prova",
    "patterns":["Quando sera a prova?","A prova será em que dia?"],
    "responses": ["no dia 26"]
  },
  { "tag": "pipe1",
    "patterns": ["Oque é um progama PIPE","Oque é PIPE?"],
    "responses": ["O Programa Pesquisa Inovativa em Pequenas Empresas da FAPESP destina-se a apoiar a execução de pesquisa científica e tecnológica em pequenas empresas no Estado de São Paulo. Seus objetivos são apoiar a pesquisa em ciência e tecnologia como instrumento para promover a inovação tecnológica e o desenvolvimento empresarial, aumentar a competitividade das pequenas empresas, possibilitar que as empresas se associem a pesquisadores do ambiente acadêmico em projetos de pesquisa visando à inovação tecnológica e contribuir para a formação e o desenvolvimento de núcleos de desenvolvimento tecnológico nas empresas e para o emprego de pesquisadores no mercado de trabalho empresarial criando uma cultura permanente de inovação." ]
  },
  { "tag": "pipe2",
    "patterns": ["Há diferentes etapas no programa?","Quantas etapas tem o progama?"],
    "responses": ["a) Fase 1: é destinada à verificação da viabilidade técnico-científica da proposta, (duração de até 9 meses e orçamento de até R$ 300.000, mais Reserva Técnica e Benefícios Complementares);\nb) Fase 2: destina-se à execução da pesquisa propriamente dita (duração de até 24 meses e orçamento de até R$ 1.500.000, mais Reserva Técnica e Benefícios Complementares);\nc) PIPE Invest: Aceleração da chegada ao mercado de Projetos da Fase 2, quando houver terceira parte interessada (duração de até 24 meses e orçamento de até R$ 1.500.000); \nd) Fase 3: desenvolvimento comercial e industrial dos produtos, processos, sistemas e/ou serviços inovadores obtidos a partir de pesquisas anteriores realizadas pela pequena empresa sem o apoio da FAPESP ou a partir de pesquisa apoiada no âmbito do PIPE." ]
  },
  { "tag": "pipe3",
    "patterns": ["A fase 1 é obrigatória?","Posso ir direto para a fase 2?"],
    "responses": ["A empresa pode submeter uma proposta à Fase 2 Direta. Nesse caso é fundamental demonstrar que a viabilidade técnica da pesquisa já foi demonstrada; para tanto é fundamental apresentar um ótimo documento de “Justificativa para a Fase 2 Direta”." ]
  },
  { "tag": "pipe4",
    "patterns": ["O projeto de pesquisa tem que ser feito na empresa?","Precisa ser feito na empresa?"],
    "responses": ["Sim, obrigatoriamente. O PIPE destina-se a apoiar a execução de pesquisa EM pequenas empresas sediadas no Estado de São Paulo, conforme está explicitado nas normas do programa." ]
  },
  { "tag": "pipe5",
    "patterns": ["Preciso já ter empresa para solicitar o PIPE?","Preciso ter uma empresa?"],
    "responses": ["Não. A FAPESP analisa propostas de empresas ainda não constituídas. Empresas startup ainda não constituídas legalmente são incentivadas a submeter. Nos casos em que a proposta for recomendada, o proponente deverá então abrir formalmente a empresa antes da concessão da proposta." ]
  },
  { "tag": "pipe6",
    "patterns": ["Oque é uma empresa para fins de submissão ao PIPE?","Oque é uma empresa de fins de subimissão?"],
    "responses": ["É uma empresa com até 250 funcionários, independentemente do seu faturamento. A FAPESP considera empresa as sociedades empresárias previstas no Código Civil, o empresário individual, o microempreendedor individual (MEI), a sociedade limitada unipessoal e as sociedades simples. Associações, fundações, institutos e cooperativas não podem sediar um PIPE da FAPESP." ]
  },
  { "tag": "pipe7",
    "patterns": ["Quando posso submeter uma proposta ao PIPE","Quando posso ter uma proposta?"],
    "responses": ["As propostas para o PIPE Fase 1, Fase 2 e PIPE Invest são recebidas em fluxo contínuo durante todo o ano." ]
  },
  { "tag": "pipe11",
  "patterns":["Possuo formação em uma área, posso submeter um projeto em outra área?", "Posso submeter um projeto sem ter experiência na área?", "Pode submeter projeto de área diferente da área de formação?"],
  "responses": ["No PIPE, o fundamental é demonstrar experiência na área do projeto. É importante que a equipe inclua profissionais de todas as áreas relevantes para a pesquisa.\n No entanto, nem todos os membros da equipe precisam ter relação direta com a empresa; podem ser incluídos na equipe especialistas de universidades e consultores, remunerados ou não, para complementar as especialidades necessárias à condução da pesquisa.\n Por exemplo, um projeto que envolve o desenvolvimento de um software para a saúde obrigatoriamente deve incluir na equipe especialistas em desenvolvimento de software e em saúde e um projeto que envolve o uso de eletrônica na agricultura obrigatoriamente deve incluir especialistas em eletrônica e em agricultura."]
  },
  { "tag": "pipe12",
  "patterns":["Preciso ter dedicação exclusiva ao projeto?", "Preciso me dedicar apenas a esse projeto?"],
  "responses": ["Caso o pesquisador principal seja pago pela empresa e não receba bolsa da FAPESP, é exigida a dedicação mínima de 24 horas semanais ao projeto na empresa. Em casos excepcionais,\n em que a empresa demonstra não poder arcar com o salário do Pesquisador Responsável, a FAPESP pode analisar solicitação de Bolsa de Pesquisa em Pequena Empresa (Bolsa PE FAPESP). Se o pesquisador principal solicitar\n Bolsa PE, é necessária a dedicação mínima de 40 horas semanais ao projeto."]
  },
  { "tag": "pipe13",
  "patterns":["Pesquisadores e/ou empresas fora do estado de são paulo podem apresentar projetos?", "Pesquisadores fora do estado de são paulo podem apresentar projetos?", "Empresas fora do estado de são paulo podem apresentar projetos?"],
  "responses": ["O Pesquisador Responsável deverá residir no estado de São Paulo para ser elegível ao PIPE. Caso a empresa já esteja constituída fora do estado de São Paulo,\n o pesquisador deverá submeter o projeto, obrigatoriamente, em nome dessa empresa. Ter unidade de pesquisa constituída no estado de São Paulo (item 3.3 da norma) é condição para a concessão do processo. Adicionalmente, pesquisadores de outros estados que venham \n a instalar novas empresas em São Paulo e se tornem residentes no estado, também são elegíveis."]
  },
  { "tag": "pipe16",
  "patterns":["Posso desenvolver a pesquisa na universidade?", "Posso desenvolver a pesquisa na faculdade?", "Posso fazer a pesquisa na universidade?"],
  "responses": ["Não. A pesquisa deve ser desenvolvida na empresa. Eventualmente, algumas atividades específicas da pesquisa podem ser sub-contratadas de laboratórios de universidades\n ou de consultores acadêmicos desde que muito bem justificadas e não se constituam na parte central da pesquisa."]
  },
  { "tag": "time",
  "patterns":["Que time você torçe?","Qual seu time preferido?"],
  "responses": ["Corinthians", "Flamengo", "Santos"]
  },
  { "tag": "pipe21",
  "patterns":["Que outros itens são financiaveis", "Qual item é financiavel?"],
  "responses": ["Além das bolsas PE e TT e de recursos para viagens, são também financiáveis Serviços de Terceiros, Material\n Permanente e Material de Consumo. Estes podem ser adquiridos tanto no Brasil quanto no exterior. Em todos os casos, é\n fundamental que eles sejam bem justificados como essenciais à pesquisa científica ou tecnológica que será desenvolvida\nno âmbito do projeto. Não são financiáveis itens de produção ou que não sejam essenciais à pesquisa proposta, mesmo\nque possam ter utilidade para a empresa."]
  },
  { "tag": "pipe22",
  "patterns":["Posso contratar consultores? Como fica a Propriedade Intelectual", "Posso contratar consultores?", "Como fica a propriedade intelectual?"],
  "responses": ["Sim. Desde que bem justificado, é possível contratar Serviços de Terceiros de especialistas, de laboratórios acadêmicos ou de outras empresas. No caso de envolvimento de terceiros, prestadores de servi ços ou parceiros no projeto, a relação deverá estar formalizada antes da concessão do projeto, considerando que:\n a) Para os casos em que a participação do terceiro for de consultoria ou prestação de serviços, com remuneração com recursos do projeto ou da empresa, deverá ser apresentado contrato de prestação de serviços. Neste caso, a propriedade intelectual deve ser de propriedade exclusiva da pequena empresa.\n b) Caso a consultoria seja realizada por pesquisador de instituição pública, deverão ser apresentados:\n b.1) ofício da agência de inovação da respectiva Instituição de vínculo do pesquisador, concordando com a não participação na propriedade intelectual;\n b.2) autorização do órgão de pessoal da instituição para a consultoria; e\n b.3) contrato entre o consultor e a empresa prevendo que a titularidade pertencerá à empresa.\n c) Para os casos em que houver colaboração entre a pequena empresa e o terceiro, poderá haver compartilhamento de propriedade intelectual, devendo ser apresentado convênio, detalhando no plano de trabalho qual a participação do terceiro e da empresa na pesquisa, bem como indicando quais serão os recursos financeiros e econômicos envolvidos para financiar as pesquisas do convênio e a origem de tais recursos.\n d) Em qualquer caso, a pequena empresa deve ter o direito de explorar com exclusividade os resultados da pesquisa.\n A atenção e cuidado profissional com os assuntos de Propriedade Intelectual é essencial para preservar o valor da empresa e de suas inovações e para viabilizar a obtenção de investimentos privados."]
  },
  { "tag": "pipe23",
  "patterns":["Posso usar recursos Pipe para pagamento de despesas relativas a proteção de propriedade intelectual como patenteamento?"],
  "responses": ["Despesas com propriedade intelectual poderão ser financiadas com recursos da Parcela para Custos de Infraestrutura Direta do Projeto."]
  },
  { "tag": "pipe24",
  "patterns":["O Apoio da FAPESP é um emprestimo?"],
  "responses": ["O apoio da FAPESP não é realizado na forma de empréstimo."]
  },
  { "tag": "pipe25",
  "patterns":["A FAPESP fica com uma parcela da empresa? Ela torna-se sócia da empresa?", "A FAPESP fica com uma parcela da empresa?", "Ela torna-se sócia da empresa?"],
  "responses": ["Não, a FAPESP não recebe cotas da empresa."]
  }
]
}

# Exemplo de funcionamento do bot

![image](https://github.com/bieltanaka11/chatbot/assets/85264276/32e03d07-58be-43fb-9a20-6f1e40fea215)

# Link com vídeo de demonstração do funcionamento

https://www.veed.io/view/fe482271-8661-4689-a6c1-558a8b72ccfc?panel=share

# Autores
                                                                                                                                                                                
  Enzo Benvenuti                                                                                                                                                             
  Gabriel Carvalho                                                                                                                                                            
  Leonardo Guerra 
