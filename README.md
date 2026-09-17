# TikTok / Instagram Telegram Downloader

بوت تيليجرام يستقبل رابط فيديو من تيك توك أو انستغرام ويرسله للمستخدم كفيديو.

## التشغيل محلياً
1. ثبّت Python 3.11+
2. ثبّت المكتبات:
   `pip install -r requirements.txt`
3. اضبط متغير البيئة `BOT_TOKEN` (تحصل عليه من @BotFather):
   - Windows (PowerShell): `$env:BOT_TOKEN="ضع_التوكن_هنا"`
   - macOS/Linux: `export BOT_TOKEN="ضع_التوكن_هنا"`
4. شغّل البوت:
   `python bot.py`

## النشر على Render
- أنشئ خدمة من نوع **Background Worker**.
- Build command: `pip install -r requirements.txt`
- Start command: `python bot.py`
- أضف متغير بيئة:
  - Key: `BOT_TOKEN`
  - Value: توكن البوت من BotFather
