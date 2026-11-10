# haoqi.design reconstruction

Editable reconstruction of the deployed portfolio at `https://haoqi.design/`.

## Run locally

```bash
npm install
npm run dev
```

The development server uses `http://127.0.0.1:4173`. Build the static application with `npm run build`; preview it on port `4174` with `npm run preview`.

Recovered production evidence, screenshots, source slices and implementation decisions live in [`reconstruction/`](./reconstruction/README.md); the final verification record is [`reconstruction/analysis/08-completion-audit.md`](./reconstruction/analysis/08-completion-audit.md). The application itself is a Vite + React + TypeScript project with Three.js/R3F for the persistent visual layer.

## Routes

- `/`
- `/reunimos`
- `/inspire_mono`
- `/wasm_design_utils`
- `/adrive`
- `/shore_icon`
- `/teambition`
- unmatched paths render the recovered production 404 shell
