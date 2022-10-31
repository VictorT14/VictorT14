 
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
 |30| Viagem Internacional?|	Incluir o campo “Viagem Internacional?” (mesmo campo do trecho)  entre o campo os campos "CPF" e "Passaporte".|	-	|-|
 |31|Número do Processo de Autorização (viagem internacional)	"Inserir o campo “Número do Processo de Autorização (viagem internacional)” após o campo ""Passaporte"".
Tipo: Texto com máscara (00000.000000/2020-00);
Visível e Necessário quando ""Viagem Internacional"" = ""Sim""."	|-	|-|
Número do Processo de Autorização (viagem internacional)	Incluir procedimento para integração com o SEI na autuação, anexação de documentos e tramitação do processo de viagem internacional.	-	-
![image](https://user-images.githubusercontent.com/101873549/199009022-8c0a03b0-9ee2-4266-a0c8-d961460a0e19.png)

 


