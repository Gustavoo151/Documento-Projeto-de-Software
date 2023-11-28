## Documentação do Projeto
# Sistema de Gestão de Agendamentos de Consultas

## Descrição e Escopo do Projeto

O Sistema de Gestão de Agendamentos de Consultas tem como objetivo facilitar a marcação de consultas médicas, permitindo que os usuários escolham e agendem consultas com médicos de sua preferência. O sistema fornecerá um catálogo completo de médicos, informações sobre especialidades e disponibilidade de horários, facilitando a escolha do profissional mais adequado.

[Documentação do projeto](https://docs.google.com/document/d/13gOxzB8zuAYRwqVptxj26siFOf7ejXupTKV4tazTGkE/edit?usp=sharing)
## Requisitos Funcionais

### Autenticação e Usuários
- [RF01] Efetuar login
- [RF02] Efetuar logoff
- [RF03] Cadastrar Usuário
- [RF04] Ler Usuário
- [RF05] Atualizar Usuário
- [RF06] Deletar Usuário

### Consultas
- [RF08] Cadastrar Consulta
- [RF09] Ler Consulta
- [RF10] Atualizar Consulta
- [RF11] Deletar Consulta

### Médicos
- [RF16] Cadastrar Médico
- [RF17] Ler Médico
- [RF18] Atualizar Médico
- [RF19] Deletar Médico
- [RF13] Filtrar Médicos

### Administradores do Sistema
- [RF21] Adicionar administrador do sistema
- [RF22] Deletar administrador do sistema
- [RF23] Ver administrador do sistema
- [RF24] Atualizar administrador do sistema

### Interface e Rotas
- [RF20] Gerenciar Interface
- [RF25] Controlar rotas no sistema

### Datas e Horários
- [RF26] Cadastrar Datas e horário
- [RF27] Atualizar Datas e horário
- [RF28] Deletar Datas e horário

### Notificações
- [RF12] Enviar notificação

### Funcionalidades Específicas
- [RF14] Verificar Datas
- [RF15] Verificar Horários

## Requisitos Não Funcionais

### Requisitos de Produto
- [RNF01] Desenvolvimento em Python com Django
- [RNF02] Banco de dados MySQL
- [RNF03] Framework Flutter
- [RNF04] Arquitetura Model View Template
- [RNF05] Criptografia dos dados dos usuários

### Requisitos Externos
- [RNF06] Hardware básico
- [RNF07] Tempo de desenvolvimento
- [RNF08] Conexão com a internet

## Diagramas

### Diagrama de Casos de Uso
- Admin
- Médico
- Paciente

### Diagrama de Classes
[Diagrama](https://lucid.app/lucidchart/5528dbf2-b1fd-4dbb-8d38-098e869cd45d/edit?invitationId=inv_ecc1903e-b7a7-4193-926f-94680b51ca0f&page=0_0#)

### Automação do projeto no Bizagi (BPMN)
[Projeto Automatizado](https://drive.google.com/file/d/1x8GIPlQS57C0ERud5U-3ZvmxB5aSoHTU/view?usp=sharing)
## Expectativas para a Implementação do Projeto

**Contexto do Projeto:**
O sistema visa simplificar o agendamento de consultas médicas, oferecendo aos usuários a escolha de médicos através de um catálogo. Com informações sobre especialidades e horários, o sistema facilita a seleção e marcação de consultas. Além disso, notificações serão enviadas para lembrar os usuários das consultas agendadas, melhorando a gestão do tempo para ambas as partes.
