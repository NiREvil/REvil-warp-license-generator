$$\small \text{W L G is $\forall{r_n = 108}$}$$

----

$$\color{silver} \LARGE \text{WarpLicenseGenerator}$$ \ R $\sum{vil_t = \mathbb{NI}\infty}$} $$


$$\color{silver} \Huge \text{\R $\sum{\vil_t = \mathbb{N108}\infty}$}$$


---
---




[🇬🇧 Dive into the English descriptions](README.md)

## تولید نامحدود لایسنس وارپ 
> Warp Licenses with 24.59 petabyte traffic volume.
>
> جدا نمیدونم واسه توضیحات بخش فارسی چی بنویسم. مشخصه دیگه همه چی، همون کلید لایسنسی که ربات های تلگرامی با اما و اگر و جوین اجباری تو چنل ایمو و محدودیت روزانه یک لایسنس میدادن رو با این اسکریپت میگیریم هر پونزده ثانیه یه لایسنس میتونه بسازه. کلید تکراری وجود نداره، کلید با ظرفیت کمتر از 24 پتابایت وجود نداره.

### واسه چه کارهایی به درد می‌خوره؟؟
- خب اول از همه برای تبدیل کلاینت 1.1.1.1 وارپ معمولی به وارپ پلاس نیاز به کلید داریم.
- برای ساختن کانفیگ وایرگارد برای کلاینت‌هایnekobox، v2rayng و Hiddify و Streisand و ... دیگه نیاز به لایسنس داریم.
- برای ساخت کانفیگ‌های سینگ‌باکس علی الخصوص اخیرا با روشی که برای هیدیفای لینک ساب درست میکنیم همگی لایسنس لازم دارن.
- و یه سری چیز دیگه ک واقعا حال نوشتنش رو ندارم،

میخواستم تو کانال یه پست برای آیفونی‌ها بذارم ک آموزش ساخت کانفیک وارپ بود بعد متوجه شدم اینا نه میتونن لایسنس بسازن و نه حتی آی‌پی تمیز وارپ اسکن کنن، ک خب هردو مشکل حل شد، برا اسکن آی‌پی هم چندتا دستور نوشتم واسه ترمینال لینوکس روی آیفون ک میذارم تو کانال.


  ## نحوه استفاده

ببین کد پایتونه دیکه، درست عین ربات وورکرسازمون که تو python anywhere اجرا کردیم میشه با بقیه هم اینکارو کرد.
پس یکی از روش ها کلون کردن مخزن تو یه سرویس میزبانی کد و اجرای اونه
برای مثال خود `replit` رو در نظر بگیر، تنها به یک اکانت رایگان نیاز داری، بعد از ساخت اکانت تو بخش template یه نمونه پایتونی ایجاد میکنی و بعد از کنسول داخل پروژه با دستور `git clone` فایل‌ها رو داخل سایت آپلود کرده و پیش نیاز هارو نصب و اجرا میکنیم.


## اجرا توسط Termux
>  **روشی ک مورد علاقه خودمو خیلی از شماهاست !**

### نصب آسان 
در صورت بروز خطا و اجرا نشدن از پروسه نصب عادی پیروی کنید.
```bash
bash -c "$(curl -fsSL https://raw.githubusercontent.com/NiREvil/WLG/main/install.sh)"
```

### نصب عادی
1. در مرحله اول پروژه رو کلون کنید:
```bash
git clone https://github.com/NiREvil/WLG.git
```
2. به فولدر پروژه برید:
```bash
cd WLG
```
3. دسترسی لازم برای اجرا شدن فایل requirement.sh رو به اون بدید:
```bash
chmod +x requirement.sh
```

4. و اون رو فراخوانی کنید با دستور:
```bash
./requirement.sh
```
5. در نهایت اجرای `main.py` 

```bash
python3 main.py
```

در این مرحله کد اجرا میشه و از شما میپرسه چندتا لایسنس نیاز دارید براتون بسازه؟ فرضا میزنیم دوتا 

<p align="left">
  <br><img src="https://github.com/NiREvil/workers-cloudflare/blob/main/Other/pics/WLG%201.png" width="360px">
</p>

شروع می‌کنه به ساخت و ارسال لایسنس‌ها، هر لایسنس که ارسال میشه باید 15 ثانیه به اصطلاح بخوابه (بخاطر الگوریتم محاسبه) و بعد از 15 ثانیه دومی رو ارسال میکنه و ادامه ...
تو این مرحله لازم نیست کپی کنید کلیدهارو. دست نگه‌دارید تا وقتی آخرین کلید لایسنس از تعداد درخواستی شما کامل شد میره صفحه جدید و اونوقت می‌تونید همه رو یکجا کپی کنید.

<p align="right">
  <br><img src="https://github.com/NiREvil/workers-cloudflare/blob/main/Other/pics/WLG%202.png" width="360px">
</p>


> از دفعات بعدی

#### واسه گرفتن لایسنس دیکه نیاز نیست مراحل کلون مخزن و نصب و ... رو انجام بدیم. فقط وارد فولدر ابزار شده و فایل اصلی رو اجرا میکنیم یا به شکل تک دستور کد رو اجرا میکنیم:
```bash
cd WLG && python3 main.py
```
#### و یا مرحله مرحله، اول ورود به دایرکتوری:
```bash
cd WLG
```
#### و سپس اجرای فایل اصلی کد: 
```bash
python3 main.py
```


### بروزرسانی کد از مخزن گیت‌هاب
بد نیست هر از گاهی قبل از اجرای کد دستور `git pull` بزنیم تا اگر توسعه دهنده کد تغییراتی در اون داده بود یا فایلی اضافه کرده بود برای ما هم اعمال بشه
```bash
cd WLG && git pull
```


<p align="center">
  <br><img src="https://github.com/NiREvil/workers-cloudflare/blob/main/Other/pics/WLG%203.png" width="360px">
</p>
همین، تامام. سوالی بود تو کامنت‌ها بپرسید.


[![Telegram Badge](https://img.shields.io/badge/Telegram-Profile-informational?style=flat&logo=telegram&logoColor=white&color=1CA2F1)](https://t.me/F_NiREvil)


### کنجکاو باشید. 🤍🪐 
---
### باکس دانلود ترماکس اندروید

| منبع | لینک‌های دانلود |
|:--------:| -------------:|
| F-Droid | [Get it Now](https://f-droid.org/en/packages/com.termux)|
|  GitHub :octocat:| [Get it Now](https://github.com/termux/termux-app/releases)|
|Google Play| [Get it Now](https://play.google.com/store/apps/details?id=com.termux)|
| نحوه رفع مشکل نصب و اجرای پکیج ها در اندروید هفت و پایین‌تر | [Fix Errors](https://t.me/F_NiREvil/5040)

> پیشنهاد میکنم حتما از گیت‌هاب نصب کنید.
> 
> نسخه فروشگاه گوگل باگ‌های بسیار زیادی داره و نسخه اف هم با خیلی از دستگاه‌ها سازگار نیست،
> بهترین انتخاب مخزن گیت‌هاب برنامه است.
----
![Alt Tag](https://i.imgur.com/PYV4crq.png "FUCKOFF")


----



> توضیحات غیرضروری:


Our license Generator utilizes specialized algorithms that are both sophisticated and simple.

The $\color{gold} \large \text{RE function}$ part of a consistent whole $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Cl
$$\Gamma(w) = \int_0^\infty t^{w-1}g^{-t}dt$$

$$\mathbb{W} = \{ N \in \mathbb{RE} : a > 128 \}$ \, $\mathrm{w} = \sum_{n=36}^{\infty} \dfrac{36}{RE!}$$

$\prod_{i=1}^{n} n_w - 108$


$$
RE_{n,v} = 
\begin{pmatrix}
RE_{1,1} & RE_{1,2} & \cdots & RE_{1,12} \\
N_{2,1} & N_{2,2} & \cdots & N_{2,24} \\
\vdots & \vdots & \ddots & \vdots \\
W_{3,1} & W_{3,2} & \cdots & W_{3,36} 
\end{pmatrix}
$$

$$
f(x)=
\begin{cases}
1/d_{ij} & \quad \text{when c.cloudflare $d_{ij} \leq 108$}\\ 
36 & \quad \text{\WLG}
\end{cases}
$$

