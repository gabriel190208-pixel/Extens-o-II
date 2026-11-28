RELATÓRIO FINAL – TESTE, VALIDAÇÃO E CONCLUSÃO

Projeto de Extensão:
Laboratório de Laticínio

Integrantes:

Frederico Antonio Suzzin Rozin – RA: 60013940

João Victor Francescon – RA: 60013919

Gabriel Pizatto Thomas – RA: 60020832 

------------------------------------------------------------------------------------------------------------------------------
1. Contextualização e Resumo da Solução
   
O presente projeto teve como objetivo digitalizar e centralizar os registros de autocontrole do laboratório de um laticínio, substituindo
o controle manual baseado em papéis e planilhas dispersas. A solução modelada e implementada em protótipo contempla três módulos principais:
 
Registros Operacionais (Funcionário do Laboratório): lançamento de recebimento e análises do leite, controle de produtos, limpeza e
higienização, temperaturas, expedição e não conformidades, com vínculo automático de data, horário e responsável pelo registro.

Consultas e Acompanhamento (Responsável pelo Laboratório / Controle de Qualidade): consulta ao histórico digital, edição de registros,
acompanhamento da frequência dos controles e aplicação de filtros por data, período, produtor e tipo.

Relatórios e Segurança (Responsável pelo Laboratório / Controle de Qualidade): geração e impressão de relatórios gerenciais e de
auditoria, além de rotina de backup das informações.

------------------------------------------------------------------------------------------------------------------------------ 
2. Testes, Validação e Avaliação de Satisfação
   
Foram executados testes funcionais de fluxo com base nos casos de uso modelados e no protótipo desenvolvido, acompanhados de sessões
 de validação junto à equipe e à gerência do laticínio:

Fluxo de Lançamento e Rastreabilidade: validou-se que todo registro operacional exige obrigatoriamente a identificação do funcionário
responsável e a gravação automática de data e horário, garantindo rastreabilidade e evitando preenchimentos anônimos ou sem registro temporal.

Fluxo de Busca e Auditoria: os filtros combinados por data, produtor e tipo permitiram localizar registros históricos de forma imediata,
eliminando a necessidade de busca manual em arquivos físicos.

Geração de Relatórios e Segurança: a emissão de relatórios consolidados e a exportação de cópia de segurança demonstraram aderência às
exigências de controle de qualidade interno e fiscalização.

Avaliação de Satisfação dos Atores Envolvidos: a validação realizada com o Gerente do Laticínio apontou aprovação positiva da solução proposta.
Destacaram-se como principais benefícios a centralização das informações em um único ambiente, a redução no uso de papel, a maior segurança
contra extravio de documentos físicos e a agilidade na consulta de dados antigos durante inspeções ou verificações de rotina. 

------------------------------------------------------------------------------------------------------------------------------
3. Matriz de Atendimento dos Requisitos
   
ID	Requisito / Caso de Uso	Ator Principal	Status de Atendimento	Observações da Validação

RF01	Registrar recebimento e análises do leite	Funcionário do Laboratório	Atendido completamente	Fluxo modelado e validado no
protótipo com inclusão automática de responsável e data/hora.

RF02	Registrar controles de produtos, limpeza, temperaturas, expedição e não conformidades	Funcionário do Laboratório	Atendido
completamente	Todos os controles operacionais previstos na rotina do laboratório foram contemplados.

RF03	Identificar responsável e registrar data/horário automaticamente	Sistema	Atendido completamente	Regra aplicada como inclusão
obrigatória a todos os controles do laboratório.

RF04	Consultar histórico digital e editar registros	Responsável pelo Laboratório	Atendido completamente	Permite visualização rápida
do histórico e correção controlada de lançamentos.

RF05	Aplicar filtros (data, período, produtor e tipo)	Responsável pelo Laboratório	Atendido completamente	Implementado como extensão
da consulta de registros, agilizando buscas específicas.

RF06	Acompanhar frequência dos controles	Responsável pelo Laboratório	Parcialmente atendido	Contagem e visualização disponíveis, mas
ainda dependem de verificação manual do gestor, sem alertas automáticos.

RF07	Gerar e imprimir relatórios	Responsável pelo Laboratório	Atendido completamente	Fluxo integrado à consulta de registros para
emissão de documentos consolidados.

RNF01	Realizar backup das informações	Responsável pelo Laboratório	Parcialmente atendido	Exportação manual implementada no protótipo,
aguardando automatização em nuvem na implantação final. 

------------------------------------------------------------------------------------------------------------------------------
4. Limitações Identificadas e Sugestões de Melhoria
   
Durante a validação da arquitetura e dos testes com o protótipo, identificaram-se limitações técnicas que originaram as seguintes propostas
de melhoria para versões futuras do sistema:

Notificações e Alertas Automáticos: implementar avisos visuais ou sonoros caso algum controle periódico, como aferição de temperatura ou
higienização, não seja registrado dentro do intervalo previsto.

Operação Offline com Sincronização: permitir o preenchimento de dados sem conexão com a internet em áreas industriais ou câmaras frias
com oscilação de sinal, sincronizando automaticamente as informações assim que a rede for restabelecida.

Log de Auditoria em Edições: registrar o histórico detalhado de alterações (valor anterior, valor atualizado, data e autor da modificação)
sempre que a funcionalidade de edição de registros for utilizada, reforçando a conformidade sanitária.

Backup Automatizado em Nuvem: substituir o acionamento manual de cópia de segurança por rotinas diárias programadas em servidor externo. 

------------------------------------------------------------------------------------------------------------------------------
5. Conclusão Geral do Projeto
   
A aplicação prática das técnicas de Engenharia de Requisitos no contexto real do laboratório de laticínio permitiu transformar uma rotina
baseada em papéis e planilhas isoladas em uma especificação estruturada, rastreável e testável. O contato direto com os atores envolvidos
evidenciou a importância da rastreabilidade dos lançamentos e da rapidez na recuperação de históricos para o controle de qualidade. Como
resultado, a solução validada reduz falhas operacionais, evita a perda de registros críticos e estabelece uma base sólida para a implantação
definitiva do sistema no ambiente produtivo.
