SETUP
1. Install Node.js 18+.
2. Run npm install, then copy .env.example to .env and fill every value.
3. Run npm start. Website: http://localhost:3000 ; admin: /admin.
4. Deploy with HTTPS and set the same environment variables in your host.

PAYMENT WARNING: The TinyPesa endpoint and request fields in server.js are an integration adapter using the endpoint pattern discussed. Verify exact endpoint, auth header, required fields, callback format/signature and payment status verification against the API documentation in your TinyPesa account before live use. Do not accept a callback as genuine unless authenticated/verified with the provider. The supplied match information and prices are not independently verified. Confirm organiser authorisation, inventory, terms and refunds before accepting money. This starter does not allocate physical seats, send emails/SMS, render downloadable QR ticket PDFs or implement gate scanning.
