# AIStyleShop

# AI-Based Fashion Recommendation System

## Description
This project is a fashion recommendation platform that leverages user feedback and AI-based sentiment analysis using **TextBlob**.  
Based on user reviews, products are rated as **positive**, **negative**, or **neutral**.  
The most popular products are highlighted, and users receive **personalized product recommendations** according to their reviews.  

It features a **minimalist and modern design** suitable for fashion-related platforms.

---
## Project Name
smartshopping

## Features
- Sentiment analysis of user reviews (positive, negative, neutral) using **TextBlob**.
- Product rating based on user feedback.
- Popular products ranking.
- Personalized product recommendations for each user.
- Minimal and clean UI design.

---

## Tech Stack
- **Backend**: Django  
- **Database**: PostgreSQL  
- **AI**: TextBlob for sentiment analysis  

---

## Installation

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd <your-repo-folder>
  

2. Create and activate a virtual environment:

   ```bash
    python -m venv smartshopping_env
    source smartshopping_env/bin/activate   # On Mac/Linux
    smartshopping_env\Scripts\activate      # On Windows
 
3. Clone the repository:
   
   ```bash
    pip install -r requirements.txt

4. Apply database migrations:
   ```bash
   python manage.py migrate


5. Create a superuser (admin panel access):
   ```bash
   python manage.py createsuperuser


6. Run the development server:
   ```bash
   python manage.py runserver

7. Open the app in your browser:
   ```bash
    http://127.0.0.1:8000/

## Usage
- Users can sign up and log in.
- Users can leave reviews for products.
- AI calculates product ratings based on reviews.
- Users receive product recommendations based on their review history.
