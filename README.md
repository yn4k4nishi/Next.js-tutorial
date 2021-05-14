## Next.js tutorial
deploy : https://nextjs-blog-tau-tawny.vercel.app/

tutorial : https://nextjs.org/learn/basics/create-nextjs-app

## Progress ![](https://progress-bar.dev/7/?scale=7&suffix=/7)
- [x] Create a next.js App
- [x] Navigate Between Pages
- [x] Assets, Metadata, and CSS
- [x] Pre-rendering and Data Fetching
- [x] Dynamic Routes
- [x] API Routes
- [x] Deploying your Next.js App

## Setup env
```bash
sudo apt update
sudo apt upgrade
curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
sudo apt install nodejs
```

## Create a app
```bash
npx create-next-app nextjs-blog --use-npm --example "https://github.com/vercel/next-learn-starter/tree/master/learn-starter"
```

## Run server
```bash
cd nextjs-blog
npm run dev
```

http://localhost:3000 を開く