# EVENT Coffee — Telegram Brand Assets & Emojis Registry

مرجع رسمی هویت بصری، کاستوم ایموجی‌ها (Custom Emojis) و استیکرهای برند **EVENT Coffee** برای استفاده در ربات‌های تلگرام (پایتون، aiogram، grammY و Cloudflare Workers).

## 📊 جدول کاستوم ایموجی‌ها و شناسه‌ها

| ردیف | عنوان / کاربرد | دسته‌بندی | پک منبع (Set Name) | ایموجی پایه | Custom Emoji ID | نمونه کد HTML |
|:---:|:---|:---|:---|:---:|:---:|:---|
| ۱ | دانه قهوه | محصولات / کاتالوگ | `t_me_Grigoryann_by_fStikBot` | 🧋 | `5467694131759305672` | `<tg-emoji emoji-id="5467694131759305672">🧋</tg-emoji>` |
| ۲ | دانه قهوه بزرگ‌تر | محصولات / دسته‌بندی | `Lkhgfdert` | ☕ | `5425042430745397139` | `<tg-emoji emoji-id="5425042430745397139">☕</tg-emoji>` |
| ۳ | دانه قهوه در حال ریختن | انیمیشن / لودینگ / فاکتور | `JellySweets` | ☕️ | `5296261422672525277` | `<tg-emoji emoji-id="5296261422672525277">☕️</tg-emoji>` |
| ۴ | دانه قهوه یک‌دسته | بسته‌بندی / برندینگ | `mixvintage` | ✨ | `5048825264373498992` | `<tg-emoji emoji-id="5048825264373498992">✨</tg-emoji>` |
| ۵ | تیک آبی چرخشی | وضعیت سفارش / پردازش | `Statusvideobytaraxd` | 💙 | `6104631352190043951` | `<tg-emoji emoji-id="6104631352190043951">💙</tg-emoji>` |
| ۶ | تیک سبز متحرک | تأیید پرداخت / موفقیت | `Borzyy_by_fStikBot` | 💳 | `5931311490307986699` | `<tg-emoji emoji-id="5931311490307986699">💳</tg-emoji>` |
| ۷ | تخفیف ۲۰ درصد | پروموشن / کد تخفیف | `Happy_new2025` | 🤑 | `5373064599090255697` | `<tg-emoji emoji-id="5373064599090255697">🤑</tg-emoji>` |
| ۸ | استیکر خرید | سبد خرید / تسویه‌حساب | `iranNewz` | 💸 | `5839260144902344766` | `<tg-emoji emoji-id="5839260144902344766">💸</tg-emoji>` |
| ۹ | متن تخفیف ویژه | بنر / کمپین‌های فروش | `iranNewz` | 📉 | `5839200234403533703` | `<tg-emoji emoji-id="5839200234403533703">📉</tg-emoji>` |
| ۱۰ | لوگو اینستاگرام گرد | شبکه‌های اجتماعی / لینک‌ها | `LogoandDesign` | 🟣 | `5375401795738682827` | `<tg-emoji emoji-id="5375401795738682827">🟣</tg-emoji>` |
| ۱۱ | اینستاگرام با اشاره‌گر به راست (متحرک) | شبکه‌های اجتماعی / دکمه لینک | `Mega_Logo` | 🌐 | `5384234065270433395` | `<tg-emoji emoji-id="5384234065270433395">🌐</tg-emoji>` |
| ۱۲ | سطل آشغال (حذف - متحرک) | عملیات / سبد خرید و ادمین | `NewsEmoji` | 🗑 | `5445267414562389170` | `<tg-emoji emoji-id="5445267414562389170">🗑</tg-emoji>` |
| ۱۳ | جستجو / سرچ کاتالوگ (متحرک) | ناوبری / جستجو و فیلتر | `KorysnostiDevicesIcons` | 📄 | `5431420628978641216` | `<tg-emoji emoji-id="5431420628978641216">📄</tg-emoji>` |
| ۱۴ | پشتیبانی با متن فارسی (متحرک) | پشتیبانی / ارتباط با ادمین | `propiycom` | 💵 | `5958416857114350105` | `<tg-emoji emoji-id="5958416857114350105">💵</tg-emoji>` |

## 💻 نمونه استفاده در کدها

### دکمه‌های شیشه‌ای و کیبورد ثابت با `icon_custom_emoji_id`:
```python
InlineKeyboardButton(
    text="کاتالوگ محصولات",
    icon_custom_emoji_id="5425042430745397139",
    callback_data="catalog"
)
```

### در فریم‌ورک TypeScript (grammY / Cloudflare Workers):
```typescript
import { InlineKeyboard } from "grammy";

const keyboard = new InlineKeyboard().text({
  text: "سبد خرید",
  icon_custom_emoji_id: "5839260144902344766"
}, "cart");
```
