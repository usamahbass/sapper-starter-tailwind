# sapper starter tailwindcss

1. clone repo

```bash
    git clone https://github.com/usamahbass/sapper-starter-tailwind
```

2. install dependencies

```bash
    yarn install or npm install
```

3. build tailwind with Tailwind CLI or npx

```bash
    npx tailwindcss build styles.css -o output.css
```

4. add link css in src/template.html like this

```bash
    <link rel="stylesheet" href="output.css">
```

5. watch tailwind and start your sapper project , run these commands in a seperate window

```bash
    yarn watch:tailwind or npm run watch:tailwind
```

```bash
    yarn dev or npm run dev
```
