DJ DEEPAK MUSIC - DIRECT ADMIN SYSTEM

Is version me har baar GitHub par song/config edit karne ki zarurat nahi hogi.
GitHub Pages sirf website files rakhega; songs/settings Supabase me save honge.

ONE-TIME SETUP:
1) Supabase par free account/project banao.
2) Project me Storage ke andar PUBLIC buckets exactly ye naam se banao:
   - songs
   - banners
3) SQL Editor me supabase-setup.sql ka poora code Run karo.
4) Authentication > Users me apna admin email/password user banao.
5) Supabase Project Settings/API se Project URL aur Publishable/anon key copy karo.
6) supabase-config.js me dono values paste karo. Service role/secret key KABHI paste mat karna.
7) Is folder ki index.html, admin.html, style.css, supabase-config.js ko GitHub repo ke root me upload/replace karo.
8) Admin URL kholo: https://djdeepak07.github.io/deepakmusic.github.io/admin.html
9) Apne Supabase admin email/password se login karo.

USKE BAAD:
- Admin se MP3 upload karo -> song website par aa jayega.
- Latest/Trending select kar sakte ho.
- Delete button se song hata sakte ho.
- WhatsApp, Instagram, email, subtitle, site title, banner change kar sakte ho.
- Visitors Play aur Download dono kar sakte hain.
- Naye song ke liye GitHub edit ki zarurat nahi.

IMPORTANT:
- Public bucket ka matlab song file ka public URL accessible hoga. Ye playback/download ke liye jaan-bujhkar hai.
- Sirf apne original ya legally licensed music ko upload karo.
- Supabase service_role/secret key ko frontend me mat daalna.


IMPORTANT SECURITY:
- supabase-setup.sql me 'admin@example.com' ko apne actual admin login email se replace karo.
- Admin user banane ke baad Supabase Auth me public email sign-ups disable karna best hai.
- dj-deepak buckets PUBLIC rakhne hain, kyunki visitors ko play/download karna hai.

Ab Admin me song ka naam/artist/category bhi edit karke Save kar sakte ho. Delete karne par song aur uska cover bhi remove karne ki koshish hoti hai.
