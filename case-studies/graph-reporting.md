<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Microsoft Graph IAM Reporting Automation | Nicholas Tjhung</title>
  <link rel="stylesheet" href="../style.css">
</head>

<body>

<header class="site-header">
  <div class="container nav">
    <a href="../index.html" class="brand">
      <span class="avatar-small">NT</span>
      <span>Nicholas Tjhung</span>
    </a>

    <nav class="nav-links">
      <a href="../index.html">Home</a>
      <a href="../projects.html">Projects</a>
      <a href="../resume.html">Resume</a>
      <a href="../contact.html">Contact</a>
      <a href="https://github.com/ntjhung">GitHub</a>
    </nav>
  </div>
</header>

<main class="container">

  <section class="hero" style="grid-template-columns: 1fr; max-width: 980px;">
    <div>
      <p class="eyebrow">IAM Case Study</p>

      <h1>Microsoft Graph IAM Reporting Automation</h1>

      <p class="hero-subtitle">
        A Microsoft Graph and PowerShell automation project focused on exporting Microsoft Entra ID users, groups, group memberships, CSV reports, and audit evidence for access review and IAM operations support.
      </p>

      <div class="badge-row">
        <span class="badge">Microsoft Graph</span>
        <span class="badge">PowerShell</span>
        <span class="badge">REST API</span>
        <span class="badge">CSV Reporting</span>
        <span class="badge">Group Membership Review</span>
        <span class="badge">Audit Evidence</span>
        <span class="badge">Troubleshooting</span>
      </div>

      <div class="cta-row">
        <a class="btn btn-primary" href="../projects.html">Back to Projects</a>
        <a class="btn btn-secondary" href="../resume.html">View Resume</a>
        <a class="btn btn-secondary" href="../contact.html">Contact Me</a>
      </div>
    </div>
  </section>

  <section class="section">
    <div class="case-layout">

      <article class="case-card">
        <h2>Project Summary</h2>
        <p>
          This project demonstrates IAM reporting automation using Microsoft Graph and PowerShell. The lab simulates how an IAM team can export users, groups, group memberships, and access evidence from Microsoft Entra ID.
        </p>

        <p>
          The goal was to show how automation can support audit readiness, access reviews, identity governance, troubleshooting, and repeatable IAM operations.
        </p>
      </article>

      <aside class="case-card">
        <h2>Tools and Concepts</h2>

        <div class="badge-row">
          <span class="badge">Microsoft Entra ID</span>
          <span class="badge">Microsoft Graph</span>
          <span class="badge">PowerShell</span>
          <span class="badge">Invoke-RestMethod</span>
          <span class="badge">REST API</span>
          <span class="badge">CSV Exports</span>
          <span class="badge">Group Membership</span>
          <span class="badge">Audit Evidence</span>
        </div>
      </aside>

    </div>
  </section>

  <section class="section">
    <div class="case-layout">

      <article class="case-card">
        <h2>Business Problem</h2>
        <p>
          IAM teams often need to provide reports for audits, access reviews, security investigations, and user lifecycle management. Manually collecting user, group, and membership data can be slow, inconsistent, and error-prone.
        </p>

        <p>
          Automating IAM reports helps standardize evidence collection, reduce manual work, improve access review support, and make identity data easier to validate during audits or security reviews.
        </p>
      </article>

      <aside class="case-card">
        <h2>Why It Matters</h2>
        <ul class="case-list">
          <li>Improves audit readiness with repeatable reports</li>
          <li>Supports access reviews with group membership exports</li>
          <li>Reduces manual evidence collection work</li>
          <li>Helps identify users and groups that need review</li>
          <li>Creates CSV files that can be shared with reviewers</li>
          <li>Shows practical troubleshooting when modules fail</li>
        </ul>
      </aside>

    </div>
  </section>

  <section class="section">
    <div class="case-card">
      <h2>What I Built</h2>

      <ul class="case-list">
        <li>Created IAM reporting scripts using PowerShell.</li>
        <li>Used Microsoft Graph to export Microsoft Entra ID users.</li>
        <li>Used Microsoft Graph to export Microsoft Entra ID groups.</li>
        <li>Exported group membership reports for access review support.</li>
        <li>Generated CSV reports that could be used as audit evidence.</li>
        <li>Created a reporting plan for IAM operations.</li>
        <li>Collected screenshots as project evidence.</li>
        <li>Used a REST-based Microsoft Graph approach to work around module loading issues.</li>
      </ul>
    </div>
  </section>

  <section class="section">
    <h2 class="section-title">Screenshots and Evidence</h2>
    <p class="section-subtitle">
      These screenshots show the Microsoft Graph REST script, exported report previews, and group membership reporting evidence.
    </p>

    <div class="screenshot-grid">

      <article class="screenshot-card">
        <img src="../assets/graph-reporting/graph-rest-script-success.png" alt="Microsoft Graph REST script success screenshot">
        <div>
          <h3>Graph REST Script Success</h3>
          <p>PowerShell output showing the REST-based Microsoft Graph reporting script running successfully.</p>
        </div>
      </article>

      <article class="screenshot-card">
        <img src="../assets/graph-reporting/all-users-report-preview.png" alt="All users report preview screenshot">
        <div>
          <h3>All Users Report Preview</h3>
          <p>CSV report preview showing exported Microsoft Entra ID user data for IAM reporting.</p>
        </div>
      </article>

      <article class="screenshot-card">
        <img src="../assets/graph-reporting/group-membership-report-preview.png" alt="Group membership report preview screenshot">
        <div>
          <h3>Group Membership Report</h3>
          <p>CSV report preview showing group membership data used for access review support.</p>
        </div>
      </article>

    </div>
  </section>

  <section class="section">
    <div class="case-layout">

      <article class="case-card">
        <h2>Reporting Workflow</h2>
        <p>
          The reporting workflow was designed to simulate how an IAM team can gather identity data, export it into reviewable formats, and save evidence for access reviews or audit requests.
        </p>

        <ul class="case-list">
          <li>Connect to Microsoft Graph.</li>
          <li>Query user objects from Microsoft Entra ID.</li>
          <li>Query group objects from Microsoft Entra ID.</li>
          <li>Query group membership details.</li>
          <li>Export results into CSV files.</li>
          <li>Review the reports for access review or audit support.</li>
          <li>Save screenshots and report files as evidence.</li>
        </ul>
      </article>

      <article class="case-card">
        <h2>Reports Created</h2>

        <ul class="case-list">
          <li>
            <strong>All Users Report:</strong> Exported user data from Microsoft Entra ID.
          </li>
          <li>
            <strong>All Groups Report:</strong> Exported group data from Microsoft Entra ID.
          </li>
          <li>
            <strong>Group Membership Report:</strong> Exported group-to-user relationships for access review support.
          </li>
          <li>
            <strong>Audit Evidence Screenshots:</strong> Captured script output and CSV previews as visual proof.
          </li>
        </ul>
      </article>

    </div>
  </section>

  <section class="section">
    <div class="case-layout">

      <article class="case-card">
        <h2>Lab Troubleshooting Note</h2>
        <p>
          The original Microsoft Graph PowerShell cmdlet approach ran into module loading issues in Azure Cloud Shell. To complete the project cleanly, a REST-based Microsoft Graph PowerShell script was created using Invoke-RestMethod and an Azure Cloud Shell access token.
        </p>

        <p>
          This demonstrates practical troubleshooting and an alternate automation method when module dependencies cause issues.
        </p>
      </article>

      <article class="case-card">
        <h2>Why the REST Approach Matters</h2>

        <ul class="case-list">
          <li>Shows the ability to work around module or dependency issues.</li>
          <li>Uses direct Microsoft Graph API calls instead of relying only on cmdlets.</li>
          <li>Demonstrates practical PowerShell troubleshooting.</li>
          <li>Creates a repeatable approach for exporting IAM data.</li>
          <li>Maps directly to real IAM reporting and audit support tasks.</li>
        </ul>
      </article>

    </div>
  </section>

  <section class="section">
    <div class="case-layout">

      <article class="case-card">
        <h2>Documentation Summary</h2>

        <ul class="case-list">
          <li>
            <strong>IAM Reporting:</strong> Helps security and IT teams understand users, groups, and access assignments.
          </li>
          <li>
            <strong>Audit Evidence:</strong> CSV reports and screenshots can support access reviews, audits, and compliance checks.
          </li>
          <li>
            <strong>Group Membership Review:</strong> Exporting group membership helps IAM teams validate whether users still need assigned access.
          </li>
          <li>
            <strong>Automation:</strong> PowerShell automation reduces manual work and makes IAM reporting more repeatable.
          </li>
          <li>
            <strong>Microsoft Graph:</strong> Graph can be used to query Microsoft Entra ID user, group, and membership data for reporting.
          </li>
        </ul>
      </article>

      <aside class="case-card">
        <h2>Skills Demonstrated</h2>

        <div class="badge-row">
          <span class="badge">Microsoft Graph</span>
          <span class="badge">PowerShell</span>
          <span class="badge">REST API</span>
          <span class="badge">IAM Reporting Automation</span>
          <span class="badge">CSV Reporting</span>
          <span class="badge">Group Membership Review</span>
          <span class="badge">Audit Evidence Collection</span>
          <span class="badge">Troubleshooting</span>
        </div>
      </aside>

    </div>
  </section>

  <section class="section">
    <div class="case-card">
      <h2>Resume Bullet</h2>

      <div class="resume-bullet">
        Built a Microsoft Graph IAM reporting automation project using PowerShell and REST API calls to export Microsoft Entra ID users, groups, group memberships, and audit evidence reports for access review support.
      </div>
    </div>
  </section>

  <section class="section">
    <div class="skill-panel">
      <h2 class="section-title">Recruiter Takeaway</h2>
      <p class="section-subtitle">
        This project shows that I can support IAM operations with reporting automation, not just manual portal work. It demonstrates Microsoft Graph, PowerShell, REST API usage, CSV reporting, group membership review, audit evidence collection, and troubleshooting when the first technical approach does not work.
      </p>

      <div class="cta-row">
        <a class="btn btn-primary" href="../projects.html">Back to Projects</a>
        <a class="btn btn-secondary" href="../resume.html">View Resume</a>
        <a class="btn btn-secondary" href="../contact.html">Contact Me</a>
      </div>
    </div>
  </section>

</main>

<footer class="footer">
  <div class="container">
    <p>© 2026 Nicholas Tjhung · IAM Portfolio</p>
  </div>
</footer>

</body>
</html>
