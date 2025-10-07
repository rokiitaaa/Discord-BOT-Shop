# rokitaaa Store Bot (CommonJS)

**Características**
- Panel de Tickets (Soporte / Pagos / Custom)
- Cierre con transcript HTML (./transcripts)
- Logs por Webhook (aperturas/cierres/transcripts)
- Slash commands: /ticketpanel /close /faq /tienda /contacto /ping
- Prefijo: !help !tienda !contacto
- Embeds con branding

**Instalación**
1) `npm i`
2) `cp .env.example .env` y rellena variables
3) `npm run deploy:cmd` (registra slash commands)
4) `npm start`

**Notas**
- Crea un webhook en tu canal de logs y pon su URL en `LOG_WEBHOOK_URL`.
- Define `TICKETS_CATEGORY_ID` para que los tickets vayan a esa categoría.
