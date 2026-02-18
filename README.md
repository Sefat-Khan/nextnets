<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NextNets – Laravel Project</title>
    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            line-height: 1.7;
            background-color: #f9fafb;
            color: #1f2937;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 900px;
            margin: auto;
            padding: 40px 20px;
            background: #ffffff;
        }
        h1, h2, h3 {
            color: #111827;
        }
        h1 {
            font-size: 2.5rem;
            margin-bottom: 5px;
        }
        h2 {
            border-bottom: 2px solid #e5e7eb;
            padding-bottom: 5px;
            margin-top: 40px;
        }
        code, pre {
            background: #111827;
            color: #e5e7eb;
            padding: 12px;
            border-radius: 6px;
            display: block;
            overflow-x: auto;
        }
        ul {
            margin-left: 20px;
        }
        .badge {
            display: inline-block;
            background: #2563eb;
            color: white;
            padding: 4px 10px;
            border-radius: 20px;
            font-size: 0.85rem;
            margin-right: 8px;
        }
        .highlight {
            background: #eff6ff;
            padding: 15px;
            border-left: 4px solid #2563eb;
            border-radius: 6px;
            margin-top: 20px;
        }
        .screenshots {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 20px;
            margin-top: 25px;
        }
        .screenshots img {
            width: 100%;
            border-radius: 10px;
            border: 1px solid #e5e7eb;
            box-shadow: 0 8px 20px rgba(0,0,0,0.08);
        }
        .screenshots p {
            text-align: center;
            font-size: 0.9rem;
            color: #6b7280;
            margin-top: 8px;
        }
        .footer {
            text-align: center;
            margin-top: 60px;
            color: #6b7280;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

<div class="container">

    <h1>🚀 NextNets</h1>
    <p><strong>Study Abroad & Visa Consulting Platform (Laravel)</strong></p>

    <span class="badge">Laravel</span>
    <span class="badge">PHP</span>
    <span class="badge">MySQL</span>
    <span class="badge">MVC</span>

    <p>
        <strong>NextNets</strong> is a modern web application built with 
        <strong>Laravel</strong>, designed for education consultancies offering 
        <strong>study abroad guidance</strong>, <strong>visa assistance</strong>, 
        and <strong>student support services</strong>.
    </p>

    <div class="highlight">
        This project follows Laravel best practices and provides a clean, scalable
        foundation for real-world production systems.
    </div>

    <h2>📸 Project Screenshots</h2>
    <p>
        Below are sample screenshots of the NextNets platform.  
        Replace the image files with your own project screenshots.
    </p>

    <div class="screenshots">
        <div>
            <img src="screenshots/homepage.png" alt="NextNets Homepage">
            <p>Homepage</p>
        </div>
        <div>
            <img src="screenshots/study-programs.png" alt="Study Programs Page">
            <p>Study Programs</p>
        </div>
        <div>
            <img src="screenshots/contact.png" alt="Contact Page">
            <p>Contact Page</p>
        </div>
    </div>

    <h2>✨ Key Features</h2>
    <ul>
        <li><strong>Laravel MVC Architecture</strong> – clean separation of logic and views</li>
        <li><strong>Study Abroad Platform</strong> – programs, campuses, and destinations</li>
        <li><strong>Visa Success Stories</strong> – real outcomes and guidance</li>
        <li><strong>English Test Information</strong> – IELTS and proficiency guidance</li>
        <li><strong>Responsive Design</strong> – mobile, tablet, and desktop friendly</li>
        <li><strong>Secure Configuration</strong> – environment-based settings</li>
    </ul>

    <h2>🛠️ Tech Stack</h2>
    <ul>
        <li><strong>Backend:</strong> Laravel (PHP)</li>
        <li><strong>Frontend:</strong> Blade Templates, HTML5, CSS3</li>
        <li><strong>Database:</strong> MySQL (configurable)</li>
        <li><strong>Tooling:</strong> Composer, Artisan CLI</li>
    </ul>

    <h2>📂 Project Structure</h2>
    <pre>
nextnets/
├── app/
├── routes/
├── resources/
│   ├── views/
│   └── assets/
├── public/
├── database/
├── screenshots/
│   ├── homepage.png
│   ├── study-programs.png
│   └── contact.png
├── .env.example
└── composer.json
    </pre>

    <h2>⚙️ Installation & Setup</h2>

    <pre>
git clone https://github.com/Sefat-Khan/nextnets.git
cd nextnets
composer install
cp .env.example .env
php artisan key:generate
php artisan serve
    </pre>

    <h2>🎯 Use Cases</h2>
    <ul>
        <li>Education consultancy websites</li>
        <li>Study abroad & immigration agencies</li>
        <li>Laravel portfolio project</li>
        <li>Base for SaaS or CRM platforms</li>
    </ul>

    <h2>📈 Future Enhancements</h2>
    <ul>
        <li>User authentication & admin dashboard</li>
        <li>Online application system</li>
        <li>Email notifications</li>
        <li>Content Management System (CMS)</li>
        <li>REST API integration</li>
    </ul>

    <h2>📄 License</h2>
    <p>
        This project is open-source and available under the <strong>MIT License</strong>.
    </p>

    <h2>⭐ Support</h2>
    <p>
        If you find this project useful, please consider giving it a ⭐ on GitHub.
    </p>

    <div class="footer">
        © 2026 NextNets — Built with Laravel ❤️
    </div>

</div>

</body>
</html>
