<style>
/* ------------------- GENERAL LINK COLOURS ------------------- */
.sidebar-nav a {
  color: #2a5db0 !important;
}
.sidebar-nav a:hover,
.sidebar-nav a:active {
  color: #1a73e8 !important;
}

/* ------------------- ZOHO DROPDOWN HEADER ------------------- */
details.sidebar-dropdown {
  padding-left: 16px;
  padding-right: 16px;
  margin-bottom: 12px; /* space between dropdowns */
}
details.sidebar-dropdown summary {
  display: flex;
  align-items: center; /* vertical align text & arrow */
  justify-content: center; /* center text horizontally */
  cursor: pointer;
  list-style: none;
  font-size: 1em;
  background-color: #f2f2f2; /* light grey background */
  padding: 6px 8px;
  border-radius: 4px;
  font-weight: bold;
  color: #333;
  transition: background-color 0.2s ease;
}
details.sidebar-dropdown summary:hover {
  background-color: #e0e0e0;
}
details.sidebar-dropdown summary::-webkit-details-marker {
  display: none;
}
/* Custom arrow */
details.sidebar-dropdown summary::after {
  content: "▼";
  font-size: 0.9em;
  position: relative;
  margin-left: 6px;
  transition: transform 0.2s ease;
}
details.sidebar-dropdown[open] summary::after {
  transform: rotate(180deg);
}

/* ------------------- LEVEL 2 HEADINGS ------------------- */
.sidebar-subteam {
  font-size: 0.95em;
  font-weight: bold;
  margin-top: 10px;
  margin-bottom: 4px;
  padding-left: 6px;
  border-left: 3px solid #000;
  color: #000;
}

/* ------------------- LEVEL 3 HEADINGS ------------------- */
.sidebar-subteam + ul > li > strong {
  font-size: 0.9em;
  font-weight: bold;
  color: #444;
  display: inline-block;
  margin-top: 6px;
  margin-bottom: 2px;
  padding-left: 12px;
}

.sidebar-subteam + ul > li > a > strong {
  font-size: 0.9em;
  font-weight: bold;
  color: #2a5db0;
  display: inline-block;
  margin-top: 6px;
  margin-bottom: 2px;
  padding-left: 12px;
}
.sidebar-subteam + ul > li > a > strong:hover {
  color: #1a73e8;
  text-decoration: underline;
}

/* ------------------- LINKS UNDER LEVEL 3 ------------------- */
.sidebar-subteam + ul ul li a {
  padding-left: 20px;
  font-size: 0.88em;
}
</style>

<details class="sidebar-dropdown" open>
  <summary><span class="sidebar-team">Website</span></summary>
</details>

<details class="sidebar-dropdown" open>
  <summary><span class="sidebar-team">Client Portal</span></summary>
    <ul>
      <li><a href="#/client-portal/troubleshooting-registration">Member Registration</a></li>
    </ul>
</details>

<details class="sidebar-dropdown" open>
  <summary><span class="sidebar-team">ZOHO</span></summary>

  <div class="sidebar-subteam">Zoho Links</div>
  <ul>
    <li><a href="https://one.zoho.com.au">Zoho One</a></li>
    <li><a href="https://crm.zoho.com.au">Zoho CRM</a></li>
    <li><a href="https://desk.zoho.com.au">Zoho Desk</a></li>
  </ul>

  <div class="sidebar-subteam">Employment Advisory Team</div>
  <ul>
    <li><strong>Ticket Management</strong>
      <ul>
        <li><a href="#/employment-advisory/ticket-management/creating-ticket">Creating a Ticket</a></li>
        <li><a href="#/employment-advisory/ticket-management/finding-ticket">Finding a Ticket</a></li>
        <li><a href="#/employment-advisory/ticket-management/merging-tickets">Merging Tickets</a></li>
      </ul>
    </li>
    <li><a href="#/employment-advisory/activity-time-entry/index"><strong>Activity & Time Entry</strong></a>
      <ul>
        <li><a href="#/employment-advisory/activity-time-entry/email-time-entry">Adding an Email Time Entry</a></li>
        <li><a href="#/employment-advisory/activity-time-entry/call-time-entry">Adding a Call Time Entry</a></li>
        <li><a href="#/employment-advisory/activity-time-entry/task-time-entry">Adding a Task Time Entry</a></li>
        <li><a href="#/employment-advisory/activity-time-entry/modifying-entry">Modifying a Time Entry</a></li>
      </ul>
    </li>
  </ul>

  <div class="sidebar-subteam">Membership Engagement Team</div>
  <ul>
    <li><a href="#/membership/new-member-onboarding-process">New Member Onboarding Process</a></li>
    <li><a href="#/membership/oauth-imap-setup">OAuth IMAP Setup</a></li>
    <li><a href="#/membership/setting-up-email-signature">Setting Up Email Signature</a></li>
    <li><a href="#/membership/manage-duplicate-contact">Manage Duplicate Contact</a></li>
    <li><a href="#/membership/ticket-contact-reassignment">Ticket Contact (Originator) Reassignment</a></li>
  </ul>
</details>
