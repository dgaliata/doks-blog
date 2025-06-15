---
title: "About Me"
description: "Learn more about my background, experience, and passion for cybersecurity"
---

<div class="about-page">

<div class="hero-intro">

Hey there 👋 Thanks for visiting my site! My name is **David**. I'm a Security Engineering Director with over 15 years of experience in IT, with a strong background in network and systems consulting. I currently focus on cybersecurity and cloud engineering solutions, leading high-impact projects.

<div class="hero-pillars">
<div class="pillar">
<div class="pillar-icon">🛠</div>
<div class="pillar-text">Building</div>
</div>
<div class="pillar">
<div class="pillar-icon">🔒</div>
<div class="pillar-text">Secure</div>
</div>
<div class="pillar">
<div class="pillar-icon">🧗</div>
<div class="pillar-text">Resilient</div>
</div>
<div class="pillar">
<div class="pillar-icon">💡</div>
<div class="pillar-text">Solutions</div>
</div>
</div>

</div>

<div class="section-header">

## 🎓 Education
{.section-title}

</div>

<div class="education-grid">

<div class="education-card">
<div class="education-degree">Master of Science in Cybersecurity Management</div>
<div class="education-school">Central Washington University</div>
<div class="education-year">2024</div>
<div class="education-description">
MS-ITAM Cybersecurity program at CWU, focused on managing cybersecurity programs and policies, preparing me for leadership roles in the field.
</div>
</div>

<div class="education-card">
<div class="education-degree">Bachelor of Science in Information Technology</div>
<div class="education-school">Western Governors University</div>
<div class="education-year">2011</div>
<div class="education-description">
BS-IT program at WGU, focused on core IT principles, including networking, security, and systems administration, providing a solid foundation for my career.
</div>
</div>

</div>

<div class="section-header">

## 💼 Experience
{.section-title}

</div>

<div class="timeline-container">
<div class="timeline">

<div class="timeline-item">
<div class="timeline-dot"></div>
<div class="timeline-content">
<div class="timeline-date">
<i class="fas fa-calendar"></i>
December 2021 - Present
</div>
<div class="timeline-title">Director, Security Engineering</div>
<div class="timeline-company">Aquia</div>
<div class="timeline-description">
Director and Principal Security Engineer leading the design and implementation of security solutions for both enterprise clients and the US Government. Responsible for cloud security architecture, regulatory compliance, and ensuring adherence to security standards while enabling advanced technological capabilities.
</div>
</div>
</div>

<div class="timeline-item">
<div class="timeline-dot"></div>
<div class="timeline-content">
<div class="timeline-date">
<i class="fas fa-calendar"></i>
June 2021 - December 2021
</div>
<div class="timeline-title">Senior Enterprise Network and Systems Consultant</div>
<div class="timeline-company">Cobaltix</div>
<div class="timeline-description">
Senior IT Consultant responsible for implementing technological solutions to solve business problems for clients throughout the Bay Area, serving as technical lead and project manager.
</div>
</div>
</div>

<div class="timeline-item">
<div class="timeline-dot"></div>
<div class="timeline-content">
<div class="timeline-date">
<i class="fas fa-calendar"></i>
November 2017 - June 2021
</div>
<div class="timeline-title">Senior IT Systems Engineer</div>
<div class="timeline-company">Nims & Associates</div>
<div class="timeline-description">
Senior IT Consultant responsible for planning and executing successful IT deployments and fostering strong client relationships, developing and supporting technology needs for clients.
</div>
</div>
</div>

<div class="timeline-item">
<div class="timeline-dot"></div>
<div class="timeline-content">
<div class="timeline-date">
<i class="fas fa-calendar"></i>
April 2013 - November 2017
</div>
<div class="timeline-title">Senior Network Engineer</div>
<div class="timeline-company">KLH Consulting</div>
<div class="timeline-description">
Designed, implemented, analyzed, and maintained IT Infrastructure of internal and external customer environments, serving as principal IT Engineer for clients throughout the Bay Area.
</div>
</div>
</div>

<div class="timeline-item">
<div class="timeline-dot"></div>
<div class="timeline-content">
<div class="timeline-date">
<i class="fas fa-calendar"></i>
December 2010 - April 2013
</div>
<div class="timeline-title">Engineer</div>
<div class="timeline-company">Portola Systems</div>
<div class="timeline-description">
Served small and medium businesses in all facets of technology, designing and implementing Windows server environments and configuring various networking technologies.
</div>
</div>
</div>

<div class="timeline-item">
<div class="timeline-dot"></div>
<div class="timeline-content">
<div class="timeline-date">
<i class="fas fa-calendar"></i>
April 2009 - November 2010
</div>
<div class="timeline-title">Junior Systems Administrator</div>
<div class="timeline-company">Hansel Enterprises</div>
<div class="timeline-description">
Internal IT Department position supporting over 500 users in 7 different locations, responsible for helpdesk tickets, server support, and backup administration.
</div>
</div>
</div>

<div class="timeline-item">
<div class="timeline-dot"></div>
<div class="timeline-content">
<div class="timeline-date">
<i class="fas fa-calendar"></i>
September 2007 - April 2009
</div>
<div class="timeline-title">NOC Technician II</div>
<div class="timeline-company">Marketlive</div>
<div class="timeline-description">
Provided website and server support for 1200+ servers for a web development e-commerce company, maintaining site availability and handling client communications.
</div>
</div>
</div>

</div>
</div>

<div class="passion-section">
<div class="passion-title">✨ Passion</div>
<div class="passion-subtitle">Lifelong Learning & Beyond</div>
<div class="passion-content">
I am dedicated to lifelong learning and passionate about DevOps, cybersecurity, and cloud technologies. Beyond my technical interests, I enjoy spending time with my family, drinking tons of coffee, listening to music, and reading.
</div>

<div class="quote-section">
<div class="quote-text">
"I bring real-world skills, dedication, and a genuine love for creating impactful solutions."
</div>
<div class="quote-author">— David Galiata</div>
</div>
</div>

</div>

<script>
// Add scroll animations
const observerOptions = {
    threshold: 0.1,
    rootMargin: '0px 0px -50px 0px'
};

const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            entry.target.style.animationPlayState = 'running';
        }
    });
}, observerOptions);

document.querySelectorAll('.timeline-item').forEach(item => {
    observer.observe(item);
});
</script>
