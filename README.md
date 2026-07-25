
<html lang="en">
<head>
    <meta charset="UTF-8">
    <style>
        @page {
            size: A4;
            margin: 16mm 14mm;
            background-color: #ffffff;
        }
        * { box-sizing: border-box; }
        body {
            font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
            color: #2c3e50;
            line-height: 1.45;
            margin: 0;
            padding: 0;
            font-size: 10pt;
        }
        .header {
            border-bottom: 2px solid #1a365d;
            padding-bottom: 12px;
            margin-bottom: 16px;
        }
        .name {
            font-size: 20pt;
            font-weight: bold;
            color: #1a365d;
            letter-spacing: 0.5px;
            text-transform: uppercase;
            margin: 0 0 6px 0;
        }
        .contact-info {
            font-size: 9pt;
            color: #4a5568;
        }
        .contact-info span {
            display: inline-block;
            margin-right: 14px;
        }
        .contact-info span:last-child { margin-right: 0; }
        .section-title {
            font-size: 11pt;
            font-weight: bold;
            color: #1a365d;
            text-transform: uppercase;
            letter-spacing: 0.8px;
            border-bottom: 1px solid #cbd5e0;
            padding-bottom: 3px;
            margin-top: 14px;
            margin-bottom: 8px;
            page-break-after: avoid;
        }
        p { margin: 0 0 6px 0; text-align: justify; }
        .grid-table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 4px;
        }
        .grid-table td {
            vertical-align: top;
            padding: 2px 0;
        }
        .edu-header {
            font-weight: bold;
            font-size: 10.5pt;
            color: #2d3748;
        }
        .job-title {
            font-weight: bold;
            color: #2d3748;
        }
        .date-col {
            text-align: right;
            font-weight: bold;
            color: #4a5568;
            white-space: nowrap;
            width: 80px;
        }
        ul { margin: 0 0 6px 0; padding-left: 18px; }
        li { margin-bottom: 3px; }
        .info-grid {
            width: 100%;
            border-collapse: collapse;
        }
        .info-grid td {
            padding: 3px 0;
            font-size: 9.5pt;
        }
        .info-label {
            font-weight: bold;
            color: #4a5568;
            width: 130px;
        }
    </style>
</head>
<body>

    <!-- HEADER -->
    <div class="header">
        <h1 class="name">Mahmoud Abou El-Qasim Maher</h1>
        <div class="contact-info">
            <span><strong>Address:</strong> Qena, Egypt</span>
            <span><strong>Phone:</strong> +201094773686</span>
            <span><strong>Email:</strong> mahmoudqasem33@icloud.com</span>
        </div>
    </div>

    <!-- CAREER OBJECTIVE -->
    <div class="section-title">Career Objective</div>
    <p>
        A challenging career opportunity in the Oil & Gas field that utilizes my academic background and engineering skills. I look forward to gaining practical experience in both production operations and processing engineering fields within petroleum refining and petrochemical industries.
    </p>

    <!-- EDUCATION -->
    <div class="section-title">Education</div>
    <table class="grid-table">
        <tr>
            <td class="edu-header">Faculty of Engineering – Minia University</td>
            <td class="date-col">2026</td>
        </tr>
    </table>
    <p style="margin-bottom: 4px;"><strong>Degree:</strong> Bachelor's degree in Petrochemical and Gas Engineering</p>
    <p style="margin-bottom: 4px;"><strong>Overall Grade:</strong> Very Good (76%) &nbsp;|&nbsp; <strong>GPA:</strong> 2.71</p>
    <p style="margin-bottom: 6px;"><strong>Graduation Project:</strong> Hydrocracking Unit Design and Simulation (Grade: Excellent)</p>

    <!-- INTERNSHIP EXPERIENCE -->
    <div class="section-title">Internship Experience</div>
    <table class="grid-table">
        <tr>
            <td class="job-title">Pharaonic Petroleum Company (PhPC)</td>
            <td class="date-col">2023</td>
        </tr>
        <tr>
            <td class="job-title">Assiut Oil Refining Company (ASORC)</td>
            <td class="date-col">2024</td>
        </tr>
        <tr>
            <td class="job-title">Belayim Petroleum Company (PETROBEL)</td>
            <td class="date-col">2024</td>
        </tr>
        <tr>
            <td class="job-title">Rashid Petroleum Company (Rashpetco)</td>
            <td class="date-col">2025</td>
        </tr>
        <tr>
            <td class="job-title">Agiba Petroleum Company</td>
            <td class="date-col">2026</td>
        </tr>
    </table>

    <!-- COURSES -->
    <div class="section-title">Technical Courses</div>
    <ul>
        <li>Natural Gas Processing</li>
        <li>Petroleum Refining</li>
    </ul>

    <!-- SKILLS -->
    <div class="section-title">Skills</div>
    <p style="margin-bottom: 3px;"><strong>Computer Skills:</strong></p>
    <ul>
        <li>Chemical process modeling and simulation software (Aspen HYSYS)</li>
        <li>Microsoft Office applications (Word, Excel, PowerPoint)</li>
    </ul>
    <p style="margin-bottom: 3px;"><strong>Soft Skills:</strong></p>
    <ul>
        <li>Presentation and communication skills</li>
        <li>Teamwork and collaboration</li>
        <li>Time management, active listening, and problem-solving</li>
        <li>Fast self-learning ability, research, and technical analysis</li>
    </ul>

    <!-- PERSONAL INFORMATION -->
    <div class="section-title">Personal Information</div>
    <table class="info-grid">
        <tr>
            <td class="info-label">Date of Birth:</td>
            <td>7/10/2001</td>
            <td class="info-label">Gender:</td>
            <td>Male</td>
        </tr>
        <tr>
            <td class="info-label">Nationality:</td>
            <td>Egyptian</td>
            <td class="info-label">Military Status:</td>
            <td>Fully Exempted</td>
        </tr>
        <tr>
            <td class="info-label">Language Skills:</td>
            <td colspan="3">Arabic (Mother Tongue), English (Good)</td>
        </tr>
    </table>

</body>
</html>
