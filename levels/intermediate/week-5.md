# 🌟 هفته ۵ – سطح متوسط

## 🎯 اهداف یادگیری

- آشنایی با مفهوم ذخیره‌سازی داده در مرورگر
- یادگیری کار با `localStorage` و `sessionStorage`
- استفاده از داده‌ها برای ایجاد تجربه پایدار (persistent experience)
- آشنایی اولیه با JSON و تبدیل داده‌ها برای ذخیره‌سازی

---

## 📚 مباحث قابل یادگیری

- تفاوت بین `localStorage` و `sessionStorage`
- متدهای مهم:
  - `setItem(key, value)`
  - `getItem(key)`
  - `removeItem(key)`
  - `clear()`
- محدودیت‌های حافظه و فقط ذخیره رشته‌ها
- آشنایی با JSON:
  - `JSON.stringify()` برای تبدیل object به string
  - `JSON.parse()` برای تبدیل string به object

> ⏱ زمان تقریبی یادگیری: **۲ تا ۳ ساعت**

---

## 🔗 منابع پیشنهادی

- [Web Storage API – MDN](https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API)
  javascript-localstorage-vs-sessionstorage/)
- [JSON in JavaScript – W3Schools](https://www.w3schools.com/js/js_json.asp)
- [آموزش کامل localStorage – سبزلرن](https://sabzlearn.ir)

---

## 🛠 تمرین عملی

### ✨ پروژه: سیستم مدیریت یادداشت (ادامه هفته قبل) با قابلیت ذخیره‌سازی

**ویژگی‌های اصلی:**

1. تسک‌هایی که کاربر اضافه می‌کند در `localStorage` ذخیره شوند.
2. هنگام رفرش صفحه، لیست تسک‌ها باقی بماند.
3. حذف تسک از لیست باید آن را از `localStorage` نیز حذف کند.
4. نمایش پیغام در صورتی که لیست خالی باشد.

> ⏱ زمان تقریبی انجام پروژه: **۲ ساعت**

---

### ✅ راهنمایی‌ها

- از `JSON.stringify()` برای ذخیره یک array از تسک‌ها استفاده کنید.
- هنگام بارگذاری صفحه (`DOMContentLoaded`)، لیست ذخیره‌شده را بخوانید و در DOM نمایش دهید.
- هنگام افزودن یا حذف، `localStorage` را به‌روزرسانی کنید.

---

## ❓تفکر و پرسش

1. چه زمانی بهتر است از `localStorage` به جای `sessionStorage` استفاده کنیم؟
2. آیا می‌توان object یا array را مستقیماً در `localStorage` ذخیره کرد؟
3. چه خطراتی ممکن است در استفاده نادرست از `localStorage` به‌وجود آید؟
4. آیا داده‌های `localStorage` در همه مرورگرها یکسان عمل می‌کنند؟
5. اگر پروژه ما نیاز به ذخیره اطلاعات حساس دارد، آیا `localStorage` گزینه مناسبی است؟

---

## 📝 نکات

- تا پایان هفته، پروژه خود و پاسخ پرسش‌ها را بارگذاری نمایید.
