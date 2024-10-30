<div align="center">

<div>
<img src="https://img.shields.io/badge/-Next_JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=61DAFB" alt="next.js" />
<img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="typescript" />
<img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
</div>

<h3 align="center">Um LiveDocs colaborativo</h3>

</div>

## 📋 <a name="table">Índice</a>

1. 🤖 [Introdução](#introdução)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Recursos](#recursos)
4. 🤸 [Início rápido](#início-rápido)


## <a name="introduction">🤖 Introdução</a>

Construído com Next.js para lidar com a interface do usuário, Liveblocks para recursos em tempo real e estilizado com TailwindCSS, LiveDocs é um clone do Google Docs. O objetivo principal é demonstrar as habilidades do desenvolvedor em um ambiente em tempo real que cria um impacto duradouro.

## <a name="tech-stack">⚙️ Tech Stack</a>

- Next.js
- TypeScript
- Liveblocks
- Lexical Editor
- ShadCN
- Tailwind CSS

## <a name="features">🔋 Recursos</a>

👉 **Autenticação**: Autenticação do usuário usando o GitHub por meio do NextAuth, garantindo login/logout seguros e gerenciamento de sessão.

👉 **Editor de texto colaborativo**: Vários usuários podem editar o mesmo documento simultaneamente com atualizações em tempo real.

👉 **Gerenciamento de documentos**
- **Criar documentos**: Os usuários podem criar novos documentos, que são salvos e listados automaticamente.
- **Excluir documentos**: Os usuários podem excluir documentos de sua propriedade.
- **Compartilhar documentos**: Os usuários podem compartilhar documentos por e-mail ou link com permissões de visualização/edição.
- **Listar documentos**: Exibe todos os documentos de propriedade ou compartilhados com o usuário, com funcionalidades de pesquisa e classificação.

👉 **Comentários**: Os usuários podem adicionar comentários em linha e gerais, com encadeamento para discussões.

👉 **Colaboradores ativos no editor de texto**: Mostra os colaboradores ativos com indicadores de presença em tempo real.

👉 **Notificações**: Notifica os usuários sobre compartilhamentos de documentos, novos comentários e atividades dos colaboradores.

👉 **Responsivo**: O aplicativo é responsivo em todos os dispositivos.

e muito mais, incluindo arquitetura de código e reutilização

## <a name="quick-start">🤸 Início rápido</a>

Siga estas etapas para configurar o projeto localmente em sua máquina.

**Pré-requisitos**

Certifique-se de ter o seguinte instalado em sua máquina:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Clonando o Repositório**

```bash
git clone https://github.com/adrianhajdin/collaborative-editor.git
cd collaborative-editor
```

**Instalação**

Instale as dependências do projeto usando npm:

```bash
npm install
```

**Configurar Variáveis ​​de Ambiente**

Crie um novo arquivo chamado `.env` na raiz do seu projeto e adicione o seguinte conteúdo:

```env
#Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

#Liveblocks
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=
LIVEBLOCKS_SECRET_KEY=
```

Substitua os valores do espaço reservado pelas suas credenciais reais do Clerk & LiveBlocks. Você pode obter essas credenciais inscrevendo-se no site [Clerk](https://clerk.com/) e [Liveblocks](liveblocks.io/).

**Executando o Projeto**

```bash
npm run dev
```

Abra [http://localhost:3000](http://localhost:3000) no seu navegador para visualizar o projeto.
Enviar feedback
Painéis laterais
Histórico
Salvas
