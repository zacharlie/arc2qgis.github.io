To run locally you need to initialize the theme submodules recursively:

```bash
git submodule update --init --recursive
```

Ensure latest LTS of Node is running first... Then (you might need sudo):

```bash
npm ci
```

If you want to run Hugo with the Docsy theme from scratch, you'll need the deps outlined at https://www.docsy.dev/docs/getting-started/

```bash
npm install hugo-extended --save-dev
npm install autoprefixer --save-dev
npm install postcss-cli --save-dev
```

Simple to automate the dev server once that's done

`serve.cmd`

```batch
for /f "delims=" %%F in ('npm bin') do call "%%F\hugo" server
```

`serve.sh`

```bash
(npm bin)/hugo server
```
