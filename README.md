Address Proximity Finder

Overview

Address Proximity Finder is a simple web-based tool that helps users map and analyze addresses from a CSV file. It clusters nearby locations based on a mileage threshold and suggests optimized trips. This is ideal for planning travel routes across multiple locations efficiently.

Features

CSV File Upload: Supports full addresses or ZIP codes.

Google Maps Integration: Displays geocoded locations on an interactive map.

Custom Distance Threshold: Allows users to set a mileage limit for clustering addresses.

Trip Recommendations: Groups nearby locations and provides suggested travel routes.

Visual Enhancements: Includes progress tracking, clustered markers, and hover-based address tooltips.

How to Use

Upload a CSV file containing addresses or ZIP codes.

Click “Process Addresses” to map them.

Adjust the mileage threshold to define proximity.

Click “Recommend Trips” to generate optimized travel groups.

Hover over markers on the map to see address details.

Installation & Deployment

Running Locally (Using Python Server)

Clone the repository:

git clone https://github.com/YOUR_USERNAME/search-app.git
cd search-app

Start a local server:

python3 -m http.server 8000

Open http://localhost:8000 in your browser.

Deploying to GitHub Pages

Push your changes to GitHub:

git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/search-app.git
git push -u origin main

Enable GitHub Pages:

Go to Settings > Pages in your repository.

Set Branch to main and click Save.

Access your live app at https://YOUR_USERNAME.github.io/search-app/.

Dependencies

Google Maps API

PapaParse (CSV Parsing)

MarkerClusterer
