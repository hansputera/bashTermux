const discord = require('discord.js')
const config = require('./mantap.json')
const hans = new discord.Client({disableEveryone: true})

hans.on('ready', async () => {
 console.log('Bot is Ready')
 hans.user.setActivity('with my friend',{type:"PLAYING"})
})

hans.login(config.token)
