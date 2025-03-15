# smartves
SmartVest: Invest Smarter, Not Harder. Discover a comprehensive investment platform offering stocks, bonds, ETFs, and more. Start investing with confidence today
Here are 30 code snippets for your SmartVest website:

1. *HTML Header*
```
<head>
  <title>SmartVest</title>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
```

2. *CSS Navigation Bar*
```
.navbar {
  background-color: #333;
  color: #fff;
  padding: 1em;
  text-align: center;
}
```

3. *JavaScript Investment Calculator*
```
function calculateInvestment(principal, rate, time) {
  return principal * Math.pow((1 + rate), time);
}
```

4. *HTML Investment Form*
```
<form>
  <label for="principal">Principal:</label>
  <input type="number" id="principal" name="principal"><br><br>
  <label for="rate">Rate:</label>
  <input type="number" id="rate" name="rate"><br><br>
  <label for="time">Time:</label>
  <input type="number" id="time" name="time"><br><br>
  <input type="submit" value="Calculate">
</form>
```

5. *CSS Investment Table*
```
.investment-table {
  border-collapse: collapse;
  width: 100%;
}

.investment-table th, .investment-table td {
  border: 1px solid #ddd;
  padding: 10px;
  text-align: left;
}
```

6. *JavaScript Chart*
```
var ctx = document.getElementById('chart').getContext('2d');
var chart = new Chart(ctx, {
  type: 'line',
  data: {
    labels: ['Jan', 'Feb', 'Mar', 'Apr', 'May'],
    datasets: [{
      label: 'Investment Growth',
      data: [10, 20, 30, 40, 50],
      backgroundColor: 'rgba(255, 99, 132, 0.2)',
      borderColor: 'rgba(255, 99, 132, 1)',
      borderWidth: 1
    }]
  }
});
```

7. *HTML Footer*
```
<footer>
  <p>&copy; 2023 SmartVest</p>
</footer>
```

8. *CSS Responsive Design*
```
@media only screen and (max-width: 768px) {
  .navbar {
    flex-direction: column;
  }
}
```

9. *JavaScript Mobile Navigation*
```
function toggleMobileNav() {
  var navbar = document.getElementById('navbar');
  navbar.classList.toggle('mobile-nav-open');
}
```

10. *HTML Social Media Links*
```
<ul>
  <li><a href="#" target="_blank">Twitter</a></li>
  <li><a href="#" target="_blank">Facebook</a></li>
  <li><a href="#" target="_blank">LinkedIn</a></li>
</ul>
```

11. *CSS Social Media Icons*
```
.social-media-icons {
  list-style: none;
  margin: 0;
  padding: 0;
}

.social-media-icons li {
  display: inline-block;
  margin-right: 10px;
}

.social-media-icons a {
  color: #333;
  font-size: 24px;
}
```

12. *JavaScript Contact Form*
```
function submitContactForm() {
  var name = document.getElementById('name').value;
  var email = document.getElementById('email').value;
  var message = document.getElementById('message').value;
  
  // Submit form data to server
}
```

13. *HTML FAQ Section*
```
<section>
  <h2>Frequently Asked Questions</h2>
  <ul>
    <li>
      <h3>What is SmartVest?</h3>
      <p>SmartVest is an investment platform that helps you grow your wealth.</p>
    </li>
    <li>
      <h3>How do I get started?</h3>
      <p>Sign up for an account and start investing today!</p>
    </li>
  </ul>
</section>
```

14. *CSS FAQ Styles*
```
.faq-section {
  background-color: #f7f7f7;
  padding: 20px;
}

.faq-section h2 {
  margin-top: 0;
}

.faq-section ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

.faq-section li {
  margin-bottom: 10px;
}

.faq-section h3 {
  font-weight: bold;
  margin-top: 0;
}
```
16. HTML Testimonials Section

<section>
  <h2>What Our Clients Say</h2>
  <div class="testimonials">
    <div class="testimonial">
      <p>"SmartVest has helped me grow my wealth significantly."</p>
      <p>- John Doe</p>
    </div>
    <div class="testimonial">
      <p>"I'm impressed with the ease of use and competitive pricing."</p>
      <p>- Jane Smith</p>
    </div>
  </div>
</section>


17. CSS Testimonials Styles

.testimonials {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.testimonial {
  background-color: #f7f7f7;
  padding: 20px;
  margin: 20px;
  width: calc(50% - 40px);
}

.testimonial p {
  font-size: 18px;
  margin-bottom: 10px;
}


18. JavaScript Navigation Menu

function toggleNavMenu() {
  var navMenu = document.getElementById('nav-menu');
  navMenu.classList.toggle('open');
}


19. HTML Investment Portfolio

<section>
  <h2>Investment Portfolio</h2>
  <table>
    <thead>
      <tr>
        <th>Asset</th>
        <th>Value</th>
        <th>Return</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Stocks</td>
        <td>$10,000</td>
        <td>10%</td>
      </tr>
      <tr>
        <td>Bonds</td>
        <td>$5,000</td>
        <td>5%</td>
      </tr>
    </tbody>
  </table>
</section>


20. CSS Investment Portfolio Styles

.investment-portfolio {
  background-color: #f7f7f7;
  padding: 20px;
}

.investment-portfolio table {
  border-collapse: collapse;
  width: 100%;
}

.investment-portfolio th, .investment-portfolio td {
  border: 1px solid #ddd;
  padding: 10px;
  text-align: left;
}


21. JavaScript Investment Portfolio Chart

var ctx = document.getElementById('investment-portfolio-chart').getContext('2d');
var chart = new Chart(ctx, {
  type: 'pie',
  data: {
    labels: ['Stocks', 'Bonds'],
    datasets: [{
      label: 'Investment Portfolio',
      data: [10000, 5000],
      backgroundColor: [
        'rgba(255, 99, 132, 0.2)',
        'rgba(54, 162, 235, 0.2)'
      ],
      borderColor: [
        'rgba(255, 99, 132, 1)',
        'rgba(54, 162, 235, 1)'
      ],
      borderWidth: 1
    }]
  }
});


22. HTML Financial News

<section>
  <h2>Financial News</h2>
  <ul>
    <li>
      <h3>Market Update: Stocks Rise Amid Economic Growth</h3>
      <p>Stocks rose sharply today amid strong economic growth and low unemployment.</p>
    </li>
    <li>
      <h3>Federal Reserve Raises Interest Rates Amid Inflation Concerns</h3>
      <p>The Federal Reserve raised interest rates today amid concerns over rising inflation.</p>
    </li>
  </ul>
</section>


23. CSS Financial News Styles

.financial-news {
  background-color: #f7f7f7;
  padding: 20px;
}

.financial-news ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

.financial-news li {
  margin-bottom: 20px;
}

.financial-news h3 {
  font-weight: bold;
  margin-top: 0;
}


24. JavaScript Financial News Ticker

function financialNewsTicker() {
  var newsItems = [
    'Market Update: Stocks Rise Amid Economic Growth',
    'Federal Reserve Raises Interest Rates Amid Inflation Concerns'
  ];
  
  var ticker = document.getElementById('financial-news-ticker');
  var newsItem
