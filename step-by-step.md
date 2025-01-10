# create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/main/packages/create-svelte).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm create svelte@latest

# create a new project in my-app
npm create svelte@latest my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.


## Create

```bash
npm create svelte@latest shadcn-svelte -y

cd shadcn-svelte

npx svelte-add@latest tailwindcss -y

npm i

npx shadcn-svelte@latest init

npx shadcn-svelte@latest add badge -y
npx shadcn-svelte@latest add breadcrumb -y
npx shadcn-svelte@latest add button -y
npx shadcn-svelte@latest add card -y
npx shadcn-svelte@latest add dropdown-menu -y
npx shadcn-svelte@latest add input -y
npx shadcn-svelte@latest add input -y
npx shadcn-svelte@latest add label -y
npx shadcn-svelte@latest add select -y
npx shadcn-svelte@latest add pagination -y
npx shadcn-svelte@latest add progress -y
npx shadcn-svelte@latest add scroll-area -y
npx shadcn-svelte@latest add separator -y
npx shadcn-svelte@latest add sheet -y
npx shadcn-svelte@latest add tabs -y
npx shadcn-svelte@latest add table -y
npx shadcn-svelte@latest add tooltip -y
```

```
mkdir src/routes/dashboard
```

```
cat << EOF > src/routes/dashboard/+layout.svelte
<script>
  import '../../app.css'; // TailwindCSS
</script>

<slot />
EOF
```

```
cat << EOF > src/routes/dashboard/+page.svelte
content
EOF
```