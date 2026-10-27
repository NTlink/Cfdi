# Cfdi — NTLink agent skill

Si buscas interactuar con el timbrado mexicano de CFDI desde una terminal o un agente como Hermes, esta skill guía el uso del CLI `nt` para revisar documentos, preparar facturas y timbrar con aprobación explícita.

La skill se llama `cfdi` en el instalador (los identificadores técnicos usan minúsculas) y se muestra como **Cfdi** en Codex.

## Instalar en Codex

```bash
npx skills add NTlink/Cfdi --skill cfdi --global --agent codex
```

Para instalarla en otros agentes compatibles, omite `--agent codex` y elige los agentes durante la instalación.

## Actualizar

```bash
npx skills update cfdi --global
```

La skill requiere el CLI `nt`, que se instala por separado:

```bash
npm install --global @ntlinkmx/nt
```

Antes de cada timbrado, la skill exige mostrar la factura completa al usuario y esperar aprobación explícita de esa versión exacta.
