<!-- English Content -->
<div class="content-en">

# SmartPark FAQ 🅿️

<div class="faq-container">

# Frequently Asked Questions

<div class="faq-item">
  <button class="faq-question">What is Abu Dhabi SmartPark?</button>
  <div class="faq-answer">
    <p>Abu Dhabi SmartPark is an AI-powered parking solution that revolutionizes urban parking in Abu Dhabi. The system helps drivers find parking spaces quickly and efficiently, reducing search times from 15-20 minutes to under 60 seconds.</p>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question">How does the real-time parking availability system work?</button>
  <div class="faq-answer">
    <p>The system uses advanced sensors and AI technology to track parking space occupancy in real-time. Users can view available parking spots through an interactive map interface, which is integrated with ArcGIS for accurate location services.</p>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question">What are the peak hours and how does pricing work?</button>
  <div class="faq-answer">
    <p>Peak hours are from 6:00 AM to 9:00 AM and 6:00 PM to 9:00 PM. The system implements dynamic pricing, which means rates may vary based on demand and parking type. This helps manage parking space availability more effectively during high-demand periods.</p>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question">Can I book a parking spot in advance?</button>
  <div class="faq-answer">
    <p>Yes, the smart booking system allows you to reserve parking spots in advance. You'll receive confirmation through SMS, and the system includes secure payment integration for a seamless experience.</p>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question">How many people are currently using the system?</button>
  <div class="faq-answer">
    <p>The system currently serves 10,000 daily users and has contributed to a 150% increase in revenue for Abu Dhabi's Government while saving approximately 3,500 hours per day in collective parking search time.</p>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question">What are the future plans for SmartPark?</button>
  <div class="faq-answer">
    <p>Future enhancements include:</p>
    <ul>
      <li>Mobile applications for iOS</li>
      <li>Advanced vehicle recognition systems</li>
      <li>AI-powered predictive analytics for parking availability</li>
      <li>Additional payment options</li>
      <li>Expansion of coverage across Abu Dhabi using open data</li>
    </ul>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question">How secure is the payment system?</button>
  <div class="faq-answer">
    <p>Our payment system is fully secured and integrated with trusted payment providers. All transactions are encrypted and processed through secure channels to ensure your financial information remains safe.</p>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question">What should I do if I need assistance?</button>
  <div class="faq-answer">
    <p>If you need help, you can:</p>
    <ol>
      <li>Contact our 24/7 customer support</li>
      <li>Use the help section in our web interface</li>
      <li>Send us an email at support@smartpark.ae</li>
    </ol>
  </div>
</div>

</div>

<style>
  .faq-container {
    background-color: white;
    border: 1px solid var(--primary-light);
    border-radius: 8px;
    padding: 20px;
    margin-top: 20px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  }

  .faq-item {
    border: 1px solid var(--primary-light);
    border-radius: 8px;
    margin-bottom: 10px;
    overflow: hidden;
  }

  .faq-question {
    background-color: white;
    color: var(--primary);
    font-weight: 500;
    width: 100%;
    text-align: left;
    padding: 15px;
    border: none;
    cursor: pointer;
    transition: all 0.2s ease;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .faq-question:hover {
    background-color: var(--primary-lighter);
  }

  .faq-question::after {
    content: '▼';
    font-size: 0.8em;
    transition: transform 0.2s ease;
  }

  .faq-item.active .faq-question::after {
    transform: rotate(180deg);
  }

  .faq-answer {
    display: none;
    padding: 15px;
    border-top: 1px solid var(--primary-light);
    background-color: white;
    color: var(--primary-hover);
  }

  .faq-item.active .faq-answer {
    display: block;
  }

  .faq-answer ul, .faq-answer ol {
    margin-left: 20px;
    margin-top: 10px;
  }

  .faq-answer li {
    margin-bottom: 5px;
  }
</style>

<script>
  document.querySelectorAll('.faq-question').forEach(button => {
    button.addEventListener('click', () => {
      const faqItem = button.parentElement;
      const wasActive = faqItem.classList.contains('active');
      
      // Close all FAQ items
      document.querySelectorAll('.faq-item').forEach(item => {
        item.classList.remove('active');
      });
      
      // If the clicked item wasn't active, open it
      if (!wasActive) {
        faqItem.classList.add('active');
      }
    });
  });
</script>

---

For more information, visit [parkit-ae.vercel.app](https://parkit-ae.vercel.app/)

</div>
</div>

<!-- Arabic Content -->
<div class="content-ar" dir="rtl">

# الأسئلة الشائعة - سمارت بارك 🅿️

<div class="faq-container">

# الأسئلة المتكررة

<div class="faq-item">
  <button class="faq-question">ما هو نظام سمارت بارك أبوظبي؟</button>
  <div class="faq-answer">
    <p>سمارت بارك أبوظبي هو حل ذكي للمواقف مدعوم بالذكاء الاصطناعي يعمل على تطوير تجربة ركن السيارات في أبوظبي. يساعد النظام السائقين في العثور على مواقف السيارات بسرعة وكفاءة، مما يقلل وقت البحث من 15-20 دقيقة إلى أقل من 60 ثانية.</p>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question">كيف يعمل نظام التوفر المفتوح للمواقف؟</button>
  <div class="faq-answer">
    <p>يستخدم النظام المتطور sensors وتكنولوجيا الذكاء الاصطناعي لمراقبة ملء مواقف السيارات بشكل مستمر. يمكن للمستخدمين عرض مواقف السيارات المتاحة عبر واجهة مفاتحة متكاملة، وهي متكاملة مع ArcGIS لخدمات الموقع بدقة.</p>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question">ما هي ساعات الطلب القصوى وكيف يعمل التسعير؟</button>
  <div class="faq-answer">
    <p>ساعات الطلب القصوى هي من 6:00 صباعا إلى 9:00 صباعا ومن 6:00 مساء إلى 9:00 مساء. ينفذ النظام تسعيرًا ديناميكيًا، مما يعني أن الأسعار تمكن من التغيير بناءً على الطلب ونوع الموقف. هذا يساعد في إدارة ملء مواقف السيارات بكفاءة أكبر خلال فترات الطلب القصوى.</p>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question">هل يمكن حجز موقف السيارة مسبقا؟</button>
  <div class="faq-answer">
    <p>نعم، يسمح نظام الحجز الذكي بتحجيز مواقف السيارات مسبقًا. ستتلقى تأكيدًا عبر ال SMS، ويشمل النظام تكاملًا آمنًا للدفع لتجربة سلسة.</p>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question">كم عدد الأشخاص الذين يستخدمون النظام الآن؟</button>
  <div class="faq-answer">
    <p>يوفر النظام الآن 10,000 مستخدم يوميًا وقد ساهم في زيادة الإيرادات بنسبة 150% لمجلس أبوظبي، مع إنقاص حوالي 3,500 ساعة يوميًا في وقت البحث عن مواقف السيارات المجمعة.</p>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question">ما هي الخطط المستقبلية لسمارت بارك؟</button>
  <div class="faq-answer">
    <p>تشمل التحسينات المستقبلية:</p>
    <ul>
      <li>تطبيقات محمولة لأندرويد</li>
      <li>أنظمة تحديد السيارات المتقدمة</li>
      <li>تحليل تنبؤي ذكي للتوفر على المواقف</li>
      <li>خيارات دفع إضافية</li>
      <li>توسيع التغطية على أبوظبي باستخدام بيانات مفتوحة</li>
    </ul>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question">كيف هو الدفع الآمن؟</button>
  <div class="faq-answer">
    <p>نظام الدفع لدينا مطور بشكل كامل ومتكامل مع مزودي الدفع الموثوقين. جميع المعاملات مشفرة ومعالجة عبر مسارات آمنة لضمان أمن معلوماتك المالية.</p>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question">ماذا يجب أن أفعل إذا كنت بحاجة إلى مساعدة؟</button>
  <div class="faq-answer">
    <p>إذا كنت بحاجة إلى مساعدة، يمكنك:</p>
    <ol>
      <li>الاتصال بدعم الخدمة المواعي لدينا 24/7</li>
      <li>استخدام قسم المساعدة في واجهة مستخدمنا الإلكترونية</li>
      <li>إرسال بريد إلكتروني إلى support@smartpark.ae</li>
    </ol>
  </div>
</div>

</div>

<style>
  .faq-container {
    background-color: white;
    border: 1px solid var(--primary-light);
    border-radius: 8px;
    padding: 20px;
    margin-top: 20px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  }

  .faq-item {
    border: 1px solid var(--primary-light);
    border-radius: 8px;
    margin-bottom: 10px;
    overflow: hidden;
  }

  .faq-question {
    background-color: white;
    color: var(--primary);
    font-weight: 500;
    width: 100%;
    text-align: left;
    padding: 15px;
    border: none;
    cursor: pointer;
    transition: all 0.2s ease;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .faq-question:hover {
    background-color: var(--primary-lighter);
  }

  .faq-question::after {
    content: '▼';
    font-size: 0.8em;
    transition: transform 0.2s ease;
  }

  .faq-item.active .faq-question::after {
    transform: rotate(180deg);
  }

  .faq-answer {
    display: none;
    padding: 15px;
    border-top: 1px solid var(--primary-light);
    background-color: white;
    color: var(--primary-hover);
  }

  .faq-item.active .faq-answer {
    display: block;
  }

  .faq-answer ul, .faq-answer ol {
    margin-left: 20px;
    margin-top: 10px;
  }

  .faq-answer li {
    margin-bottom: 5px;
  }
</style>

<script>
  document.querySelectorAll('.faq-question').forEach(button => {
    button.addEventListener('click', () => {
      const faqItem = button.parentElement;
      const wasActive = faqItem.classList.contains('active');
      
      // Close all FAQ items
      document.querySelectorAll('.faq-item').forEach(item => {
        item.classList.remove('active');
      });
      
      // If the clicked item wasn't active, open it
      if (!wasActive) {
        faqItem.classList.add('active');
      }
    });
  });
</script>

---

For more information, visit [parkit-ae.vercel.app](https://parkit-ae.vercel.app/)

</div>
</div>

