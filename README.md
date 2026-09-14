# @all_bypass_file_bot - Railway Setup

এই bot ব্যবহার করতে হলে user-কে আগে নিচের দুইটি channel join করতে হবে:

- @KingNetworkBD
- @minarulsensi

দুইটি channel-এ bot-কে Administrator করুন।

## GitHub upload

এই ৬টি file একই GitHub repository root-এ upload করুন:

- hosting_bot.py
- requirements.txt
- Procfile
- railway.json
- nixpacks.toml
- README.md

## Railway

1. railway.app খুলুন এবং GitHub দিয়ে sign in করুন।
2. New Project → Deploy from GitHub repo চাপুন।
3. এই repository নির্বাচন করুন।
4. Service → Variables → New Variable-এ যোগ করুন:

   TELEGRAM_BOT_TOKEN = BotFather থেকে পাওয়া নতুন token

5. Deploy/Redeploy চাপুন এবং Logs দেখুন।

পুরনো প্রকাশিত token ব্যবহার করবেন না।
