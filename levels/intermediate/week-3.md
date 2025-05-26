# 🌟 هفته ۳ – سطح متوسط

## 🎯 اهداف یادگیری

- درک بهتر مفاهیم **scope**، **closure** و **context**
- یادگیری مدیریت خطاها با استفاده از `try...catch`
- آشنایی با مفهوم توابع بازگشتی و کاربرد آن‌ها
- تقویت توانایی در نوشتن توابع سازمان‌یافته و مستقل
- درک تفاوت بین **توابع معمولی** و **arrow functions** در زمینه `this`

---

## 📚 مباحث قابل یادگیری

- Scope و انواع آن (Global، Function، Block)
- Hoisting دوباره مرور شود، این‌بار در زمینه توابع
- Closure و مثال‌های واقعی از کاربرد آن
- Context (`this`) در توابع مختلف
- مدیریت خطا با استفاده از `try...catch` و `throw`
- توابع بازگشتی (Recursive Functions)

> ⏱ زمان تقریبی یادگیری: **۲ تا ۳ ساعت**

---

## 🔗 منابع پیشنهادی

- [JavaScript Scope – MDN](https://developer.mozilla.org/en-US/docs/Glossary/Scope)
- [JavaScript Closures – MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures)
- [JavaScript Error Handling – W3Schools](https://www.w3schools.com/js/js_errors.asp)
- [JavaScript Recursion – JavaScript.info](https://javascript.info/recursion)

---

## 🛠 تمرین عملی

### ✨ پروژه: ساخت یک ماشین‌حساب بازگشتی و محافظت‌شده

**ویژگی‌های اصلی:**

1. تابعی برای محاسبه فاکتوریل به صورت بازگشتی
   ```js
   factorial(5); // 120
   ```
2. تابعی برای محاسبه مجموع اعداد درون آرایه (به صورت بازگشتی)

   ```js
   sumArray([1, 2, 3, 4]); // 10
   ```

3. تابعی برای گرفتن ورودی و اجرای عملیات با try...catch

   ```js
   safeDivide(10, 2); // 5
   safeDivide(10, 0); // "Cannot divide by zero!"
   ```

4. تابعی با استفاده از Closure برای ایجاد شمارنده خصوصی

   ```js
   const counter = createCounter();
   counter(); // 1
   counter(); // 2
   ```

> ⏱ زمان تقریبی انجام پروژه: **۱ ساعت**

---

### ❓تفکر و پرسش

1. چرا استفاده از closure در برخی مواقع مفید است؟
2. در چه مواردی استفاده از توابع بازگشتی بهتر از حلقه‌ها است؟
3. مفهوم this در توابع معمولی و توابع پیکانی چگونه متفاوت است؟
4. مدیریت خطا چگونه باعث افزایش کیفیت کد می‌شود؟
5. این تکه کد مربوط به مدیریت خطا را تشریح کنید و بگویید که هر بخش چه کاری را انجام میدهد؟

   ```js
   try {
     // tryStatements
   } catch (exception) {
     // catchStatements
   } finally {
     // finallyStatements
   }
   ```

## 📝 نکات

- تا پایان هفته، پروژه خود و پاسخ پرسش‌ها را بارگذاری نمایید.
