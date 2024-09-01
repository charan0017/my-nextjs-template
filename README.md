<h1 align="center">
My next.js template
</h1>

# What's included
 - TypeScript-ESLint-Prettier setup
 - TailwindCSS with cva, clsx
 - Ant Design components and icons
 - Framer Motion for animations
 - Misc utilities like qs, lodash, dayjs, uuid, copy-to-clipboard, swr, use-debounce
 - Dockerfile for development and production

## How to clone this template
```bash
npx create-next-app --example https://github.com/charan0017/my-nextjs-template <your-app-name>
cd <your-app-name>
```

## How to run the app
```bash
npm run dev-fast
```
`Note: dev-fast uses --turbo flag to skip type-checking and linting. Use it only if you are sure about your code. Otherwise, use npm run dev`

## How to build and start the app (for production)
```bash
npm run build
npm run start
```

## How to run the app in Docker
```bash
docker build -t my-nextjs-app .
docker run -p 3000:3000 my-nextjs-app
```

## How to deploy the app to Vercel
```bash
vercel
```
