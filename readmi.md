/**
 * Welcome to Cloudflare Workers! This is your first worker.
 *
 * - Run `npm run dev` in your terminal to start a development server
 * - Open a browser tab at http://localhost:8787/ to see your worker in action
 * - Run `npm run deploy` to publish your worker
 *
 * Learn more at https://developers.cloudflare.com/workers/
 */Deploy online
 */ npx wrangler d1 execute prod-d1-tutorial --file=./schema.sql
 */ npx wrangler d1 execute prod-d1-tutorial --command="SELECT * FROM Customers"
 */ npx wrangler deploy

Telegram webhoock
https://xabaras.medium.com/setting-your-telegram-bot-webhook-the-easy-way-c7577b2d6f72

Check webhoock:
https://api.telegram.org/bot{my_bot_token}/getWebhookInfo

Set webhoock:
https://api.telegram.org/bot{my_bot_token}/setWebhook?url={url_to_send_updates_to}
