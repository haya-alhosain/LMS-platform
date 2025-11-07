
## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

## Dependencies

```bash
npm install @clerk/nextjs
npm install react-hot-toast
npm install uploadthing @uploadthing/react react-dropzone
npm install react-quill ==> Editor de blogs
npm install @mux/mux-node && npm install @mux/mux-player-react ==> Preview de Videos
npm install zustand ==> Manejo de Estado global
npm install react-confetti
npm install query-string
npm install react-icons
npm install stripe
npm install recharts ==> Graficos
```

## Backend Initial

```bash
npm i -D prisma
npx prisma init
npx prisma generate
npx prisma db push
npx prisma studio
npx prisma migrate reset ==> Elimina toda la BD
```

### Execution Seed

```bash
node scripts/seed.ts
```

### Resources

https://uploadthing.com/ => Bucket de almacenamiento
https://clerk.com/docs => Autenticacion
https://ui.shadcn.com/ => UI
https://planetscale.com/ => MYSQL
https://dashboard.mux.com/organizations/4jdo85/environments/8vkcln/video/assets => Preview De videos

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!
