
  GNU nano 8.3                    main.js
const mineflayer = require('mineflayer');
const express = require('express');
const app = express();
const port = process.env.PORT || 8080;

const GLOBAL_CONFIG = {
  host: '185.207.166.12',
  port: 25565,
  version: '1.20.1',
  password: 'woylah12',
  targetPlayer: 'pellk0re'
};

const ACCOUNTS = ['netherite_ores', 'dogyy', 'athenaaucuu', 'penguras_>
const bots = {};
let webLogs = [];

function addWebLog(name, msg) {
  const cleanMsg = msg.replace(/§[0-9a-fk-or]/g, '');
  const entry = `<span style="color: #888">[${new Date().toLocaleTimeS>
  webLogs.unshift(entry);
  if (webLogs.length > 80) webLogs.pop();
}

class BotInstance {
  constructor(username, index) {
    this.username = username;
    this.status = 'Initializing';
    this.isInGame = false;

    setTimeout(() => this.connect(), index * 10000);
  }

  connect() {
    this.cleanup();
    this.status = 'Connecting...';
    this.bot = mineflayer.createBot({
      host: GLOBAL_CONFIG.host,
      port: GLOBAL_CONFIG.port,
      username: this.username,
      version: GLOBAL_CONFIG.version,

^G Help       ^O Write Out  ^F Where Is   ^K Cut        ^T Execute
^X Exit       ^R Read File  ^\ Replace    ^U Paste      ^J Justify
