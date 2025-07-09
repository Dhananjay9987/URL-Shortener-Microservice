# URL Shortener Microservice

A lightweight microservice that converts long URLs into short, redirectable links using Base62 encoding. Built with Flask and SQLite, this tool is ideal for quick deployments and local usage.

# Features

1. Converts long URLs to short Base62-encoded links
2. Form-based user interface
3. Stores URL mappings using SQLite
4. Redirects shortened URLs to original targets
5. All-in-one Python file (easy to deploy)

# Technologies Used

1. Python 3.12
2. Flask – Web framework
3. SQLite – Lightweight database
4. Base62 – Encoding for short links

# File Structure

URLShortener.py     # Main Flask app with encoding, redirect, and DB logic  
urls.db             # SQLite database to persist URL mappings

# How to Run

1. Install dependencies: pip install flask
2. Start the server: python URLShortener.py
3. Visit in browser: http://localhost:5000/

# Future Enhancements
1. Admin dashboard to manage all links
2. Click analytics and expiration settings
3. Support for custom short aliases
4. Cloud deployment with SSL + custom domain
