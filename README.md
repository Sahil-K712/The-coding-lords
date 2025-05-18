<h1>EdPay - Payout Automation System for EdTech Mentors</h1>

<h2>🚀 Project Overview</h2>
<p>
EdPay is a comprehensive payout automation platform designed for EdTech companies to manage and automate mentor and instructor payments. It streamlines session tracking, role-based access, and financial reporting — making payouts transparent, auditable, and efficient.
</p>

<h2>🌐 Live Demo</h2>
<p>
  Check out the deployed version here: 
  <a href="https://edpay.netlify.app/" target="_blank" rel="noopener noreferrer">
    EdPay Live Demo
  </a>
</p>

<h2>💡 Key Features</h2>

<ul>
  <li><strong>Role-Based Access Control:</strong> Separate dashboards and features for admins and mentors.</li>
  <li><strong>Session Management:</strong> Add, edit, delete, filter, and import/export mentoring sessions.</li>
  <li><strong>Payout Automation:</strong> Smart calculation of payments with platform fee and tax deductions.</li>
  <li><strong>Receipt Generation:</strong> Generate, view, and download receipts for completed sessions.</li>
  <li><strong>Data Visualization:</strong> Charts for earnings, session type breakdown, and payout distribution.</li>
  <li><strong>Mobile-Friendly:</strong> Responsive design for all devices.</li>
</ul>

<h2>🔐 Authentication & Access</h2>

<ul>
  <li><strong>Sign In Page:</strong> Role toggle (Admin/Mentor) with form validation and demo credentials.</li>
  <li><strong>Protected Routes:</strong> Authorization via <code>ProtectedRoute.tsx</code>.</li>
  <li><strong>Auth Context:</strong> Role state and session stored in <code>AuthContext.tsx</code> using localStorage.</li>
</ul>

<h2>📊 Admin Dashboard Features</h2>

<ul>
  <li><strong>Analytics Overview:</strong> Total sessions, total payout, active mentors, and pending receipts.</li>
  <li><strong>Session Management:</strong> Add/edit/delete sessions, import/export via CSV, filter by date.</li>
  <li><strong>Mentor Management:</strong> Add/view mentors, assign sessions, generate receipts.</li>
  <li><strong>Receipts:</strong> View details, status, and generate receipts.</li>
  <li><strong>Charts:</strong> Pie chart for session types and bar chart for payout distribution.</li>
</ul>

<h2>👨‍🏫 Mentor Dashboard Features</h2>

<ul>
  <li><strong>Profile:</strong> View mentor details and statistics.</li>
  <li><strong>Session Tracking:</strong> View upcoming/completed/cancelled sessions, add notes, mark status.</li>
  <li><strong>Earnings:</strong> Total, paid, and pending earnings with a 6-month trend chart.</li>
  <li><strong>Receipts:</strong> View and download payment receipts.</li>
</ul>

<h2>📁 Components & Utilities</h2>

<ul>
  <li><strong>Layout:</strong> Responsive header, footer, and navigation with role-based links.</li>
  <li><strong>SessionDialog.tsx:</strong> Modal form for session creation with React Hook Form and Zod validation.</li>
  <li><strong>Toast Notifications:</strong> Informative, auto-dismissing alerts with duplicate prevention.</li>
</ul>

<h2>🧮 Helper Utilities</h2>

<ul>
  <li><code>payout-calculator.ts</code>: Calculates payouts after fees and taxes.</li>
  <li><code>receipt-generator.ts</code>: Generates payment receipts based on session data.</li>
  <li><code>utils.ts</code>: Handles currency formatting, date formatting, and duration calculation.</li>
</ul>

<h2>📦 Data Models</h2>

<ul>
  <li><strong>User:</strong> Admin or mentor roles with authentication info.</li>
  <li><strong>Session:</strong> Session ID, duration, type, date, status, and notes.</li>
  <li><strong>Receipt:</strong> Receipt ID, associated sessions, total amount, status, and date.</li>
</ul>

<h2>🎯 Tech Stack</h2>

<ul>
  <li>React + Vite</li>
  <li>TypeScript</li>
  <li>Tailwind CSS</li>
  <li>React Hook Form + Zod</li>
  <li>Chart.js or Recharts (for charts)</li>
</ul>

<h2>📌 Getting Started</h2>

<ol>
  <li>Clone the repo: <code>git clone https://github.com/Sahil-K712/The-coding-lords</code></li>
  <li>Cd: payout-system</li>
  <li>Install dependencies: <code>npm install</code></li>
  <li>Run the app: <code>npm run dev</code></li>
</ol>

<h2>👨‍💻 Contributors</h2>
<ul>
  <li>
    <a href="https://github.com/sahilnikalje" target="_blank" rel="noopener noreferrer">
      Sahil Nikalje
    </a>
  </li>
  <li>
    <a href="https://github.com/Sahil-K712" target="_blank" rel="noopener noreferrer">
      Sahil Kadavekar
    </a>
  </li>

</ul>
