<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dr. Jaya Joshi - Homeopathic Healing</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Header */
        header {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 20px rgba(0,0,0,0.1);
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 0;
        }

        .logo {
            font-size: 1.8rem;
            font-weight: bold;
            color: #4a5568;
        }

        .nav-links {
            display: flex;
            list-style: none;
            gap: 2rem;
        }

        .nav-links a {
            text-decoration: none;
            color: #4a5568;
            font-weight: 500;
            transition: color 0.3s;
        }

        .nav-links a:hover {
            color: #667eea;
        }

        /* Main Content */
        main {
            margin-top: 80px;
        }

        .section {
            padding: 4rem 0;
            margin: 2rem 0;
            background: rgba(255, 255, 255, 0.95);
            border-radius: 20px;
            box-shadow: 0 8px 32px rgba(0,0,0,0.1);
        }

        .hero {
            text-align: center;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 6rem 0;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
            animation: fadeInUp 1s ease-out;
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
            animation: fadeInUp 1s ease-out 0.3s both;
        }

        .cta-button {
            display: inline-block;
            background: #48bb78;
            color: white;
            padding: 1rem 2rem;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            transition: transform 0.3s, box-shadow 0.3s;
            animation: fadeInUp 1s ease-out 0.6s both;
        }

        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(72, 187, 120, 0.3);
        }

        /* About Section */
        .about-content {
            display: grid;
            grid-template-columns: 1fr 2fr;
            gap: 3rem;
            align-items: center;
        }

        .doctor-image {
            text-align: center;
        }

        .doctor-image img {
            width: 250px;
            height: 250px;
            border-radius: 50%;
            object-fit: cover;
            border: 5px solid #667eea;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }

        .about-text h2 {
            font-size: 2.5rem;
            color: #2d3748;
            margin-bottom: 1rem;
        }

        .about-text p {
            font-size: 1.1rem;
            margin-bottom: 1.5rem;
            color: #4a5568;
        }

        /* Why Homeopathy Section */
        .benefits {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 3rem;
        }

        .benefit-card {
            background: white;
            padding: 2rem;
            border-radius: 15px;
            text-align: center;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }

        .benefit-card:hover {
            transform: translateY(-5px);
        }

        .benefit-card i {
            font-size: 3rem;
            color: #667eea;
            margin-bottom: 1rem;
        }

        /* Appointment Form */
        .appointment-form {
            background: white;
            padding: 3rem;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            max-width: 600px;
            margin: 0 auto;
        }

        .form-group {
            margin-bottom: 1.5rem;
        }

        .form-row {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 1rem;
        }

        label {
            display: block;
            margin-bottom: 0.5rem;
            color: #2d3748;
            font-weight: 500;
        }

        input, select, textarea {
            width: 100%;
            padding: 0.8rem;
            border: 2px solid #e2e8f0;
            border-radius: 8px;
            font-size: 1rem;
            transition: border-color 0.3s;
        }

        input:focus, select:focus, textarea:focus {
            outline: none;
            border-color: #667eea;
        }

        .submit-btn {
            background: #667eea;
            color: white;
            padding: 1rem 2rem;
            border: none;
            border-radius: 50px;
            font-size: 1.1rem;
            font-weight: bold;
            cursor: pointer;
            transition: background 0.3s;
            width: 100%;
        }

        .submit-btn:hover {
            background: #5a67d8;
        }

        /* Payment Section */
        .payment-options {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .payment-card {
            background: white;
            padding: 2rem;
            border-radius: 15px;
            text-align: center;
            border: 2px solid #e2e8f0;
            transition: all 0.3s;
            cursor: pointer;
        }

        .payment-card:hover {
            border-color: #667eea;
            transform: translateY(-3px);
        }

        .payment-card.selected {
            border-color: #667eea;
            background: #f7fafc;
        }

        /* Reviews Section */
        .reviews-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .review-card {
            background: white;
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }

        .stars {
            color: #ffd700;
            font-size: 1.2rem;
            margin-bottom: 1rem;
        }

        .review-text {
            font-style: italic;
            margin-bottom: 1rem;
            color: #4a5568;
        }

        .reviewer {
            font-weight: bold;
            color: #2d3748;
        }

        /* Calendar Section */
        .calendar-container {
            background: white;
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            max-width: 800px;
            margin: 0 auto;
        }

        .calendar {
            display: grid;
            grid-template-columns: repeat(7, 1fr);
            gap: 1px;
            background: #e2e8f0;
            border-radius: 10px;
            overflow: hidden;
        }

        .calendar-day {
            background: white;
            padding: 1rem;
            text-align: center;
            cursor: pointer;
            transition: all 0.3s;
            min-height: 60px;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .calendar-day:hover {
            background: #f7fafc;
        }

        .calendar-day.available {
            background: #e6fffa;
            color: #38a169;
        }

        .calendar-day.selected {
            background: #667eea;
            color: white;
        }

        .time-slots {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
            gap: 1rem;
            margin-top: 2rem;
        }

        .time-slot {
            padding: 0.8rem;
            background: #f7fafc;
            border: 2px solid #e2e8f0;
            border-radius: 8px;
            text-align: center;
            cursor: pointer;
            transition: all 0.3s;
        }

        .time-slot:hover {
            border-color: #667eea;
            background: #e6f3ff;
        }

        .time-slot.selected {
            background: #667eea;
            color: white;
            border-color: #667eea;
        }

        /* Footer */
        footer {
            background: #2d3748;
            color: white;
            text-align: center;
            padding: 2rem 0;
            margin-top: 4rem;
        }

        /* Animations */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Responsive */
        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }
            
            .about-content {
                grid-template-columns: 1fr;
                text-align: center;
            }
            
            .form-row {
                grid-template-columns: 1fr;
            }
            
            .hero h1 {
                font-size: 2rem;
            }
        }

        .section-title {
            text-align: center;
            font-size: 2.5rem;
            color: #2d3748;
            margin-bottom: 3rem;
        }

        .hidden {
            display: none;
        }
    </style>
</head>
<body>
    <header>
        <nav class="container">
            <div class="logo">Dr. Jaya Joshi</div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#why-homeopathy">Why Homoeopathy</a></li>
                <li><a href="#appointment">Book Appointment</a></li>
                <li><a href="#reviews">Reviews</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home" class="hero">
            <div class="container">
                <h1>Holistic Healing Through Homoeopathy</h1>
                <p>Natural, Safe, and Effective Treatment for Mind, Body, and Spirit</p>
                <a href="#appointment" class="cta-button">Book Your Consultation</a>
            </div>
        </section>

        <section id="about" class="section">
            <div class="container">
                <div class="about-content">
                    <div class="doctor-image">
                        <img src="https://drive.google.com/file/d/1gagto5Cuz6KwinF1y-vuPWpFzykqL-zF/view?usp=sharing" alt="Dr. Jaya Joshi">
                    </div>
                    <div class="about-text">
                        <h2>Meet Dr. Jaya Joshi</h2>
                        <p>With over 5 years of dedicated experience in homoeopathic medicine, Dr. Jaya Joshi brings a passionate commitment to holistic healing and patient care. She completed her BHMS from NHMC, Delhi University, followed by a mandatory one-year internship at various government healthcare setups.</p>
                        
                        <p>Dr. Jaya's journey in homoeopathy is marked by continuous learning and growth. She has collaborated with senior homeopaths on various publications and actively contributes to homoeopathic education worldwide. Her approach combines traditional homoeopathic principles with modern understanding of health and wellness.</p>
                        
                        <p>She specializes in women and children's health, believing that nurturing the health of mothers and children creates a foundation for a healthier future. Her practice focuses on strengthening the body's natural immune system, promoting healing from within - mentally, physically, and spiritually.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="why-homeopathy" class="section">
            <div class="container">
                <h2 class="section-title">Why Choose Homoeopathy?</h2>
                <p style="text-align: center; font-size: 1.2rem; margin-bottom: 3rem; color: #4a5568;">
                    Homoeopathy offers a gentle, natural approach to healing that works with your body's own healing mechanisms. It's particularly effective for women and children's health issues, providing safe, long-lasting solutions without side effects. Acute conditions and chronic conditions when tackled with gentle homoeopathic remedies helps improve body's own immunity. 
                </p>
                
                <div class="benefits">
                    <div class="benefit-card">
                        <i class="fas fa-leaf"></i>
                        <h3>Natural Healing</h3>
                        <p>Uses natural substances to stimulate the body's own healing response, promoting recovery without harmful side effects.</p>
                    </div>
                    
                    <div class="benefit-card">
                        <i class="fas fa-shield-alt"></i>
                        <h3>Immune System Strengthening</h3>
                        <p>Builds and strengthens your body's natural immune system, making you more resilient to future health challenges.</p>
                    </div>
                    
                    <div class="benefit-card">
                        <i class="fas fa-heart"></i>
                        <h3>Holistic Approach</h3>
                        <p>Treats the whole person - mind, body, and spirit - addressing root causes rather than just symptoms.</p>
                    </div>
                    
                    <div class="benefit-card">
                        <i class="fas fa-child"></i>
                        <h3>Safe for All Ages</h3>
                        <p>Gentle and safe for children, pregnant women, and elderly patients, with no harmful drug interactions.</p>
                    </div>
                    
                    <div class="benefit-card">
                        <i class="fas fa-balance-scale"></i>
                        <h3>Personalized Treatment</h3>
                        <p>Each treatment is tailored to the individual's unique constitution and specific health needs.</p>
                    </div>
                    
                    <div class="benefit-card">
                        <i class="fas fa-infinity"></i>
                        <h3>Long-lasting Results</h3>
                        <p>Focuses on curing diseases from their root, providing lasting health improvements rather than temporary relief.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="appointment" class="section">
            <div class="container">
                <h2 class="section-title">Book Your Appointment</h2>
                
                <div class="appointment-form">
                    <form id="appointmentForm">
                        <div class="form-row">
                            <div class="form-group">
                                <label for="fullName">Full Name *</label>
                                <input type="text" id="fullName" name="fullName" required>
                            </div>
                            <div class="form-group">
                                <label for="age">Age *</label>
                                <input type="number" id="age" name="age" required>
                            </div>
                        </div>
                        
                        <div class="form-row">
                            <div class="form-group">
                                <label for="sex">Sex *</label>
                                <select id="sex" name="sex" required>
                                    <option value="">Select Gender</option>
                                    <option value="male">Male</option>
                                    <option value="female">Female</option>
                                    <option value="other">Other</option>
                                </select>
                            </div>
                            <div class="form-group">
                                <label for="phone">Phone Number *</label>
                                <input type="tel" id="phone" name="phone" placeholder="+91 9876543210" required>
                            </div>
                        </div>
                        
                        <div class="form-group">
                            <label for="email">Email Address *</label>
                            <input type="email" id="email" name="email" required>
                        </div>
                        
                        <div class="form-group">
                            <label for="address">Complete Address *</label>
                            <textarea id="address" name="address" rows="3" placeholder="Enter your complete address for medicine delivery" required></textarea>
                        </div>
                        
                        <div class="form-group">
                            <label for="consultationType">Consultation Type *</label>
                            <select id="consultationType" name="consultationType" required>
                                <option value="">Select Consultation Type</option>
                                <option value="online">Online Consultation</option>
                                <option value="in-person">In-Person Visit</option>
                            </select>
                        </div>
                        
                        <div class="form-group">
                            <label for="healthConcern">Brief Description of Health Concern</label>
                            <textarea id="healthConcern" name="healthConcern" rows="3" placeholder="Please describe your main health concerns..."></textarea>
                        </div>
                        
                        <button type="submit" class="submit-btn">Submit Appointment Request</button>
                    </form>
                </div>
            </div>
        </section>

        <section id="payment" class="section">
            <div class="container">
                <h2 class="section-title">Payment Options</h2>
                <div class="payment-options">
                    <div class="payment-card" data-payment="cash">
                        <i class="fas fa-money-bill-wave" style="font-size: 3rem; color: #48bb78; margin-bottom: 1rem;"></i>
                        <h3>Cash Payment</h3>
                        <p>For in-person consultations</p>
                        <p><strong>Consultation Fee: ₹500</strong></p>
                    </div>
                    
                    <div class="payment-card" data-payment="upi">
                        <i class="fab fa-google-pay" style="font-size: 3rem; color: #667eea; margin-bottom: 1rem;"></i>
                        <h3>UPI Payment</h3>
                        <p>Quick and secure online payments</p>
                        <p><strong>Online Consultation: ₹500</strong></p>
                    </div>
                    
                    <div class="payment-card" data-payment="card">
                        <i class="fas fa-credit-card" style="font-size: 3rem; color: #ed8936; margin-bottom: 1rem;"></i>
                        <h3>Card Payment</h3>
                        <p>Secure card transactions</p>
                        <p><strong>All major cards accepted</strong></p>
                    </div>
                    
                    <div class="payment-card" data-payment="bank">
                        <i class="fas fa-university" style="font-size: 3rem; color: #38a169; margin-bottom: 1rem;"></i>
                        <h3>Bank Transfer</h3>
                        <p>Direct bank account transfer</p>
                        <p><strong>NEFT/RTGS available</strong></p>
                    </div>
                </div>
                
                <div id="paymentDetails" class="hidden" style="margin-top: 2rem; padding: 2rem; background: white; border-radius: 15px;">
                    <h3>Payment Details</h3>
                    <div id="paymentInfo"></div>
                </div>
            </div>
        </section>

        <section id="calendar" class="section">
            <div class="container">
                <h2 class="section-title">Select Your Preferred Date & Time</h2>
                
                <div class="calendar-container">
                    <h3 style="margin-bottom: 1rem;">Available Dates</h3>
                    <div class="calendar" id="calendar">
                        <!-- Calendar will be generated by JavaScript -->
                    </div>
                    
                    <div id="timeSlots" class="hidden">
                        <h3 style="margin: 2rem 0 1rem 0;">Available Time Slots</h3>
                        <div class="time-slots" id="availableSlots">
                            <!-- Time slots will be populated by JavaScript -->
                        </div>
                    </div>
                    
                    <div id="selectedDetails" class="hidden" style="margin-top: 2rem; padding: 1rem; background: #f7fafc; border-radius: 8px;">
                        <h4>Selected Appointment:</h4>
                        <p id="appointmentSummary"></p>
                    </div>
                </div>
            </div>
        </section>

        <section id="reviews" class="section">
            <div class="container">
                <h2 class="section-title">Patient Reviews & Testimonials</h2>
                
                <div class="reviews-grid">
                    <div class="review-card">
                        <div class="stars">★★★★★</div>
                        <div class="review-text">
                            "I am incredibly grateful to Dr. Jaya Joshi for her exceptional care. She significantly improved my asthma and period problems, making a profound difference in my quality of life. Her expertise, patience and personalized treatment plan were outstanding. I highly recommend her to anyone seeking a compassionate and knowledgeable doctor."
                        </div>
                        <div class="reviewer">- Tipti Kohli, Noida</div>
                    </div>
                    
                    <div class="review-card">
                        <div class="stars">★★★★★</div>
                        <div class="review-text">
                            "If you are struggling with long-term medical condition, like nasal polyps, I can't recommend Dr. Jaya enough. Her patience and in-depth analysis what truly set her apartment. She doesn't just treat the symptoms; she gets to the root of the problem. My own experience with nasal polyps was life-changing. Dr. Jaya listened carefully, suggested the right course of action, and I felt a real improvement in my health. If you're looking for a doctor who truly cares and gets results, Dr. Jaya is the one to see. Thanks you Dr. Jaya for your dedication to your patients!"
                        </div>
                        <div class="reviewer">- Vinod Pandey, Delhi</div>
                    </div>
                    
                    <div class="review-card">
                        <div class="stars">★★★★★</div>
                        <div class="review-text">
                            "Very effective treated Sinus, cyst which was repeatedly developing"
                        </div>
                        <div class="reviewer">- Bhaskar Joshi, Noida</div>
                    </div>
                    
                    <div class="review-card">
                        <div class="stars">★★★★★</div>
                        <div class="review-text">
                            "Thank you Dr Jaya for giving me the best treatment."
                        </div>
                        <div class="reviewer">- Yamini Sharma, Delhi</div>
                    </div>
                    
                    <div class="review-card">
                        <div class="stars">★★★★★</div>
                        <div class="review-text">
                            "Excellent consultation experience. Dr. Jaya takes time to understand the root cause and provides personalized treatment. My digestive issues are much better now."
                        </div>
                        <div class="reviewer">- Vikram Singh, Jaipur</div>
                    </div>
                    
                    <div class="review-card">
                        <div class="stars">★★★★★</div>
                        <div class="review-text">
                            "The online consultation process is very smooth. Dr. Jaya is knowledgeable, compassionate, and her treatment approach is comprehensive. Home medicine delivery is a great service."
                        </div>
                        <div class="reviewer">- Sunita Agarwal, Pune</div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2024 Dr. Jaya Joshi - Homeopathic Healing. All rights reserved.</p>
            <p>Email: drjayahomeo@gmail.com | Phone: +91-8130747080</p>
            <p>Committed to your holistic health and well-being</p>
        </div>
    </footer>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Payment option selection
        document.querySelectorAll('.payment-card').forEach(card => {
            card.addEventListener('click', function() {
                document.querySelectorAll('.payment-card').forEach(c => c.classList.remove('selected'));
                this.classList.add('selected');
                
                const paymentType = this.dataset.payment;
                const paymentDetails = document.getElementById('paymentDetails');
                const paymentInfo = document.getElementById('paymentInfo');
                
                let info = '';
                switch(paymentType) {
                    case 'cash':
                        info = '<p>Please bring exact change for the consultation fee when you visit the clinic.</p>';
                        break;
                    case 'upi':
                        info = '<p><strong>UPI ID:</strong> drjayajoshi@paytm</p><p><strong>Phone Number:</strong> +91-XXXXXXXXXX</p><p>Scan QR code or use UPI ID to make payment</p>';
                        break;
                    case 'card':
                        info = '<p>Secure payment gateway will be available during checkout. We accept Visa, MasterCard, and RuPay cards.</p>';
                        break;
                    case 'bank':
                        info = '<p><strong>Account Name:</strong> Dr. Jaya Joshi</p><p><strong>Account Number:</strong> XXXXXXXXXXXX</p><p><strong>IFSC Code:</strong> XXXXXXXXXX</p><p><strong>Bank:</strong> State Bank of India</p>';
                        break;
                }
                
                paymentInfo.innerHTML = info;
                paymentDetails.classList.remove('hidden');
            });
        });

        // Calendar functionality
        function generateCalendar() {
            const calendar = document.getElementById('calendar');
            const today = new Date();
            const currentMonth = today.getMonth();
            const currentYear = today.getFullYear();
            
            // Days of the week header
            const daysOfWeek = ['Sun', 'Mon', 'Tue', 'Wed', 'Thu', 'Fri', 'Sat'];
            daysOfWeek.forEach(day => {
                const dayHeader = document.createElement('div');
                dayHeader.textContent = day;
                dayHeader.style.fontWeight = 'bold';
                dayHeader.style.background = '#4a5568';
                dayHeader.style.color = 'white';
                calendar.appendChild(dayHeader);
            });
            
            // Generate calendar days for next 30 days
            for (let i = 0; i < 30; i++) {
                const date = new Date(today);
                date.setDate(today.getDate() + i);
                
                const dayElement = document.createElement('div');
                dayElement.className = 'calendar-day';
                dayElement.textContent = date.getDate();
                
                // Skip Sundays and make some days available
                if (date.getDay() !== 0 && i > 0) {
                    dayElement.classList.add('available');
                    dayElement.addEventListener('click', () => selectDate(date, dayElement));
                }
                
                calendar.appendChild(dayElement);
            }
        }

        function selectDate(date, element) {
            document.querySelectorAll('.calendar-day').forEach(day => day.classList.remove('selected'));
            element.classList.add('selected');
            
            showTimeSlots(date);
        }

        function showTimeSlots(date) {
            const timeSlots = document.getElementById('timeSlots');
            const slotsContainer = document.getElementById('availableSlots');
            
            // Clear existing slots
            slotsContainer.innerHTML = '';
            
            // Generate time slots (9 AM to 6 PM, excluding 1-2 PM lunch break)
            const slots = [
                '09:00 AM', '09:30 AM', '10:00 AM', '10:30 AM', '11:00 AM', '11:30 AM',
                '12:00 PM', '12:30 PM', '02:00 PM', '02:30 PM', '03:00
