# reddit-next13-prisma-sql
 Reddit clone - social network with a forum-style discussion structure

initial initialisation using 
npx create-next-app
npx prisma init
npx shadcn-ui add button with an added isLoading state
on-click-outside hook from use hooks website
added basic styling : editor.css(for posts) and global.css
db.ts file setup s.t. when we run it on local setup we aren't instantiating multiple prisma clients ,intstead we use a cached one
utils.ts for indicating when a post has happened
tailwindconfig setup and installing dependancies
