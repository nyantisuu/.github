# Nyantisuu!
<img src="https://raw.githubusercontent.com/Nyantise/Nyantise/main/assets/nyantisuuBanner.png"/>


Nyantisuu! is a TS Framework focusing on Discord, Telegram and "WhatsApp(not native)" bot creation with API (to control your bot using HTTP requests).
We will distribute free client APP for consuming your bot API (made with Flutter - development stage).

[Nyuu (CLI to create your first nyantisuu bot project).](https://github.com/nyantisuu/nyuu)<br/>
[Client (To consume your Bot API).]()<br/>
[Documentation and Tutorials](https://nyantisuu.netlify.app).

## About
The mostly utilized technologies are: Express, Typescript, PrismaORM, Gluegun, Flutter.
- Everything is Class based, architected, organized and clean coded.
- Rich documentation and simple to understand.
- Multipurpose CLI to assist you.

## Checklist
- [x] Helper builder.
- [ ] Commands and subcommands builder.
- [ ] API routes builder.
- [ ] Actions builder.
- [x] Servers and Channels selector (Discord).
- [ ] Users and Roles selector.
- [ ] Watchers builder.
- [ ] Command and helper builder auto integration and populate.

### Definition list
- **Builder** - Constructor Class, they can wrap other libs or no, they will bring a easier syntax and normally will build/rebuild something for you, from buttons, button rows, embedded messages on discord or even create a command for you.
- **Selector** - Selector Class, they will wrap complex functions and resume it for you with a comprehensive name, their function can be resumed as: "they select things for you", from servers your bot are currently on to users it have access and their respective roles etc.
- **Watcher** - Class used to set an event watcher, with Event-Driven logic, an example use case would be: i want you to watch every time {THIS SPECIFIC USER}(watch) {SAYS: letsgo!}(condition). {THEN MAKE THIS ACTION}(action).
- **Actions** - Now i think you can guess more or less, but actions have a huge range: send a message, answer somebody, kick this guy, give a role, etc. And yeah, its a group of Class too
<img src="https://raw.githubusercontent.com/Nyantise/Nyantise/main/assets/nyantisuuExample.png"/>


<!-- ### A ideia nasceu do Minecraft!
Tudo começou com um servidor que eu criei, com o passar dos dias fui criando shellscripts e automações como:<br>
- Backup na nuvem.<br>
- Abrir portas.<br>
- Criação de um CLI para iniciar o servidor etc.<br>

Acabou surgindo a ideia de automatizar o status num servidor de discord com meus amigos (mostrando se estava online, qual foi o ultimo momento de funcionamento e o ultimo backup) e a solução para isso foi a criação do Nyantisuu! -->



And that's it! actually its a small project of mine but i hope i can nurture it. Have a nice day! 