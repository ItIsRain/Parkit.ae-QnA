# SmartPark FAQ 🅿️

<div class="faq-container">

# Frequently Asked Questions

<div class="faq-item">
  <button class="faq-question">How do I book a parking spot?</button>
  <div class="faq-answer">
    <p>You can book a parking spot through our web interface or mobile app. Simply select your desired location, choose your parking duration, and complete the payment process. The system will confirm your booking via SMS.</p>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question">How can I extend my booking?</button>
  <div class="faq-answer">
    <p>To extend your current booking:</p>
    <ol>
      <li>Log into your account</li>
      <li>Navigate to "Active Bookings"</li>
      <li>Select the booking you want to extend</li>
      <li>Click "Extend Booking" and follow the prompts</li>
    </ol>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question">What payment methods are accepted?</button>
  <div class="faq-answer">
    <p>We accept various payment methods including:</p>
    <ul>
      <li>Credit/Debit cards</li>
      <li>Digital wallets</li>
      <li>Direct bank transfers</li>
      <li>Prepaid parking cards</li>
    </ul>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question">What is your refund policy?</button>
  <div class="faq-answer">
    <p>Refunds are processed automatically for cancellations made at least 1 hour before the booking start time. Late cancellations or no-shows are not eligible for refunds.</p>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question">How do I update my vehicle information?</button>
  <div class="faq-answer">
    <p>To update your vehicle information:</p>
    <ol>
      <li>Go to "Account Settings"</li>
      <li>Select "Vehicle Management"</li>
      <li>Choose "Edit" or "Add New Vehicle"</li>
      <li>Enter the required information</li>
      <li>Save your changes</li>
    </ol>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question">How can I view my parking history?</button>
  <div class="faq-answer">
    <p>Your parking history is available in your account dashboard:</p>
    <ol>
      <li>Log into your account</li>
      <li>Navigate to "Parking History"</li>
      <li>View all past bookings and transactions</li>
    </ol>
  </div>
</div>

<div class="faq-item">
  <button class="faq-question">How do I cancel a booking?</button>
  <div class="faq-answer">
    <p>You can cancel your booking up to 1 hour before the scheduled start time. To cancel:</p>
    <ol>
      <li>Go to "My Bookings"</li>
      <li>Select the booking you wish to cancel</li>
      <li>Click "Cancel Booking"</li>
      <li>Follow the refund instructions if applicable</li>
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

