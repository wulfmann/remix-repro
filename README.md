This repo is an unmodified build using the basic remix run app. Here are the options I selected:

```
% npx create-remix@latest repro
? What type of app do you want to create? Just the basics
? Where do you want to deploy? Choose Remix App Server if you're unsure; it's easy to change deployment targets. Vercel
? TypeScript or JavaScript? TypeScript
? Do you want me to run `npm install`? Yes
```

```
node -v
v19.1.0
```

Running `npm run dev` shows this in the console:

![console screenshot](https://github.com/wulfmann/remix-repro/blob/master/remix-repro-console-screenshot.png)

I've attached a download of the console in [localhost-1675992116202.log](https://github.com/wulfmann/remix-repro/blob/master/localhost-1675992116202.log).

# Welcome to Remix!

- [Remix Docs](https://remix.run/docs)

## Deployment

After having run the `create-remix` command and selected "Vercel" as a deployment target, you only need to [import your Git repository](https://vercel.com/new) into Vercel, and it will be deployed.

If you'd like to avoid using a Git repository, you can also deploy the directory by running [Vercel CLI](https://vercel.com/cli):

```sh
npm i -g vercel
vercel
```

It is generally recommended to use a Git repository, because future commits will then automatically be deployed by Vercel, through its [Git Integration](https://vercel.com/docs/concepts/git).

## Development

To run your Remix app locally, make sure your project's local dependencies are installed:

```sh
npm install
```

Afterwards, start the Remix development server like so:

```sh
npm run dev
```

Open up [http://localhost:3000](http://localhost:3000) and you should be ready to go!

If you're used to using the `vercel dev` command provided by [Vercel CLI](https://vercel.com/cli) instead, you can also use that, but it's not needed.
