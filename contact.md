:root {
  --text: #393939;
  --muted: #666f68;
  --green-dark: #2f5f3f;
  --green: #3f7d55;
  --green-mid: #5f9a70;
  --green-soft: #edf6ef;
  --green-pale: #f7fbf8;
  --green-border: #c9decf;
  --paper: #ffffff;
  --line: #dbe6de;
}

* {
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {
  margin: 0;
  padding: 0;
  font: 14px/1.5 "Poppins", "Helvetica Neue", Arial, sans-serif;
  color: var(--text);
  background:
    linear-gradient(180deg, var(--green-pale) 0, #fff 260px)
    fixed;
}

.site-shell {
  max-width: 980px;
  margin: 0 auto;
  padding: 36px 24px 30px;
}

.site-header {
  display: flex;
  align-items: flex-end;
  justify-content: space-between;
  gap: 24px;
  margin-bottom: 34px;
  padding-bottom: 18px;
  border-bottom: 1px solid var(--line);
}

.site-title {
  color: var(--green-dark);
  font-size: 28px;
  font-weight: 700;
  letter-spacing: -0.02em;
  text-decoration: none;
}

.site-title:hover {
  color: var(--green);
}

.site-subtitle {
  margin-top: 4px;
  color: var(--muted);
  font-size: 13px;
}

.site-nav {
  display: flex;
  flex-wrap: wrap;
  justify-content: flex-end;
  gap: 7px;
}

.site-nav a {
  display: inline-block;
  padding: 7px 11px;
  border-radius: 999px;
  color: var(--green-dark);
  text-decoration: none;
  font-weight: 500;
}

.site-nav a:hover,
.site-nav a.active {
  color: var(--green-dark);
  background: var(--green-soft);
}

.content {
  background: var(--paper);
}

.hero {
  padding: 28px 30px;
  border: 1px solid var(--green-border);
  border-radius: 16px;
  background: linear-gradient(135deg, #ffffff 0%, var(--green-soft) 100%);
  margin-bottom: 28px;
}

.hero h1 {
  margin: 0 0 8px;
  color: var(--green-dark);
  font-size: 32px;
  line-height: 1.15;
  letter-spacing: -0.03em;
}

.lead {
  margin: 0;
  max-width: 760px;
  color: #425148;
  font-size: 16px;
}

.page-section {
  margin: 28px 0;
}

.page-section:first-child {
  margin-top: 0;
}

.section-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 18px;
}

.card {
  border: 1px solid var(--line);
  border-radius: 12px;
  padding: 18px 20px;
  background: #fff;
}

.card h3 {
  margin-top: 0;
}

h1,
h2,
h3 {
  color: var(--green-dark);
}

h1 {
  font-size: 30px;
  margin: 0 0 18px;
  line-height: 1.2;
}

h2 {
  font-size: 22px;
  margin: 0 0 12px;
  padding-bottom: 6px;
  border-bottom: 1px solid var(--line);
}

h3 {
  font-size: 17px;
  margin: 18px 0 8px;
}

p {
  margin: 0 0 13px;
}

ul,
ol {
  margin-top: 8px;
  padding-left: 24px;
}

li {
  margin: 5px 0;
}

a {
  color: var(--green);
  text-decoration: none;
}

a:hover {
  color: var(--green-dark);
  text-decoration: underline;
}

strong {
  font-weight: 600;
}

.meta {
  color: var(--muted);
  font-size: 13px;
}

.list-plain {
  padding-left: 0;
  list-style: none;
}

.list-plain li {
  padding: 9px 0;
  border-bottom: 1px solid var(--line);
}

.list-plain li:last-child {
  border-bottom: 0;
}

.contact-table {
  width: 100%;
  border-collapse: collapse;
  margin-top: 8px;
}

.contact-table th,
.contact-table td {
  vertical-align: top;
  padding: 10px 0;
  border-bottom: 1px solid var(--line);
}

.contact-table th {
  width: 145px;
  color: var(--green-dark);
  text-align: left;
  font-weight: 600;
}

.notice {
  padding: 14px 16px;
  border-left: 4px solid var(--green-mid);
  background: var(--green-soft);
  border-radius: 8px;
}

.site-footer {
  display: flex;
  justify-content: space-between;
  gap: 20px;
  margin-top: 44px;
  padding-top: 16px;
  border-top: 1px solid var(--line);
  color: var(--muted);
  font-size: 12px;
}

.footer-note {
  text-align: right;
}

@media (max-width: 760px) {
  .site-shell {
    padding: 24px 17px 26px;
  }

  .site-header {
    display: block;
  }

  .site-nav {
    justify-content: flex-start;
    margin-top: 16px;
  }

  .hero {
    padding: 22px 20px;
  }

  .hero h1 {
    font-size: 28px;
  }

  .lead {
    font-size: 15px;
  }

  .section-grid {
    grid-template-columns: 1fr;
  }

  .site-footer {
    display: block;
  }

  .footer-note {
    margin-top: 5px;
    text-align: left;
  }

  .contact-table th,
  .contact-table td {
    display: block;
    width: 100%;
    padding: 6px 0;
    border-bottom: 0;
  }

  .contact-table tr {
    display: block;
    padding: 8px 0;
    border-bottom: 1px solid var(--line);
  }
}
