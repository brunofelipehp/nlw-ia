<div align="center">
  <h1>
     NLW AI
  </h1>
  
  > 13ª edição do Next Level Week onde o foco é o uso da Inteligência Artificial.
  
  <p align="center">
    <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#-contatos">Contatos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
     <a href="#-instalacao">Instação</a>
  </p>
  
  <br />
  
  <img src="./assets/project.png" />
</div>

## 🌟 **Projeto**

Esta é a 13ª edição do Next Level Week, uma semana intensiva de aprendizado com foco em codificação, desafios e networking. O objetivo é impulsionar sua carreira para o próximo nível, independentemente de onde você esteja atualmente.

Nesta trilha de Mastery, voltada para desenvolvedores que desejam dominar novas tecnologias, você terá a oportunidade de criar um projeto completo e se destacar na construção do futuro da sua carreira com Inteligência Artificial.

Desenvolvemos a interface da nossa aplicação Upload.ai, uma plataforma para o envio de vídeos, transcrição e geração de títulos e descrições para o YouTube.

## ✨ Tecnologias

A lista de tecnologias abaixo mostra um pouco do que foi abordado nesta semana de muito conteúdo da Trilha Mastery.

- [React](https://pt-br.legacy.reactjs.org/)
- [Node](https://nodejs.org/en/about)
- [TypeScript](https://www.typescriptlang.org/)
- [Fastify](https://fastify.dev/)
- [Prisma](https://www.prisma.io/)
- [Open AI](https://platform.openai.com/docs/introduction)
- [Zod](https://zod.dev/)
- [ffmpeg wasm](https://ffmpegwasm.netlify.app/)
- [Shadcn](https://ui.shadcn.com/)
- [Tailwind](https://tailwindcss.com/)
- [Radix UI Primitives](https://www.radix-ui.com/primitives)

## 📦<span id="instacao"> Instalação </span>

> <p>Para clonar e executar está aplicação, você precisará do Git, NodeJS v18.17.1 ou superior + npm v9.17.1 ou superior e o PNPm 8.7.5 instalado no seu computador.</p>
> <p> Nesse Projeto utilizamos pnpm.</p> 
> <p>Este repositório é dividido em dois diretórios.</P>
> <p>Veja como instalar as duas partes do projeto logo abaixo: </p>

- web é aonde esta o nosso Front-End.
- api é o diretório aonde esta o nosso Back-End.

<p>Para clonar o projeto:</p>

```bash
git clone
```

<h2 align="center">Front-End</h2>

```bash
$ cd web
```

```bash
#pnpm
$ pnpm install

#npm
$ npm install
```

 <p>Execute o projeto:</p>

```bash
# pnpm
pnpm run dev

# npm
npm run dev
```

 <h2 align="center">Back-End</h2>

```bash
$ cd api
```

```bash
#pnpm
$ pnpm install

#npm
$ npm install
```

<p>Crie o arquivo .env com as variáveis de ambiente necessárias:</p>
<span></span>


```bash
DATABASE_URL="file:./dev.db"
OPENAI_KEY="sua OpenAI key"

NOTE: Para obter a OpenAI KEY:
1 - Acesse a página OpenAI crie um usuário.
2 - Em seu usuário procure por API KEY aonde você poderá criar a OPENAI_KEY.

```

 <p>Rode o comando a seguir para gerar o client do Prisma:</p>

```bash
# pnpm
pnpm prisma generate

# npm
npm prisma generate
```

 <p>Execute as migrations do banco de dados:</p>

```bash
# pnpm
pnpm prisma migrate dev

# npm
npm prisma migrate dev
```

<p>Execute o projeto:</p>

```bash
# pnpm
pnpm run dev

# npm
npm run dev
```

<p align="center">Aplicação construída com muito 💜 por Burno Felipe</p>
