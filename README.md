# Doutor Agenda - Sistema de Gestão para Clínicas

Um sistema SaaS moderno para gestão de clínicas médicas, desenvolvido durante o bootcamp da Full Stack Club. Este projeto implementa as melhores práticas de desenvolvimento fullstack, utilizando tecnologias atuais e um design system robusto.

## 🚀 Tecnologias

- **Frontend:**

  - Next.js 15
  - React 19
  - TypeScript
  - Tailwind CSS
  - Shadcn/ui (Componentes)

- **Backend:**

  - Next.js API Routes
  - Drizzle ORM
  - PostgreSQL

- **Ferramentas de Desenvolvimento:**
  - ESLint
  - Prettier
  - TypeScript
  - Drizzle Kit

## ✨ Funcionalidades

- [Em desenvolvimento] Sistema de autenticação
- [Em desenvolvimento] Dashboard administrativo
- [Em desenvolvimento] Gestão de pacientes
- [Em desenvolvimento] Agendamento de consultas
- [Em desenvolvimento] Gestão de profissionais
- [Em desenvolvimento] Relatórios e análises

## 🛠️ Instalação

1. Clone o repositório:

```bash
git clone https://github.com/ruan-webdev/clinic-saas.git
cd clinic-saas
```

2. Instale as dependências:

```bash
npm install
```

3. Configure as variáveis de ambiente:

```bash
# Crie um arquivo .env.local na raiz do projeto
# Adicione as seguintes variáveis:
DATABASE_URL="sua_url_do_postgres"
```

4. Execute as migrações do banco de dados:

```bash
npm run db:migrate
```

5. Inicie o servidor de desenvolvimento:

```bash
npm run dev
```

O projeto estará disponível em `http://localhost:3000`

## 📁 Estrutura do Projeto

```
src/
├── app/          # Rotas e páginas da aplicação
├── components/   # Componentes reutilizáveis
├── db/          # Configuração e schemas do banco de dados
└── lib/         # Utilitários e configurações
```

## 🤝 Contribuindo

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👨‍💻 Autor

Ruan WebDev - [GitHub](https://github.com/ruan-webdev)

---

Desenvolvido com 💜 durante o bootcamp da Full Stack Club
