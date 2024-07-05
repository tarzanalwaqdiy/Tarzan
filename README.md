
import requests
import hashlib, random
import telebot
from telebot import types
token = "5424002919:AAEgQDywN1C_3Ab0W8NYZqymVi5UEO13fNs"
bot = telebot.TeleBot(token)

@bot.message_handler(commands=[ start ])
def start(message):
  b = types.InlineKeyboardMarkup()
  b.add(brok)
  bot.reply_to(message, اهـــلآ بك في بـــوت طــرزان لارسال مــكالمات مزيفه الا اي رقم في العالم  قم بضغط علا /tarzan•👾\n+ ,reply_markup=b)



@bot.message_handler(commands=[ Hild ])
def tarzan(message):
  b = types.InlineKeyboardMarkup()
  b.add(brok)
  bot.reply_to(message, هلاً بك انا هنا لمساعدتك في اي شيئ تحتاجه فقط اطلب ما تحتاجه وسابذل قصاري جهدي لتقديم المساعده سواء كنت تبحث عن معلومات او اجابه اي اسئله او ترغب في الحصول علا توجيه في موضوع معين فانا هنا لخدمتك لا تتردد في طرح اي سؤال او طلب ما تحتاجه ساكون سعيد بتقديم المساعده بافضل ما لدي                                                                            طـــرزان                                                    رقمي وتساب                                                     https://wa.me/966571961318         \n+ ,reply_markup=b)





brok=types.InlineKeyboardButton(text=  معرفي تلي جرام  ,url="t.me/amr222tarzan")
