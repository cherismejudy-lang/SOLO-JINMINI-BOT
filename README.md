# SOLO-JIN-MINI-BOT
MINI BOT 
const TelegramBot = require('node-telegram-bot-api');

const token = '8662481300:AAFfSr7NgvTtQ8wpKMylZv-oKchoNdCO52M';

const bot = new TelegramBot(token, { polling: true });

bot.on('message', (msg) => {
  bot.sendMessage(msg.chat.id, "Salut 👋");
});
