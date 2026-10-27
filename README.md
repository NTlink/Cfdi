# NTLink CFDI skill

Skill para usar el CLI `nt` con tareas de CFDI: revisar documentos, analizar PDF/XML/JSON, preparar y gestionar borradores, y timbrar solo con autorización explícita.

## Instalar en Codex

```bash
npx skills add NTlink/ntlink-cfdi-skill --skill cfdi --global --agent codex
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
