<html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Your Name | Personal Website</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f5f5f5;
      color: #222;
    }
    header {
      background: #111827;
      color: #fff;
      padding: 40px 20px;
      text-align: center;
    }
    header img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid #4f46e5;
      margin-bottom: 15px;
    }
    header h1 {
      margin: 10px 0 5px;
      font-size: 28px;
    }
    header p {
      margin: 5px 0;
      opacity: 0.9;
    }
    .container {
      max-width: 900px;
      margin: 0 auto;
      padding: 20px;
    }
    .section {
      background: #fff;
      border-radius: 8px;
      padding: 20px;
      margin-bottom: 20px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.05);
    }
    .section h2 {
      margin-top: 0;
      font-size: 22px;
      margin-bottom: 10px;
    }
    .tagline {
      font-size: 14px;
      color: #6b7280;
    }
    .cta-buttons {
      margin-top: 15px;
    }
    .btn {
      display: inline-block;
      padding: 10px 18px;
      margin: 5px 8px 0 0;
      border-radius: 999px;
      border: none;
      cursor: pointer;
      font-size: 14px;
      text-decoration: none;
    }
    .btn-primary {
      background: #4f46e5;
      color: #fff;
    }
    .btn-outline {
      background: #fff;
      color: #4f46e5;
      border: 1px solid #4f46e5;
    }
    .offer-list {
      list-style: none;
      padding: 0;
      margin: 0;
    }
    .offer-item {
      padding: 12px 0;
      border-bottom: 1px solid #e5e7eb;
    }
    .offer-item:last-child {
      border-bottom: none;
    }
    .offer-title {
      font-weight: bold;
    }
    .offer-meta {
      font-size: 13px;
      color: #6b7280;
    }
    .badges span {
      display: inline-block;
      font-size: 12px;
      padding: 3px 8px;
      border-radius: 999px;
      background: #eef2ff;
      color: #4f46e5;
      margin-right: 6px;
      margin-top: 4px;
    }
    .testimonials blockquote {
      margin: 0 0 15px;
      padding: 10px 0;
      border-bottom: 1px solid #e5e7eb;
      font-size: 14px;
      line-height: 1.5;
    }
    .testimonials cite {
      display: block;
      margin-top: 5px;
      font-size: 13px;
      color: #6b7280;
    }
    footer {
      text-align: center;
      font-size: 13px;
      color: #6b7280;
      padding: 20px;
    }
    @media (max-width: 600px) {
      header {
        padding: 30px 15px;
      }
      .container {
        padding: 15px;
      }
    }
  </style>
</head>
<body>

  <!-- HERO / INTRO -->
  <header>
    <!-- Replace src with your photo URL or remove the img tag -->
    <img src="https://via.placeholder.com/120" alt="Your profile photo">
    <h1>Your Name</h1>
    <p class="tagline">Role or Title • e.g. Senior Software Engineer | Interview Coach</p>
    <p>I help software engineers crack system design and coding interviews with clear frameworks and practical guidance.</p>
    <div class="cta-buttons">
      <a href="#contact" class="btn btn-primary">Book a session</a>
      <a href="#offers" class="btn btn-outline">View all offerings</a>
    </div>
  </header>

  <div class="container">

    <!-- QUICK INFO / HIGHLIGHTS -->
    <section class="section">
      <h2>Why work with me?</h2>
      <p>
        Over X+ years in the industry, I have mentored candidates into companies like FAANG, high-growth startups, and top tech firms.
      </p>
      <div class="badges">
        <span>4.9/5 rating</span>
        <span>70+ testimonials</span>
        <span>200+ sessions</span>
      </div>
    </section>

    <!-- OFFERINGS SECTION -->
    <section class="section" id="offers">
      <h2>Sessions and offerings</h2>
      <ul class="offer-list">
        <li class="offer-item">
          <div class="offer-title">Resume review</div>
          <div class="offer-meta">30 minutes • Online call</div>
          <p>
            Get detailed, actionable feedback on your resume to highlight your impact and align with target roles.
          </p>
        </li>
        <li class="offer-item">
          <div class="offer-title">Mock system design interview</div>
          <div class="offer-meta">60 minutes • Online call</div>
          <p>
            Practice end-to-end system design interviews with real-world scenarios and structured feedback.
          </p>
        </li>
        <li class="offer-item">
          <div class="offer-title">Interview readiness & prep plan</div>
          <div class="offer-meta">45 minutes • Online call</div>
          <p>
            Assess your current level, identify gaps, and leave with a clear, customized preparation roadmap.
          </p>
        </li>
        <li class="offer-item">
          <div class="offer-title">Ask me anything (AMA)</div>
          <div class="offer-meta">15 minutes • Chat or call</div>
          <p>
            Use this for quick questions about career moves, interviews, or tech roadmap decisions.
          </p>
        </li>
      </ul>
    </section>

    <!-- ABOUT SECTION -->
    <section class="section" id="about">
      <h2>About me</h2>
      <p>
        I’m a software engineer currently working at [Your Company], with experience in backend systems, distributed architecture, and large-scale web applications.
      </p>
      <p>
        I’ve interviewed and mentored dozens of engineers, and I enjoy simplifying complex topics into easy-to-follow steps.
      </p>
    </section>

    <!-- TESTIMONIALS SECTION -->
    <section class="section testimonials">
      <h2>Testimonials</h2>
      <blockquote>
        “The session was very detailed and helped me understand exactly where my system design approach was weak
        and how to improve it.”
        <cite>— Candidate A, SDE interview prep</cite>
      </blockquote>
      <blockquote>
        “Clear, structured feedback and real examples from the industry. I left the call with a concrete action plan.”
        <cite>— Candidate B, mid-level engineer</cite>
      </blockquote>
    </section>

    <!-- CONTACT / FORM SECTION -->
    <section class="section" id="contact">
      <h2>Book a session or say hi</h2>
      <p>
        Fill out this simple form and I’ll reply with available slots and next steps.
      </p>
      <form>
        <p>
          <label for="name">Name</label><br>
          <input type="text" id="name" name="name" style="width:100%; padding:8px;" />
        </p>
        <p>
          <label for="email">Email</label><br>
          <input type="email" id="email" name="email" style="width:100%; padding:8px;" />
        </p>
        <p>
          <label for="session-type">What are you looking for?</label><br>
          <select id="session-type" name="session-type" style="width:100%; padding:8px;">
            <option>Resume review</option>
            <option>System design mock</option>
            <option>Coding interview mock</option>
            <option>Career guidance</option>
            <option>Other / not sure</option>
          </select>
        </p>
        <p>
          <label for="message">Message (optional)</label><br>
          <textarea id="message" name="message" rows="4" style="width:100%; padding:8px;"></textarea>
        </p>
        <button type="submit" class="btn btn-primary">Submit</button>
      </form>
    </section>

  </div>

  <footer>
    © <span id="year"></span> Your Name · All rights reserved
  </footer>

  <script>
    // Small script to always show the current year in the footer
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>

</body>
</html>

