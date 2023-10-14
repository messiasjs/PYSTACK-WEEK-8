# PYSTACK-WEEK-8
# Sistema de Gerenciamento de Exames - Vitalab
O Sistema de Gerenciamento de Exames da Vitalab é uma aplicação web desenvolvida para auxiliar na gestão de exames médicos e pedidos de exames. Ele oferece várias funcionalidades para médicos, pacientes e administradores da clínica.

## Funcionalidades Gerais
O sistema inclui as seguintes funcionalidades gerais:

- Cadastro e Login de Usuários: Os usuários podem se cadastrar na plataforma e fazer login em suas contas. O registro é necessário para acessar a maioria das funcionalidades.

- Página Inicial (Home): A página inicial fornece um painel de controle com atalhos para as principais seções do sistema.

## Funcionalidades Relacionadas a Exames
As funcionalidades relacionadas a exames incluem:

- Solicitação de Exames: Médicos podem solicitar exames médicos para seus pacientes através do sistema.

- Fechamento de Pedidos: Após a solicitação de exames, os pedidos podem ser fechados, registrando as informações relevantes.

- Gerenciamento de Pedidos: Os administradores da clínica podem gerenciar todos os pedidos de exames, revisar e aprovar os pedidos.

- Cancelamento de Pedidos: Médicos e pacientes podem cancelar pedidos de exames específicos.

- Gerenciamento de Exames: Esta seção permite o acompanhamento e gerenciamento dos exames solicitados, com informações detalhadas.

- Permitir Abrir Exame: Médicos podem autorizar a visualização de exames específicos para os pacientes.

- Solicitação de Senha de Exame: Pacientes podem solicitar senhas para acessar exames específicos.

- Gerar Acesso Médico: Permite a geração de tokens de acesso médico para autorização de acesso a informações específicas de pacientes.

- Acesso Médico: Médicos podem acessar informações de pacientes através de tokens de acesso médico.

## Funcionalidades Relacionadas a Clientes Empresariais
Para clientes empresariais, as funcionalidades incluem:

- Gerenciamento de Clientes: Administradores podem gerenciar clientes empresariais e suas informações.

- Visualização de Cliente: Visualização detalhada das informações do cliente empresarial.

- Exame do Cliente: Visualização de exames associados a um cliente empresarial específico.

- Proxy PDF: Geração de arquivos PDF a partir dos dados dos exames.

- Gerar Senha: Geração de senhas para exames específicos.

- Alteração de Dados do Exame: Médicos e pacientes podem atualizar informações de exames específicos.

## Instalação
- Clone o repositório.

- Instale as dependências.

- Configure as variáveis de ambiente necessárias, como configurações de banco de dados e segurança.

- Execute o servidor de desenvolvimento com python manage.py runserver.

- Acesse o sistema em http://localhost:8000/ (ou a URL específica do seu ambiente).
