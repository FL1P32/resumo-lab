# resumo-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO.
Acesse o Portal Azure

1-Entre em https://portal.azure.com

Faça login com sua conta Microsoft

2-Crie um Serviço de Banco de Dados

Clique em "Criar um recurso" (+)

Seleção "Bancos de dados" > "Banco de Dados SQL"

3-Configure o Banco de Dados

Assinatura: Selecione sua assinatura

Grupo de recursos: Crie um novo ou use existente

Nome do banco de dados: Dê um nome 

Servidor: Clique em "Criar novo" e preencha:

Nome do servidor

Localização (escolha a mais próxima de você)

Método de autenticação (recomendado "Usar autenticação do SQL")

Defina login e senha do administrador

4-Escolha o Tipo de Banco

Selecione a opção "Básico" para testes 

Ou "Standard" para produção

5-Configurações Adicionais

Na aba "Rede":

Selecione "Ponto de extremidade público"

Adicione seu IP atual como exceção de firewall

Na aba "Tags" (opcional):

Adicione tags para organização

6-Revise e Crie

Revise todas as configurações

Clique em "Criar"

7-Acesse seu Banco de Dados

Quando a implantação estiver concluída (pode levar alguns minutos)

Vá até "Todos os recursos" e selecione seu banco de dados

Use o "Editor de consultas" ou conecte via:

SQL Server Management Studio

Azure Data Studio

Sua aplicação
