## Desafio Técnico: Sistema de Login com Controle de Agendamentos

### Objetivo
Desenvolver um sistema que implemente funcionalidades de autenticação e controle de permissões, permitindo que diferentes tipos de usuários desempenhem ações específicas. O sistema deve incluir tanto o frontend quanto o backend.

---

### Funcionalidades

#### **1. Login de Usuário**
- Criar um sistema de login que autentique usuários com base em suas credenciais.
- Não é necessário implementar a funcionalidade de cadastro; os usuários já devem existir no sistema.

#### **2. Controle de Papéis de Usuário**
- **Admin**:
  - Tem acesso à funcionalidade de criação de agendamentos.
- **Usuário comum**:
  - Apenas visualiza os agendamentos criados pelo admin.
  - Não pode criar, editar ou excluir agendamentos.

#### **3. Funcionalidade de Agendamentos**
- **Admin**:
  - Pode criar agendamentos com informações como título, data e descrição.
  - Os agendamentos criados devem ser exibidos para todos os usuários.
- **Usuário comum**:
  - Visualiza uma lista de agendamentos ordenada pela data mais recente.
  - A lista deve ser clara e acessível, mas o usuário não pode realizar nenhuma ação de modificação.

---

### Expectativas
- A aplicação deve oferecer uma experiência clara e funcional para ambos os tipos de usuários.
- Deve garantir que as permissões sejam respeitadas, de modo que cada papel só tenha acesso às funcionalidades que lhe foram atribuídas.
- O sistema deve ser entregue como um projeto completo, com frontend e backend, funcionando de forma integrada.

Boa sorte! 😊
