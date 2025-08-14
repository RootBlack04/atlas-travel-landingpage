# 📋 Project Specifications — Atlas Travel Landing Page



Version: EN + AR



1\) Scope / النطاق



EN: Single responsive landing page (no backend).



AR: صفحة هبوط واحدة متجاوبة (بدون باك-إند).



2\) Sections / الأقسام



Header



EN: Logo (text), navigation (Home, Destinations, Services, Contact).



AR: شعار نصّي + قائمة روابط (الرئيسية، الوجهات، الخدمات، تواصل).



Hero



EN: Big headline, short subtext, primary CTA button.



AR: عنوان رئيسي، وصف قصير، زر دعوة لاتخاذ إجراء.



Services



EN: 3 cards (title + short description + “Learn more”).



AR: 3 بطاقات (عنوان + وصف مختصر + “اعرف أكثر”).



Featured Destinations



EN: 3 destination tiles (image + caption).



AR: 3 بلاطات لوجهات (صورة + تسمية).



Footer



EN: Copyright + simple social links.



AR: حقوق النشر + روابط بسيطة للسوشيال.



3\) Layout \& Behavior / التخطيط والسلوك



EN:



Use inline-block for Services cards.



Use float + clear for Destinations grid.



Center text in Hero; full-width hero background color.



AR:



استعمل inline-block لبطاقات الخدمات.



استعمل float + clear لقسم الوجهات.



النص في الـ Hero بمحاذاة وسط وخلفية عريضة.



4\) Responsiveness / الاستجابة



Desktop (≥ 960px):



Services: 3 cards per row.



Destinations: 3 tiles per row.



Tablet (640–959px):



Services/Destinations: 2 per row (يمكنك استخدام width: 48%).



Mobile (≤ 639px):



All sections stack to 1 per row; content centered.



Media Query Example:



EN: @media (max-width: 768px) { … }



AR: استخدم ميديا كويري لتبديل العرض إلى عمود واحد على الموبايل.



5\) Typography \& Colors / الخطوط والألوان



Font: System font or Google “Inter” (optional).



Primary Color: #2563eb (CTA \& highlights)



Header/Footer BG: white #ffffff



Body BG: #f8fafc



Text: dark #0f172a, muted #64748b



AR: استخدم نفس القيم اللونية، وخط نظام أو Inter من Google Fonts.



6\) Assets / الأصول



Images: Use royalty-free placeholders (Unsplash) or your own.



Image size: 1200×800 (approx), object-fit: cover where needed.



AR: صور مجانية أو خاصة بك، حجم تقريبي 1200×800 وجودة مناسبة.



7\) Accessibility / الوصولية



EN:



Add alt text for all images.



Sufficient color contrast (check legibility on buttons).



Keyboard focus visible on links/buttons.



AR:



نص بديل للصور، تباين لوني جيد، إبراز تركيز الكيبورد على الروابط والأزرار.



8\) Performance / الأداء



EN:



Compress images; avoid very large files.



Minimize inline styles; keep one CSS file.



AR:



اضغط الصور وخلّي ملف CSS واحد بدون تكرار.



9\) Code Rules / قواعد الكود



HTML: Semantic structure, no extra wrappers.



CSS:



No Flexbox/Grid (for now, as requested).



Use inline-block, float, clear, display, and one media query at least.



Use box-sizing: border-box;.



AR: هيكل دلالي في HTML، واستعمل القواعد التي تعلّمتها فقط.



10\) Interactions / التفاعلات



EN:



Hover states for nav links, cards, and CTA buttons (e.g., slight underline/opacity).



AR: حالات Hover خفيفة للروابط والأزرار والبطاقات.



11\) Acceptance Criteria / معايير القبول



EN:



Matches goal image layout spirit.



3 services + 3 destinations visible on desktop in rows.



Fully responsive down to mobile.



No Flexbox/Grid used.



Passes basic accessibility checks (alt text, readable colors).



AR:



مطابق للفكرة، 3 خدمات و3 وجهات على الديسكتوب، متجاوب، بدون Flex/Grid، ومراعي الوصولية الأساسية.



12\) Deliverables / المخرجات



EN:



index.html, style.css, assets/ (images).



Short README (what you used + how to run).



AR:



ملفات HTML/CSS ومجلد الصور + ملف README مختصر.



13\) Stretch Goals (Optional) / مهام إضافية (اختياري)



EN: Sticky header on scroll; simple “Back to top” button; smooth scroll.



AR: هيدر ثابت، زر الرجوع للأعلى، سكرول سلس.

