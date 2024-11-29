
<img src ="../177353242.png"/>

# Venturo ERP 


## Integrantes
- **Guilherme Veiga Pedromilo**: Product Owner (PO) e Back-end
- **Isabela Teixeira dos Santos**: Front-end
- **Caio Felipe Vieira Ferreira**: Front-end
- **João Pedro Araújo Teixeira**: Full-Stack

## Objetivo
Venturo é um sistema ERP (Enterprise Resource Planning) desenvolvido pela equipe Venturo's, projetado como um sistema SAAS (Software como Serviço) Multi-Tenant com Multi-Schemas. O objetivo do Venturo é oferecer uma solução abrangente de gestão empresarial, melhorando a eficiência e produtividade das empresas por meio do controle de estoque, vendas, financeiro e gestão de funcionários.

## Perfis de Usuário
### 1. SuperAdmins
- Acesso completo ao sistema.
- Destinado à equipe Venturo's.

### 2. Gestores
- Proprietários das empresas clientes.
- Acesso exclusivo ao banco de dados da própria empresa.
- Podem registrar, excluir e alterar informações de funcionários.

### 3. Outros Perfis em Definição
- Detalhes sobre outros perfis serão definidos posteriormente.

## Frameworks
- Docker
- Node.js
- Figma
- GitHub
- Visual Studio Code
- MySQL Workbench
- Express

## Bibliotecas
- React
- Vite
- Recharts
- React Icons
- Knex.js
- JWT
- Bcrypt
- Dotenv

## Outras Tecnologias
- Computadores ou Notebooks
- Acesso à Internet

## Requisitos Não Funcionais
- **Desempenho**: O sistema deve ser rápido e eficiente, capaz de lidar com um grande número de transações simultâneas.
- **Segurança**: Implementação de práticas robustas de segurança, incluindo autenticação JWT e criptografia de senhas com Bcrypt.
- **Usabilidade**: Interface intuitiva e fácil de usar, baseada em designs de UX modernos.
- **Escalabilidade**: Capacidade de escalar para suportar um número crescente de usuários e dados sem degradação de desempenho.
- **Confiabilidade**: O sistema deve ser altamente disponível e resiliente a falhas.

## Funcionalidades
### Plano de Contas
- **Cadastro de Contas**: Registro de novas contas contábeis no sistema.
- **Hierarquia de Contas**: Define a estrutura hierárquica das contas.
- **Razão**: Consulta detalhada da razão contábil.
- **Balancete**: Visualização do balancete contábil, com filtros por período.
- **DRE (Demonstração do Resultado do Exercício)**: Visualização da DRE e comparação de períodos.

### Contas a Pagar
- **Cadastro de Fornecedores**: Registro de informações sobre fornecedores.
- **Lançamento de Despesas**: Registro de despesas no sistema.
- **Pagamentos Programados**: Agendamento e gestão de pagamentos futuros.

### Contas a Receber
- **Cadastro de Clientes**: Registro de informações sobre clientes.
- **Lançamento de Receitas**: Registro de receitas no sistema.
- **Recebimentos Programados**: Agendamento e gestão de recebimentos futuros.
- **Fluxo de Caixa**: Monitoramento do fluxo de caixa.

### Estoque
- **Registro de Produtos**: Registro de novos produtos.
- **Atualização de Informações de Produtos**: Atualização das informações dos produtos.
- **Movimentações**: Registro de entradas e saídas de produtos no estoque, com histórico detalhado.

### Vendas
- **Emissão de Notas Fiscais**: Registro e emissão de notas fiscais.
- **Pedidos**: Registro e consulta de pedidos de venda.
- **Clientes**: Registro de informações detalhadas sobre clientes e histórico de compras.
- **Relatórios de Vendas**: Geração de relatórios detalhados de vendas por produto e por cliente.

### Dashboard
- **Visão Geral**: Visão geral e interativa do desempenho empresarial com gráficos e indicadores chave.

### Cadastro de Usuários
- **Perfis e Permissões**: Definição de perfis de usuários e configuração de permissões de acesso.

### Auditoria
- **Log de Ações de Usuários**: Registro detalhado das ações realizadas por cada usuário.
- **Relatórios de Auditoria**: Geração de relatórios detalhados para auditoria e controle interno.

### Suporte e Comunicação
- **Sistema de E-mail entre Usuários**: Comunicação entre funcionários da empresa.
- **Comunicação Direta com o Suporte**: Envio de mensagens diretamente para a equipe Venturo.

