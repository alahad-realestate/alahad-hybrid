[README-alahad-hybrid.md](https://github.com/user-attachments/files/23141182/README-alahad-hybrid.md)
<p align="center">
  <img src="assets/logo.jpg" alt="شعار منصة العهد العقارية" width="160" style="border-radius:16px;">
</p>

<h1 align="center">منصة العهد العقارية | Al-Ahd Real Estate Platform</h1>

<p align="center">
  موقع إلكتروني احترافي لمكتب <strong>منصة العهد العقارية</strong> في الجبيل الصناعية – مكتب عقار معتمد متخصص في البيع، الشراء، التأجير، وإدارة الأملاك.
</p>

---

## 🏗️ عن المشروع
تم إنشاء هذا الموقع كنسخة هجينة (**Hybrid Website**) محسّنة لمحركات البحث **SEO + Schema JSON-LD**  
ويدعم اللغتين **العربية والإنجليزية**، مع تضمين:
- **Google Analytics 4 (G-F68WDKX19K)**  
- **Chatbase AI Assistant (cMdnFJwSFiXB5Z8fzaAoJ)**  

---

## ⚙️ المميزات
- تصميم سريع ومتجاوب لجميع الأجهزة 📱💻  
- صفحتان رئيسيتان:  
  - 🏠 `index.html` — الرئيسية  
  - 📬 `contact.html` — تواصل معنا  
- روابط مدمجة لجميع حسابات التواصل  
- خريطة Google Maps مباشرة في الصفحة  
- إعدادات SEO كاملة:
  - ملف `robots.txt`  
  - خريطة `sitemap.xml`  
  - ترميز Schema JSON-LD  
- دعم لغتين مع زر تبديل اللغة  
- تتبع Google Analytics جاهز  
- مساعد عقاري ذكي يظهر أسفل يمين الصفحة  

---

## 🧩 الملفات الأساسية

| الملف | الوصف |
|-------|--------|
| `index.html` | الصفحة الرئيسية للموقع |
| `contact.html` | صفحة تواصل معنا |
| `style.css` | ملف التنسيق العام |
| `robots.txt` | ملف السماح للفهرسة |
| `sitemap.xml` | خريطة XML لفهرسة Google |
| `assets/` | يحتوي على شعار المكتب والصور |

---

## 🧠 كود المساعد العقاري الذكي Chatbase

```html
<!-- 🤖 Chatbase AI Assistant -->
<script>
(function(){
  if(!window.chatbase||window.chatbase("getState")!=="initialized"){
    window.chatbase=(...arguments)=>{
      if(!window.chatbase.q){window.chatbase.q=[]}
      window.chatbase.q.push(arguments)
    };
    window.chatbase=new Proxy(window.chatbase,{
      get(target,prop){
        if(prop==="q"){return target.q}
        return(...args)=>target(prop,...args)
      }
    });
  }
  const onLoad=function(){
    const script=document.createElement("script");
    script.src="https://www.chatbase.co/embed.min.js";
    script.id="cMdnFJwSFiXB5Z8fzaAoJ";
    script.domain="www.chatbase.co";
    document.body.appendChild(script);
  };
  if(document.readyState==="complete"){onLoad()}
  else{window.addEventListener("load",onLoad)}
})();
</script>
<!-- ✅ End Chatbase -->
```

---

## 📊 كود Google Analytics 4

```html
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-F68WDKX19K"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-F68WDKX19K');
</script>
```

---

## 🗺️ كود خريطة موقع المكتب

```html
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3551.0437146467207!2d49.554262523893634!3d27.123433051001978!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3e350f149cfeca91%3A0x22354686078f6ea3!2z2YXZhti12Kkg2KfZhNi52YfYryDYp9mE2LnZgtin2LHZitip!5e0!3m2!1sar!2ssa!4v1761373305995!5m2!1sar!2ssa"
 width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"
 referrerpolicy="no-referrer-when-downgrade"></iframe>
```

---

## 📬 بيانات التواصل

| الوسيلة | التفاصيل |
|----------|------------|
| 📞 واتساب | [0530397770](https://wa.me/966530397770) |
| 📧 البريد الإلكتروني | [alahad_realestate@yahoo.com](mailto:alahad_realestate@yahoo.com) |
| 🐦 X (تويتر) | [@AlahadRrealstat](https://x.com/AlahadRrealstat) |
| 💼 LinkedIn | [منصة العهد العقارية](https://www.linkedin.com/in/alahad-realestate-237377390/) |
| 📘 Facebook | [صفحة فيسبوك](https://www.facebook.com/profile.php?id=61582549690029) |
| 🎵 TikTok | [@al3had_realestate](https://www.tiktok.com/@al3had_realestate?_t=ZS-90q2qHo3Diz&_r=1) |

---

## 🚀 طريقة النشر

### 1. رفع الملفات إلى GitHub
- المستودع:  
  [`https://github.com/alahad-realestate/alahad-hybrid`](https://github.com/alahad-realestate/alahad-hybrid)
- الملفات المطلوبة:
  ```
  index.html
  contact.html
  style.css
  robots.txt
  sitemap.xml
  assets/
  ```

### 2. ربط GitHub مع Netlify
- من Netlify اختر **Import from GitHub**
- اختر المستودع `alahad-hybrid`
- اضغط **Deploy Site**

### 3. تأكيد التحليلات
- الدخول إلى **Google Analytics → Realtime**
- فتح الموقع `https://alahad-hybrid.netlify.app`
- يجب أن ترى جلسة مباشرة (✅ تم الاتصال)

---

## 📜 رخصة
© 2025 منصة العهد العقارية – جميع الحقوق محفوظة.  
استخدام المحتوى أو الكود لأغراض تجارية يتطلب إذن مسبق من إدارة المكتب.
