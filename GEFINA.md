# GEFINA
*sistema de gestão de contas a receber*

serão 6 etapas (sprints) para a construção, cada entrega termina com uma versão publicada e funcional do sistema.
deverá ser acessível por endereço publico.

interface responsiva.

* gerenciador de user com niveis de permissão

* niveis
- super user
- user gerente

- users geral
*altera fatura mas nao deleta*

*um cliente so pode ser removido se nao tiver uma fatura atrelada a ele*

* tela 1 com dashboard
- total recebido geral
- total de valores pendentes
- numeto total de faturas
- numero total de clientes

* no final
- 5 ultimos clientes e 5 ultimas faturas

cad
- clientes
- faturas de clientes
- status (situação da divida)

* clientes e faturas listados de 10 em 10
* 2 colunas clientes / faturas
* listar por ordem de data de cadastro (desc)
*a tela de acesso a clientes e faturas deverá ter filtro*

* todos podem vizualizar as faturas criadas de todos
* somente quem criou a fatura pode 

* pode alterar o adm do cliente

-----------------------------
o sistema obedecerá as boas praticas do cliclo de desenvolvimento
# ciclo de desenvolvimento

- levantamento de requisitos
- protiotipação
- modelagem
- desenvolvimento
- qualidade
- homologação

-
dominio: O Sistema
-----------------------------------
requisito funcional: ponto de vista de quem utiliza o sistema. (não preciso de informações tecnicas para entender)
requisito não funcional: detalhes tecnicos de formatação. ex: linguagem, validação de caracteres, tipos de upload etc.
-----------------------------------

# Entidades
algo do dominio que eu preciso armazenar
*ex:*
- usuarios
- faturas
- clientes
-
----------------------------
# Atributos

* usuarios
- nome
- email
- senha
- papel (tipo de usuário)

* clientes
- nome
- endereço
- imagem (não obrigatorio)

* faturas
- valor
- situação (pendente, paga, atrasada)
- data de emissão
- data de vencimento