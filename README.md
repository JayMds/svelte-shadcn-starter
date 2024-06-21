# RAW Svelkit 4 app Shadcn Ui 

## Setup 
https://www.shadcn-svelte.com/docs/installation/sveltekit

Les composants shadcn présents dans src/lib/components/ui sont compatibles avec une app setup tailwind avec la configuration
adéquate

Créer un app sveltkit :
```shell
npm create svelte@latest my-app 
```

Ajouter Tailwind CSS :
```shell
npx @svelte-add/tailwindcss@latest 
```

Installation
```shell
npm install
```

Dans svelte.config.js :
```js
const config = {
  // ... other config
  kit: {
    // ... other config
    alias: {
      "@/*": "./path/to/lib/*",
    },
  },
};
```

Init la config des composants shadcn :
```shell
npx shadcn-svelte@latest init
```


Copier tous les composants disponibles : 
```shell
npx shadcn-svelte@latest add button
```
