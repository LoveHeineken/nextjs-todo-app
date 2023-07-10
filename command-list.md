npx create-next-app@latest . // tyoe yes to all
npm i prisma --save-dev
npx prisma init --datasource-provider sqlite
npx prisma migrate dev --name init
npx prisma init --datasource-provider sqlite
npm run dev