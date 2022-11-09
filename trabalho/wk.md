 
 |-| Campo | Solitação/Comentário                 | texto atual| Alterar para |
 |-|-|--------------------------------------|------------|--------------|
 |21|-| Incluir ação "Descartar Solicitação" | - |	- |
 |22|Status|Bloquear edição do campo | - | - |
 |23|Entidade de Negócios|"Deve ser possível alterar a UDVD após a criação da solicitação, mas acredito que não é possível alterar na forma atual pois após a criação a UDVD   torna-se a pai da solicitação.Minha sugestão nesse caso seria que se criasse um pai padrão, já selecionado previamente em todas as solicitações." |-|-|
 |24|Servidor Solicitante|Alterar rótulo|Servidor Solicitante|Servidor (Proposto)|
 |24|Servidor Solicitante|Incluir descrição|Beneficiário da PCDP|-|
 |24|Servidor Solicitante|Preencher o campo com o nome do criador da solicitação|-|-|
 |24|Servidor Solicitante|Necessário = "Verdadeiro"|-|-|
 |25|Servidor Solicitante|Alterar rótulo|Secretaria Responsável| Solicitante SCDP|
 |25|Secretaria Responsável|Alterar descrição|-|-|
 |25|Secretaria Responsável|Filtrar o Solicitante SCDP de acordo com a unidade|-|-|
 |25|Secretaria Responsável|Necessário = "Verdadeiro"|--|-|
 |26|Gestor Superior Imediato|	Alterar rótulo|	Gestor Superior Imediato|	Superior Imediato|
 |26|Gestor Superior Imediato|	Alterar descrição|	gestor_superior_imediato|	Superior imediato do beneficiário da PCDP.|
 |26|Gestor Superior Imediato|	O superior imediato deve ser distinto do solicitante|	-|	-|
 |26|Gestor Superior Imediato|	Selecionar o superior imediato automaticamente de acordo com a unidade do servidor|	-|	-|
 |26|Gestor Superior Imediato|	Necessário = "Verdadeiro"	|-|	-|
 |27|Responsável GTAG|	Alterar rótulo|	Responsável GTAG|	Revisor da Solicitação|
 |27|Responsável GTAG|	Alterar descrição|	responsavel_gtag	|Revisor das informações cadastradas.|
 |27|Responsável GTAG|	Selecionar automaticamente o Revisor da Solicitação de acordo com a unidade|	-|	-|
 |27|Responsável GTAG|	Necessário = "Verdadeiro"|	-|	-|
 |28| -	|"Alterar posição dos campos para seguir a ordem de execução: Servidor (Proposto); Superior Imediato; Revisor da Solicitação; Solicitante SCDP."|	-|	-|
 |29|CPF (999.999.999-99)	|Alterar rótulo|	CPF (999.999.999-99)	|CPF|
 |29|CPF (999.999.999-99)	|Alterar descrição	cpf_servidor	CPF do Beneficiário da PCDP
 |29|CPF (999.999.999-99)	|"Permitir somente a inclusão de caracteres numéricos no campo CPF, aplicando a máscara “999.999.999-99” à medida que o campo for preenchido. 
 "|	-|-|
 |29|CPF (999.999.999-99)	|Travar o campo CPF na quantidade máxima de caracteres.|	-|	-|
 |29|CPF (999.999.999-99)	|Incluir validação do número do CPF.|	-	|-|
 |30|Viagem Internacional?|	Incluir o campo “Viagem Internacional?” (mesmo campo do trecho)  entre o campo os campos "CPF" e "Passaporte".|	-	|-|
 |30|Viagem Internacional?| Alterar descrição|	viagem_internacional |	Viagem internacional?|
 |30|Viagem Internacional?|Incluir aviso de que os campos "Número do Processo de Autorização" e "Passaporte" são necessários quando "Viagem Internacional" = "Sim".|	-|	O "Número do Processo de Autorização" e o "Passaporte" são obrigatórios para viagens internacionais.|
 |31|Número do Processo de Autorização (viagem internacional)|	"Inserir o campo “Número do Processo de Autorização (viagem internacional)” após o campo ""Passaporte"".Tipo: Texto com máscara (00000.000000/2020-00);Visível e Necessário quando ""Viagem Internacional"" = ""Sim""."
 |31| Número do Processo de Autorização (viagem internacional)|	Incluir procedimento para integração com o SEI na autuação, anexação de documentos e tramitação do processo de  viagem internacional.|	-	|-|
|32|Passaporte (AB123456)|Permitir somente a inclusão de caracteres alfanuméricos no campo Passaporte.|-	|-|
|32|Passaporte (AB123456)|Alterar descrição|passaporte_servidor|Passaporte do beneficiário da solicitação|
|32|Passaporte (AB123456)|Travar o campo Passaporte na quantidade máxima de caracteres.-	|-|
|32|Passaporte (AB123456)|O campo Passaporte somente deve ser exibido quando se tratar de viagem internacional.|-	|-|
|32|Passaporte (AB123456)|O campo Passaporte deve ser obrigatório caso "Viagem Internacional?" = "Sim"|-	|-|
|33|	-|	Alterar aviso|	"Modo apenas de visualização A visualização de tarefas será editável assim que o flyover do Quick View for fechado."|	"Modo apenas de visualização A visualização de tarefas será editável assim que o painel lateral for fechado."|
|34| Descrição do motivo da viagem	|Excluir campo|	-	|-|
|35| Despacho de bagagem?|	Alterar descrição|	despacho_bagagem	| O servidor necessitará despachar bagagem?|
|35| Despacho de bagagem?| ecessário = "Verdadeiro", Padrão = "Não"|	-|	-|
|35| Despacho de bagagem?|	Incluir aviso caso "Despacho de bagagem?" = "Sim".|-	|Viagens de até dois pernoites não permitem o despacho de bagagem.|
|36| Viagens em Urgência/finais de semana?|	Alterar rótulo	|Viagens em Urgência/finais de semana?|	Viagens em urgência, finais de semana ou feriado?|
|36| Viagens em Urgência/finais de semana?|	Necessário = "Verdadeiro"|	-|	-|
|36| Viagens em Urgência/finais de semana?|	Alterar descrição|	viagens_urgencia_finais_semana|	Selecione "Sim"  no caso de viagem solicitada em prazo inferior ao definido pela SAF ou que deva ser realizada durante finais de semana ou feriados.|
|36| Viagens em Urgência/finais de semana?|	Incluir aviso caso "Viagens em Urgência/finais de semana?" = "Sim".|	-	|"Informe as circunstâncias da urgência (imprevisibilidade, inviabilidade de agendamento posterior ou risco institucional) ou as justificativas para a solicitação de diárias em finais de semana no campo ""Observações - PCDP"".|
|37| Observações - PCDP|	Alterar descrição|	observacoes_PCDP|	Observações adicionais da solicitação.|
|38| Viagem com Origem Diversa da Localidade de Exercício?|	Alterar descrição|	viagem_origem_diversa_localidade_exercicio|	Informar "Sim" no caso de concessão de diárias e passagens que tenham por objeto a emissão de bilhete aéreo com origem diversa da localidade da unidade organizacional, para participante do Pacto ANAC+, em que o servidor esteja em exercício, de acordo com o previsto na Portaria Nº 7.016/SAF, de 19 de janeiro de 2022.|
|38|Viagem com Origem Diversa da Localidade de Exercício?|	Necessário = "Verdadeiro"|	-|	C|
|38|Viagem com Origem Diversa da Localidade de Exercício?|		Alterar aviso|		Para viagem com origem diversa da localidade em exercício, os gastos com passagens para locomoção diversa fica sob responsabilidade do servidor.	|	"Para solicitação de viagem com origem diversa do local de exercício, o servidor deverá autuar o devido processo conforme orientações da SAF:https://intranet.anac.gov.br/servicos/saf/viagens-e-deslocamentos/concessao-de-diarias-e-passagens-aereas-com-origem-diversa-da-localidade-de-exercicio-do-servidor; https://extranet.anac.gov.br/servicos/saf/viagens-e-deslocamentos/concessao-de-diarias-e-passagens-aereas-com-origem-diversa-da-localidade-de-exercicio-do-servidor; Os eventuais custos adicionais deverão ser ressarcidos pelo servidor."|	
|38|	Viagem com Origem Diversa da Localidade de Exercício?|	Incluir procedimento para integração com o SEI na autuação, anexação de documentos e tramitação do processo de "Solicitação de Viagem com Origem Diversa da Localidade de Exercício".	| - | 	- |
|39| Documento Motivador|	Ocultar ou bloquear campos não utilizados “IdDocumento”.	 | -	| - |
|39| Documento Motivador|	Do que se trata esse campo “Assinaturas”? |	-	|-|
|39| Documento Motivador|	Devo efetuar o check-out? Qual o efeito? |	-	|- |
|40| Localidade Onde Ocorrerá a Atividade | Alterar descrição  |	localidade_onde_ocorrera_atividade	| Local (Cidade/UF) e endereço onde a atividade será realizada.|
|40| Localidade Onde Ocorrerá a Atividade |	Necessário = "Verdadeiro"|	-|	-|
|41| Data de Início da Missão	|Alterar descrição|	data_inicio_missao|	Data de início da atividade.|
|41| Data de Início da Missão	|Necessário = "Verdadeiro"|	-|	-|
|41| Data de Início da Missão	|Importar a informação da Fiscalização("Início Planejado - Execução") quando for o caso.|	-|	-|
|41| Data de Início da Missão	|Incluir Regra: Maior que ou igual a Hoje|	-|	-|
|42| Horário de Início da Missão|	Alterar descrição	|horario_inicio_missao	|Horário de início da atividade.|
|42| Horário de Início da Missão|	Aceitar somente números aplicando a máscara de hora enquanto o texto é digitado.|	-|	-|
|43| Data de Término Prevista	|Alterar descrição	|data_termino_prevista|	Data prevista pra o término da atividade.|
|43| Data de Término Prevista	|Necessário = "Verdadeiro"|	-|	-|
|43| Data de Término Prevista	|Importar a informação da Fiscalização (Término Planejado - Execução) quando for o caso.|	-|	-|
|43| Data de Término Prevista	|Incluir Regra: Maior que ou igual a "Data de Início da Missão"|-	|-|


|44|Horário de Término Prevista|	Alterar descrição|	horario_termino_prevista|	Horário previsto para o término da atividade.|
|44|Horário de Término Prevista|	Aceitar somente números aplicando a máscara de hora enquanto o texto é digitado.|	-|	-|


|45| Cumprirá expediente antes do Embarque?|	Alterar descrição|	cumprira_expediente_antes_do_Embarque|	Informar caso o servidor tenha que cumprir expediente antes do embarque no trecho inicial de ida.|
|45|Cumprirá expediente antes do Embarque?|	Necessário = "Verdadeiro"|	-|	-|
|45|Cumprirá expediente antes do Embarque?	|"Alterar tipo para lista com as seguintes opções: Não (Padrão); e Sim;"|	-|	-|

|46| Horário de Término do Expediente	"Incluir campo do tipo hora.
Descrição: Horário de Término do Expediente
Visível e Necessário caso ""Cumprirá expediente antes do Embarque?"" = ""Sim"""	-	-

|47|Cumprirá expediente após o Desembarque no Retorno da Missão?	Alterar descrição	cumprira_expediente_apos_desembarque_retorno_missao	Informar caso o servidor tenha que cumprir expediente após o desembarque no trecho final de volta.

|47|Cumprirá expediente após o Desembarque no Retorno da Missão?	Necessário = "Verdadeiro"	-	-
|47|Cumprirá expediente após o Desembarque no Retorno da Missão?	"Alterar tipo para lista com as seguintes opções: 
Não (Padrão); e
Sim;
"	-	-

|48| Horário de Início do Expediente	"Incluir campo do tipo hora.|Descrição: Horário de Término do Expediente Visível e Necessário caso ""Cumprirá expediente após o Desembarque no Retorno da Missão?"" = ""Sim"""	-	-

|49|Idenficação de alguma dificuldade Logística com Relação ao seu deslocamento	Alterar descrição	idenficacao_dificuldade_logistica_deslocamento	Dificuldades logísticas em relação ao deslocamento que devam ser observadas na concessão da PCDP.
|49|Idenficação de alguma dificuldade Logística com Relação ao seu deslocamento	Necessário = "Verdadeiro"	-	-


|50|Tempo de deslocamento Aeroporto/Missão - Missão/Aeroporto (min)	Alterar descrição	tempo_deslocamento_aeroporto_missao_missao_aeroporto	Tempo de deslocamento do aeroporto até o local da missão, contado em minutos. O valor 0 deve ser informado caso não se aplique.
|50|Tempo de deslocamento Aeroporto/Missão - Missão/Aeroporto (min)	Necessário = "Verdadeiro"	-	-

|51|Horário previsto para uso de outro meio de transporte após/antes do deslocamento aéreo	Alterar descrição	horario_previsto_uso_outro_transporte_apos_antes_deslocamento	Horário previsto para uso de outro meio de transporte após/antes do deslocamento aéreo.


|52|Proposta de Voos	|Alterar descrição	proposta_voos	|Informar os voos propostos.|
|52|Proposta de Voos|	Necessário = "Verdadeiro"|	-	|-|

|53| Tipo de viagem	|"Incluir o campo “Tipo de viagem” do tipo lista no início da seção com as seguintes opções:
Ida e Volta (padrão); Somente Ida; e Somente Volta."|	-|	-|
|54| -	|Alterar texto do aviso	"Atenção ao Preenchimento O preenchimento dos trechos de viagem deve conter no mínimo dois trechos, um com etapa de deslocamento de Ida e outro com etapa de deslocamento de Volta."|	"Atenção ao Preenchimento O preenchimento dos trechos de viagem deve conter no mínimo: Um trecho de ida e um trecho de volta para viagens de Ida e Volta; Um trecho de ida , para viagens só de ida; ou Um trecho de volta para viagens só de volta."|













