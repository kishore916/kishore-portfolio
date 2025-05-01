# kishore-portfolio
My Personal Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kishore Kumar - Data Analyst Portfolio</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f9;
        }
        .section {
            padding: 4rem 2rem;
        }
        .profile-img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="bg-blue-600 text-white p-4 fixed w-full top-0 z-10">
        <div class="container mx-auto flex justify-between items-center">
            <h1 class="text-xl font-bold">Kishore Kumar</h1>
            <div>
                <a href="#home" class="px-3 hover:underline">Home</a>
                <a href="#about" class="px-3 hover:underline">About</a>
                <a href="#experience" class="px-3 hover:underline">Experience</a>
                <a href="#projects" class="px-3 hover:underline">Projects</a>
                <a href="#contact" class="px-3 hover:underline">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Home Section -->
    <section id="home" class="section bg-blue-100 text-center">
        <img src="https://via.placeholder.com/150" alt="Profile Picture" class="profile-img mx-auto mb-4">
        <h1 class="text-4xl font-bold mb-2">Kishore Kumar Panchananam Vishwakarma</h1>
        <p class="text-xl mb-4">Data Analyst | MSc in Data Analytics</p>
        <a href="#contact" class="bg-blue-600 text-white px-6 py-2 rounded hover:bg-blue-700">Get in Touch</a>
    </section>

    <!-- About Section -->
    <section id="about" class="section bg-white">
        <div class="container mx-auto">
            <h2 class="text-3xl font-bold mb-4 text-center">About Me</h2>
            <p class="text-lg mb-4">
                I am a Data Analyst with over 5 years of experience in compliance operations, data analysis, and cross-functional collaboration at top-tier organizations like Amazon. I specialize in SQL, Python, Tableau, and ETL processes, with a proven track record of improving operational efficiency and delivering actionable insights. I hold an MSc in Data Analytics from Dublin Business School and am passionate about leveraging data to solve complex business challenges.
            </p>
            <h3 class="text-2xl font-semibold mb-2">Technical Skills</h3>
            <ul class="list-disc pl-6">
                <li>Languages & Tools: Python, SQL, Tableau, Excel, Hubble, Query Editor</li>
                <li>Data Skills: Data Manipulation, Visualization, Statistical Modeling, Machine Learning, ETL</li>
                <li>Tools: SM9, Hubble, ServiceNow, Microsoft Office</li>
                <li>Soft Skills: Communication, Problem-Solving, Team Collaboration, Stakeholder Management</li>
            </ul>
            <h3 class="text-2xl font-semibold mb-2 mt-4">Languages</h3>
            <p>English (Fluent), Hindi (Fluent), Kannada (Fluent), Telugu (Fluent), Tamil (Conversational)</p>
        </div>
    </section>

    <!-- Experience Section -->
    <section id="experience" class="section bg-gray-100">
        <div class="container mx-auto">
            <h2 class="text-3xl font-bold mb-4 text-center">Professional Experience</h2>
            <div class="mb-6">
                <h3 class="text-2xl font-semibold">Data Analyst / Senior Associate - Product Compliance</h3>
                <p class="text-lg">Amazon Development Centre India (ADCI), Bangalore | Sep 2019 - Apr 2023</p>
                <ul class="list-disc pl-6">
                    <li>Analyzed compliance data, improving product issue resolution time by 20%.</li>
                    <li>Created automated dashboards and reports to track KPIs for global stakeholders.</li>
                    <li>Optimized complex SQL queries on Hubble for large-scale data analysis.</li>
                    <li>Streamlined ETL processes, enhancing data quality and delivery.</li>
                    <li>Led compliance audits and collaborated with legal and supply chain teams.</li>
                    <li>Managed high-priority escalations, including product recalls.</li>
                </ul>
            </div>
            <div class="mb-6">
                <h3 class="text-2xl font-semibold">System Engineer - Technical Support</h3>
                <p class="text-lg">Tata Consultancy Services (TCS) - PwC Project | Jan 2018 - Oct 2018</p>
                <ul class="list-disc pl-6">
                    <li>Supported auditors with database access and data navigation.</li>
                    <li>Ensured minimal downtime during peak operations.</li>
                    <li>Contributed to SLA achievement through timely issue resolution.</li>
                </ul>
            </div>
            <div>
                <h3 class="text-2xl font-semibold">Process Executive</h3>
                <p class="text-lg">Infosys BPM Ltd - British Telecom Process | Dec 2016 - Jan 2018</p>
                <ul class="list-disc pl-6">
                    <li>Delivered customer service for billing and technical queries.</li>
                    <li>Provided technical troubleshooting for WLAN, TV, and telephone services.</li>
                    <li>Maintained high customer satisfaction and SLA compliance.</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="section bg-white">
        <div class="container mx-auto">
            <h2 class="text-3xl font-bold mb-4 text-center">Projects</h2>
            <div class="mb-6">
                <h3 class="text-2xl font-semibold">Factors Affecting Online Shopping Behaviour</h3>
                <p class="text-lg">Jun 2024 - Aug 2024</p>
                <ul class="list-disc pl-6">
                    <li>Built machine learning models to identify key factors influencing online shopping behavior.</li>
                    <li>Applied data cleaning, EDA, and modeling techniques to deliver e-commerce insights.</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section bg-blue-100">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl font-bold mb-4">Contact Me</h2>
            <p class="text-lg mb-4">Feel free to reach out for collaboration or opportunities!</p>
            <p class="text-lg mb-2">Email: <a href="mailto:kishorekumarp47@gmail.com" class="text-blue-600 hover:underline">kishorekumarp47@gmail.com</a></p>
            <p class="text-lg mb-2">Phone: <a href="tel:+353879025674" class="text-blue-600 hover:underline">+353 87 902 5674</a></p>
            <p class="text-lg mb-2">LinkedIn: <a href="https://linkedin.com/in/kishore-kumar-514711102" class="text-blue-600 hover:underline">linkedin.com/in/kishore-kumar-514711102</a></p>
            <p class="text-lg">Location: Swords, Co. Dublin, Ireland</p>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-blue-600 text-white p-4 text-center">
        <p>&copy; 2025 Kishore Kumar. All rights reserved.</p>
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
    </script>
</body>
</html>
