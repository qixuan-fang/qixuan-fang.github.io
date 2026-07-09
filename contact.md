---
layout: default
title: Contact
nav_key: contact
description: Contact Qixuan Fang
permalink: /contact/
---

<h1>Contact</h1>

<section class="page-section">
  <table class="contact-table">
    <tr>
      <th>Email</th>
      <td>
        <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a><br>
        <a href="mailto:{{ site.author.alt_email }}">{{ site.author.alt_email }}</a>
      </td>
    </tr>
    <tr>
      <th>Office</th>
      <td>{{ site.author.office }}</td>
    </tr>
    <tr>
      <th>Department</th>
      <td>{{ site.author.department }}, {{ site.author.affiliation }}</td>
    </tr>
    <tr>
      <th>Phone</th>
      <td>{{ site.author.phone }}</td>
    </tr>
    <tr>
      <th>Office hours</th>
      <td>{{ site.author.office_hours }}</td>
    </tr>
  </table>
</section>
