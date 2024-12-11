<div class="logo-container">
  <img src="SmartParkLogoWritingNew.svg" alt="SmartPark Logo">
</div>

<!-- English Content -->
<div class="content-en">

<div class="faq-container">
<h1>Frequently Asked Questions</h1>

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

<!-- Arabic Content -->
<div class="content-ar">

<div class="faq-container">
<h1>الأسئلة المتكررة</h1>

<div class="faq-item">
  <button class="faq-question">ما هو نظام سمارت بارك أبوظبي؟</button>
  <div class="faq-answer">
    <p>سمارت بارك أبوظبي هو حل ذكي للمواقف مدعوم بالذكاء الاصطناعي يعمل على تطوير تجربة ركن السيارات في أبوظبي. يساعد النظام السائقين في العثور على مواقف السيارات بسرعة كفاءة، مما يقلل وقت البحث من 15-20 دقيقة إلى أقل من 60 ثانية.</p>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question">كيف يعمل نظام توفر المواقف في الوقت الفعلي؟</button>
  <div class="faq-answer">
    <p>يستخدم النظام أجهزة استشعار متطورة وتقنية الذكاء الاصطناعي لتتبع إشغال مواقف السيارات في الوقت الفعلي. يمكن للمستخدمين عرض مواقف السيارات المتاحة من خلال واجهة خريطة تفاعلية، والتي تم دمجها مع ArcGIS للحصول على خدمات موقع دقيقة.</p>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question">ما هي ساعات الطروة وكيف يعمل نظام التسعير؟</button>
  <div class="faq-answer">
    <p>ساعات الذروة هي من الساعة 6:00 صباحاً حتى 9:00 صباحاً ومن 6:00 مساءً حتى 9:00 مساءً. يطبق النظام التسعير الديناميكي، مما يعني أن الأسعار قد تختلف حسب الطلب ونوع موقف السيارات. يساعد هذا في إدارة توفر مواقف السيارات بشكل أكثر فعالية خلال فترات الطلب المرتفع.</p>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question">كم عدد الأشخاص الذين يستخدمون النظام حالياً؟</button>
  <div class="faq-answer">
    <p>يخدم النظام حالياً 10,000 مستخدم يومياً وقد ساهم في زيادة إيرادات حكومة أبوظبي بنسبة 150٪ مع توفير حوالي 3,500 ساعة يومياً في وقت البحث الجماعي عن مواقف السيارات.</p>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question">ما هي الخطط المستقبلية لسمارت بارك؟</button>
  <div class="faq-answer">
    <p>تشمل التحسينات المستقبلية:</p>
    <ul>
      <li>تطبيقات للهواتف المحمولة لنظام iOS</li>
      <li>أنظمة متقدمة للتعرف على المركبات</li>
      <li>تحليلات تنبؤية مدعومة بالذكاء الاصطناعي لتوفر مواقف السيارات</li>
      <li>خيارات دفع إضافية</li>
      <li>توسيع نطاق التغطية في جميع أنحاء أبوظبي باستخدام البيانات المفتوحة</li>
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
