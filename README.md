# Indice de Pesquisa do Azure

Base de conhecimento: https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html#azure-resources-needed

Recursos do Azure necessários

A solução que você criará para o Fourth Coffee requer os seguintes recursos em sua assinatura do Azure:
- Um recurso de Pesquisa de IA do Azure, que gerenciará a indexação e a consulta.
- Um recurso de serviços de IA do Azure, que fornece serviços de IA para habilidades que sua solução de pesquisa pode usar para enriquecer os dados na fonte de dados com insights gerados por IA.
- Uma conta de armazenamento com contêineres de blob, que armazenará documentos brutos e outras coleções de tabelas, objetos ou arquivos.

# Criar um recurso de Pesquisa de IA do Azure

- 1 Entre no portal do Azure.
https://portal.azure.com/learn.docs.microsoft.com?azure-portal=true
- 2 Clique no botão + Criar um recurso, procure Pesquisa de IA do Azure e crie um recurso de Pesquisa de IA do Azure com as seguintes configurações:

Assinatura: sua assinatura do Azure.
Grupo de recursos: selecione ou crie um grupo de recursos com um nome exclusivo.
Nome do serviço: um nome exclusivo.
Localização: Escolha qualquer região disponível.
Nível de preços: Básico

- 3 Selecione Revisar + criar e, depois de ver a resposta Êxito da validação, selecione Criar.
- 4 Após a conclusão da implantação, selecione Ir para o recurso. Na página de visão geral da Pesquisa de IA do Azure, você pode adicionar índices, importar dados e pesquisar índices criados.

# Criar um recurso de serviços de IA do Azure

Você precisará provisionar um recurso de serviços de IA do Azure que esteja no mesmo local que seu recurso de Pesquisa de IA do Azure. Sua solução de pesquisa usará esse recurso para enriquecer os dados no armazenamento de dados com insights gerados por IA.

- 1 Retorne à home page do portal do Azure. Clique no botão +Criar um recurso e procure serviços de IA do Azure. Selecione criar um plano de serviços de IA do Azure. Você será levado a uma página para criar um recurso de serviços de IA do Azure. Configure-o com as seguintes configurações:

Assinatura: sua assinatura do Azure.
Grupo de recursos: o mesmo grupo de recursos que seu recurso de Pesquisa de IA do Azure.
Região: o mesmo local que seu recurso de Pesquisa de IA do Azure.
Nome: Um nome exclusivo.
Nível de preços: Standard S0
Ao marcar esta caixa reconheço que li e compreendi todos os termos abaixo: Selecionado

- 2 Selecione Revisar + criar. Depois de ver a resposta Validação aprovada, selecione Criar.
- 3 Aguarde a conclusão da implantação e exiba os detalhes da implantação.
