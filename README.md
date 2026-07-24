# ☕ API de Cafeteria — Projeto de Aprendizado com Django REST Framework

Bem-vindo ao projeto de desenvolvimento de uma API REST utilizando **Django REST Framework (DRF)**.

Neste projeto você desenvolverá o back-end de uma cafeteria, implementando autenticação, gerenciamento de usuários, cardápio e pedidos.

A proposta é servir como um projeto tutorial: você receberá requisitos claros e algumas orientações ao longo do caminho, mas as decisões de implementação ficam por sua conta.

---

# 🚀 O que você vai aprender

Ao concluir este projeto você terá praticado:

- Desenvolvimento de APIs REST com Django REST Framework;
- Autenticação e autorização de usuários;
- Modelagem de entidades e relacionamentos;
- Organização de um projeto back-end;
- Boas práticas de desenvolvimento.

---

# 🛠 Tecnologias

- Python 3.10+
- Django
- Django REST Framework
- Simple JWT *(recomendado)*

---

# 📦 Antes de começar

Antes de iniciar o projeto:

- [ ] Criar e ativar um ambiente virtual;
- [ ] Instalar as dependências necessárias;
- [ ] Criar um projeto Django;
- [ ] Configurar o Django REST Framework;
- [ ] Executar as migrações iniciais;
- [ ] Criar um superusuário;
- [ ] Iniciar o servidor de desenvolvimento.

> Ao longo do projeto, organize a aplicação da forma que considerar mais adequada. A divisão em apps, serializers, views e demais componentes faz parte das decisões de implementação.

---

# 📖 Módulo 1 — Autenticação e Usuários

Neste módulo você desenvolverá a base da autenticação da aplicação e os recursos relacionados aos usuários.

## Requisitos

- [ ] Um visitante deve ser capaz de criar uma conta na plataforma.
- [ ] Um usuário cadastrado deve ser capaz de realizar login.
- [ ] Um usuário autenticado deve ser capaz de visualizar suas próprias informações.
- [ ] Um usuário autenticado deve ser capaz de atualizar seus dados cadastrais.
- [ ] Um usuário autenticado deve ser capaz de remover sua própria conta.
- [ ] Um administrador deve ser capaz de visualizar todos os usuários da plataforma.
- [ ] Um administrador deve ser capaz de consultar as informações de qualquer usuário.

### ✅ Checkpoint

Ao concluir este módulo, você deve ser capaz de:

- [ ] Criar um usuário.
- [ ] Realizar login.
- [ ] Consumir endpoints protegidos utilizando um token JWT.
- [ ] Diferenciar permissões entre usuários comuns e administradores.

> 💡 **Orientações**
>
> - Proteja os endpoints conforme eles forem sendo implementados.
> - Caso isso dificulte os testes durante o desenvolvimento, desabilite temporariamente a autenticação de uma rota específica ou aumente o tempo de expiração do token JWT.
> - Antes de concluir o módulo, revise as permissões da API e garanta que cada endpoint possua o nível de acesso adequado.

---

# 📖 Módulo 2 — Cardápio

Neste módulo você desenvolverá a API responsável pelo gerenciamento dos produtos da cafeteria.

## Requisitos

- [ ] Um visitante deve ser capaz de visualizar todos os produtos disponíveis.
- [ ] Um visitante deve ser capaz de visualizar os detalhes de um produto.
- [ ] Um administrador deve ser capaz de adicionar novos produtos ao cardápio.
- [ ] Um administrador deve ser capaz de atualizar as informações de um produto.
- [ ] Um administrador deve ser capaz de remover produtos do cardápio.

### ✅ Checkpoint

Ao concluir este módulo, você deve ser capaz de:

- [ ] Cadastrar novos produtos.
- [ ] Consultar produtos individualmente ou em listagem.
- [ ] Aplicar permissões diferentes para visitantes, usuários autenticados e administradores.

> 💡 **Orientações**
>
> - Pense cuidadosamente nas permissões de cada operação antes de concluir o módulo.
> - Nem todos os recursos precisam estar disponíveis para todos os usuários.

---

# 📖 Módulo 3 — Pedidos

Neste módulo você implementará o fluxo principal da aplicação: permitir que clientes realizem pedidos utilizando os produtos cadastrados.

## Requisitos

- [ ] Um usuário autenticado deve ser capaz de fazer um pedido.
- [ ] Um usuário autenticado deve ser capaz de visualizar seus próprios pedidos.
- [ ] Um usuário autenticado deve ser capaz de consultar um pedido específico.
- [ ] Um administrador deve ser capaz de visualizar todos os pedidos realizados.
- [ ] Um administrador deve ser capaz de atualizar o status de um pedido.

### ✅ Checkpoint

Ao concluir este módulo, você deve ser capaz de:

- [ ] Fazer um pedido contendo um ou mais produtos.
- [ ] Consultar pedidos já realizados.
- [ ] Atualizar o status de um pedido.
- [ ] Aplicar regras de autorização para diferentes tipos de usuários.

> 💡 **Orientações**
>
> - Defina regras claras para acesso aos pedidos.
> - Considere cuidadosamente quais usuários podem alterar o status de um pedido e em quais situações.

---

# ⭐ Próximos passos

Depois de concluir os módulos principais, tente expandir a aplicação com novas funcionalidades.

## Desafios sugeridos

- [ ] Sistema de favoritos.
- [ ] Documentação da API.
- [ ] Testes automatizados.
- [ ] Deploy da aplicação.

Esses desafios não são obrigatórios, mas são excelentes oportunidades para aprofundar seus conhecimentos no ecossistema Django.

---

# 📚 Referências

Durante o desenvolvimento, utilize a documentação oficial sempre que necessário.

- Django
- Django REST Framework
- Simple JWT

---

**Bom código e bons cafés! ☕**