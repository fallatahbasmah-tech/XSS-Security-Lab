
# XSS Security Lab 🔐

## Project Overview

This repository documents my hands-on learning experience in web application security using PortSwigger Web Security Academy.

As a cybersecurity student, I am exploring common web vulnerabilities and learning how to identify, understand, and prevent security risks.

## Lab Information

**Platform:** PortSwigger Web Security Academy

**Lab Name:** Reflected XSS into HTML context with nothing encoded

**Difficulty:** Apprentice

**Vulnerability:** Reflected Cross-Site Scripting (XSS)

**Status:** Successfully Solved ✅

## Objective

The objective of this lab was to identify a reflected XSS vulnerability in a web application's search functionality and demonstrate JavaScript execution using the `alert()` function in a controlled training environment.

## Practical Implementation

### Step 1: Accessing the Lab
I accessed the "Reflected XSS into HTML context with nothing encoded" lab on PortSwigger Web Security Academy.

### Step 2: Testing the Search Functionality
I entered a test string into the search field and observed that the application displayed my input in the search results.

### Step 3: Testing JavaScript Execution
I entered the following JavaScript payload into the search field:

```html
<script>alert('Hello Basmah')</script>
```

### Step 4: Observing the Results
The browser executed the JavaScript code and displayed an alert message saying "Hello Basmah".

The lab status changed to **Solved**, confirming that I successfully completed the exercise.

## What I Learned

- How reflected XSS vulnerabilities occur.
- How user input can be reflected in a web application's response.
- How JavaScript can execute when user input is not properly encoded.
- The importance of validating and safely handling user input.

## Security Recommendations

To help prevent reflected XSS vulnerabilities, developers should:

- Apply context-aware output encoding.
- Avoid inserting untrusted input directly into HTML.
- Use safe DOM APIs when displaying user-generated content.
- Implement Content Security Policy (CSP) as an additional layer of protection.

## Disclaimer

This project was completed in a legal, controlled educational environment provided by PortSwigger Web Security Academy.

## Lab Completion Screenshot 🏆

![XSS Lab Successfully Solved](Screenshot%202026-11-17%20193456.png)
