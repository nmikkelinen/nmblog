---
layout: default
title: "CV | Nicklas Mikkelinen"
---

<style>
body {
    max-width: 1000px !important;
}
.cv-container {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    max-width: 100%;
    margin: 0 auto;
}
.cv-header {
    display: flex;
    align-items: center;
    gap: 30px;
    margin-bottom: 40px;
}
.cv-photo {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    object-fit: cover;
    border: 2px solid currentColor;
}
.cv-title h1 {
    margin: 0;
    font-size: 2.4rem;
    line-height: 1.1;
    letter-spacing: -0.02em;
}
.cv-section {
    margin-bottom: 35px;
}
.cv-section h2 {
    border-bottom: 1px solid rgba(255, 255, 255, 0.1);
    padding-bottom: 6px;
    margin-bottom: 15px;
    text-transform: uppercase;
    font-size: 1rem;
    letter-spacing: 0.05em;
}
.contact-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 10px 32px;
    font-size: 14px;
    margin-bottom: 30px;
}
.job-block, .edu-block {
    margin-bottom: 25px;
    padding-bottom: 20px;
    border-bottom: 1px solid rgba(255, 255, 255, 0.05);
}
.job-block:last-child, .edu-block:last-child {
    border-bottom: none;
}
.job-header, .edu-header {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    margin-bottom: 5px;
}
.job-title, .edu-title {
    font-weight: 600;
    font-size: 1.1rem;
    margin: 0;
}
.job-date, .edu-date {
    font-size: 14px;
    color: #64748b;
    font-weight: 500;
}
.skill-category {
    margin-bottom: 15px;
}
a.cv-accent {
    text-decoration: none !important;
    pointer-events: none;
    cursor: default;
    font-weight: 600;
}
.contact-grid a {
    color: inherit;
    text-decoration: none;
}
.contact-grid a:hover {
    text-decoration: underline;
}
@media print {
    body {
        background: #ffffff !important;
        color: #1e293b !important;
        font-size: 12pt !important;
        max-width: 100% !important;
        margin: 0 !important;
        padding: 1.5cm !important;
    }
    header, footer, hr, script, button, .cv-selectors, div[style*="margin-bottom"] {
        display: none !important;
    }
    .cv-container {
        max-width: 100% !important;
    }
    .cv-section h2 {
        border-bottom: 1px solid #cbd5e1 !important;
        color: #0f172a !important;
    }
    .job-title, .edu-title {
        color: #0f172a !important;
    }
    .job-block {
        page-break-inside: avoid;
        border-bottom: 1px solid #e2e8f0 !important;
    }
    a.cv-accent, .skill-category strong, .contact-grid a {
        color: #475569 !important;
    }
    .job-date, .edu-date {
        color: #64748b !important;
    }
}
</style>

<div class="cv-container">

    <div class="cv-header">
        <img src="/assets/images/portraitbw.jpg" alt="Nicklas Mikkelinen" class="cv-photo">
        <div class="cv-title">
            <h1>NICKLAS<br>MIKKELINEN</h1>
            <p><a class="cv-accent">Curriculum Vitae</a></p>
        </div>
    </div>

    <div class="contact-grid">
        <div>• 21/11/1986</div>
        <div>• +46-735-746-082</div>
        <div>• <a href="mailto:nicklas@mikkelinen.se">nicklas@mikkelinen.se</a></div>
        <div>• Boden, Sweden</div>
        <div>• <a href="https://linkedin.com/in/mikkelinen" target="_blank">LinkedIn</a></div>
    </div>

    <div class="cv-section">
        <h2>Professional Profile</h2>
        <p>Senior security leader with a background in global industry and critical infrastructure. Currently leading cybersecurity and CSL (NIS2) alignment at Gestamp Hardtech, with a focus on transitioning complex OT environments from reactive maintenance to proactive resilience.</p>
        <p>Extensive experience with the Swedish Protective Security Act and a specialist in GRC, ensuring that compliance acts as a business enabler. My leadership is built with focus on the individual, developing high-performance teams and modernizing security culture to enable a secure-by-design infrastructure.</p>
    </div>

    <div class="cv-section">
        <h2>Strategic Skills</h2>
        <div class="skill-category">
            <strong><a class="cv-accent">Security & Risk Management:</a></strong> Information Security, Protective Security (Säkerhetsskydd), Risk Management
        </div>
        <div class="skill-category">
            <strong><a class="cv-accent">Frameworks & Compliance:</a></strong> GRC, NIS2/CSL, ISO 27001, NIST, GDPR, DORA
        </div>
        <div class="skill-category">
            <strong><a class="cv-accent">Infrastructure:</a></strong> IT/OT Security, Infrastructure Resilience, Industrial Cybersecurity
        </div>
        <div class="skill-category">
            <strong><a class="cv-accent">Leadership & Governance:</a></strong> Executive Reporting, Steering Committees, Change Management, Security Strategy, Crisis Management, Authority Collaboration
        </div>
    </div>

    <div class="cv-section">
        <h2>Work Experience</h2>

        <div class="job-block">
            <div class="job-header">
                <div>
                    <h3 class="job-title">CIO & CSO</h3>
                    <div class="job-company"><a class="cv-accent">Gestamp Hardtech AB</a></div>
                </div>
                <div class="job-date">2025-TODAY</div>
            </div>
            <ul>
                <li>Member of the Executive Management Team at Gestamp Hardtech Sweden, providing strategic direction for security and IT.</li>
                <li>Regional CSO and CIO responsibility with primary focus on information security governance and physical security.</li>
                <li>Leading regional CSL (NIS2) alignment and implementing cybersecurity frameworks within Sweden.</li>
                <li>Managing the security transition of complex OT systems, shifting reactive maintenance to proactive resilience.</li>
                <li>Ensuring regulatory compliance and risk mitigation in a global industrial context, reporting directly to the Managing Director.</li>
                <li>Coordinating security operations, incident response and change management during an organizational divestment.</li>
            </ul>
        </div>

        <div class="job-block">
            <div class="job-header">
                <div>
                    <h3 class="job-title">Information Security Manager</h3>
                    <div class="job-company"><a class="cv-accent">Swedbank AB</a></div>
                </div>
                <div class="job-date">2023-2025</div>
            </div>
            <ul>
                <li>Information Security Manager (ISM) for Group Risk, Legal, Internal Audit and Compliance.</li>
                <li>Strategic security advisor for control functions, serving as a functional extension of the Group CISO.</li>
                <li>Delivered security governance and strategic risk reports to senior leadership within the business areas.</li>
                <li>Ensured regulatory alignment across complex stakeholder landscapes in a highly regulated financial environment.</li>
                <li>Facilitated security training and improved security awareness across specialized professional groups.</li>
            </ul>
        </div>

        <div class="job-block">
            <div class="job-header">
                <div>
                    <h3 class="job-title">CISO & Deputy Head of Protective Security</h3>
                    <div class="job-company"><a class="cv-accent">Luleå Municipality</a></div>
                </div>
                <div class="job-date">2021-2023</div>
            </div>
            <ul>
                <li>Chief Information Security Officer (CISO) and Deputy Head of Protective Security (Biträdande säkerhetsskyddschef).</li>
                <li>Full accountability for ISMS implementation and security strategy across all municipal departments.</li>
                <li>Managed security frameworks for essential services governed by the Swedish Protective Security Act.</li>
                <li>Coordinated regional civil preparedness and authority collaboration with Säkerhetspolisen and MSB.</li>
                <li>Responsible for security clearance processes and protective security analysis for critical infrastructure.</li>
                <li>Provided strategic advice and risk reporting to the municipal leadership on national security matters.</li>
            </ul>
        </div>

        <div class="job-block">
            <div class="job-header">
                <div>
                    <h3 class="job-title">Security Ambassador</h3>
                    <div class="job-company"><a class="cv-accent">Facebook (Meta)</a></div>
                </div>
                <div class="job-date">2020-2021</div>
            </div>
            <ul>
                <li>Led the global Enterprise Engineering privacy and policies pod, focusing on policy deployment.</li>
                <li>Cross-functional coordination with information security partners to expand global guidelines.</li>
            </ul>
        </div>

        <div class="job-block">
            <div class="job-header">
                <div>
                    <h3 class="job-title">Technical Principal</h3>
                    <div class="job-company"><a class="cv-accent">Facebook (Meta)</a></div>
                </div>
                <div class="job-date">2017-2021</div>
            </div>
            <ul>
                <li>Managed IT infrastructure deployment and administration for EMEA datacenters and new offices.</li>
                <li>Orchestrated logistics and fulfillment for end-user IT equipment and video conferencing systems.</li>
            </ul>
        </div>

        <div class="job-block">
            <div class="job-header">
                <div>
                    <h3 class="job-title">IT Field Technician</h3>
                    <div class="job-company"><a class="cv-accent">Milestone Technologies, Inc.</a></div>
                </div>
                <div class="job-date">2016-2017</div>
            </div>
            <ul>
                <li>Worked as an IT Field technician, coordinating and maintaining the IT of Facebook datacenter in Luleå.</li>
            </ul>
        </div>

        <div class="job-block">
            <div class="job-header">
                <div>
                    <h3 class="job-title">Supervisor (Teaching Assistant)</h3>
                    <div class="job-company"><a class="cv-accent">The University of Skövde</a></div>
                </div>
                <div class="job-date">2014-2015</div>
            </div>
            <ul>
                <li>Teaching assistance and lab supervision in computer science and information security courses.</li>
            </ul>
        </div>

        <div class="job-block">
            <div class="job-header">
                <div>
                    <h3 class="job-title">IT Consultant</h3>
                    <div class="job-company"><a class="cv-accent">Fanboys AB</a></div>
                </div>
                <div class="job-date">2011-2012</div>
            </div>
            <ul>
                <li>IT consulting role focused on system administration, client support and infrastructure maintenance.</li>
            </ul>
        </div>

        <div class="job-block">
            <div class="job-header">
                <div>
                    <h3 class="job-title">Technical Support</h3>
                    <div class="job-company"><a class="cv-accent">Teleperformance Nordic</a></div>
                </div>
                <div class="job-date">2008-2010</div>
            </div>
            <ul>
                <li>Early-career role in technical support, customer service and quality assurance.</li>
            </ul>
        </div>
    </div>

    <div class="cv-section">
        <h2>Education</h2>

        <div class="edu-block">
            <div class="edu-header">
                <div>
                    <h3 class="edu-title">Information Security</h3>
                    <div class="edu-school"><a class="cv-accent">Luleå University of Technology</a></div>
                </div>
                <div class="edu-date">2015-2016</div>
            </div>
            <p style="margin: 5px 0 0 0; font-size: 15px; color: #64748b;">MSc. level • Subsidiary subject: Information Security • In-depth study: IT Security</p>
        </div>

        <div class="edu-block">
            <div class="edu-header">
                <div>
                    <h3 class="edu-title">Network and Systems administration</h3>
                    <div class="edu-school"><a class="cv-accent">University of Skövde</a></div>
                </div>
                <div class="edu-date">2012-2015</div>
            </div>
            <p style="margin: 5px 0 0 0; font-size: 15px; color: #64748b;">Degree: BSc. in Computer Science • Subsidiary subject: Information Security • In-depth study: Computer Science</p>
        </div>
    </div>

    <div class="cv-section">
        <h2>Languages</h2>
        <p>Swedish (Mothertongue) • English (Fluent) • Norwegian (Conversational)</p>
    </div>

</div>
