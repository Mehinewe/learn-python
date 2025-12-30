# Exercices

## 🧾 1: Clean Customer Emails (Data Cleaning – Real Company Task)

### Scenario:
You receive customer emails from a signup form. The data is messy and needs cleaning before analysis.

### Given data:
emails = [
    "  Alice@gmail.com ",
    "BOB@Yahoo.COM",
    "carol123@hotmail.com ",
    "   david@outlook.com",
    "eva@@gmail.com"
]

### Tasks:
* Remove extra spaces
* Convert all emails to lowercase
* Identify invalid emails: (must contain exactly one @, must end with .com)

### Expected skills used:
* strip()
* lower()
* count()
* endswith()
* find()
* Bonus (optional):
Create two lists:
valid_emails
invalid_emails

💼 Real world: This is what happens before marketing campaigns or CRM imports.  

## 🛒 2: Analyze Product Reviews (Text Search & Transformation)

### Scenario:
You work for an e-commerce company and need to flag negative reviews.

### Given data:
reviews = [
    "This product is AMAZING",
    "very bad quality",
    "I love it",
    "Bad experience, waste of money",
    "excellent service",
    "BAD packaging"
]

### Tasks:
* Convert all reviews to lowercase
* Identify reviews containing the word "bad"
* Count how many negative reviews there are
* Extract the first 10 characters of each negative review

### Expected skills used:
* lower()
* 'word' in text
* count()
* slicing [0:10]

💼 Real world: Basic sentiment analysis before dashboards or ML models.  

## 📊 3: Clean Campaign Names for a Marketing Report

### Scenario:
Marketing campaign names are inconsistent. You must standardize them before analysis.

### Given data:
campaigns = [
    " Email_Summer ",
    "email-winter",
    "EMAIL spring",
    " Social Media ",
    "social_media"
]

### Tasks:
* Remove extra spaces
* Convert to lowercase
* Replace spaces and dashes (-) with underscores (_)
* Count how many times "email" campaigns appear

### Expected skills used:
* strip()
* lower()
* replace()
* count()
* 
💼 Real world: This is exactly what analysts do before SQL joins and dashboards.
