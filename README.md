<img width="1878" height="896" alt="Screenshot 2025-11-25 153102" src="https://github.com/user-attachments/assets/22ce800a-9950-4940-8fb7-20d1718ca20b" />Image Search Engine

A simple and responsive web application that lets users search for images using the Unsplash API.
Users can type any keyword, view image results instantly, and load more images with a single click.


🚀 Features

🔍 Search images using keywords
🖼️ Fetch high-quality images from Unsplash API
📄 Show More button to load additional results
⚡ Fast and lightweight
🎨 Modern UI with smooth layout
📱 Fully responsive grid design


🛠️ Technologies Used

HTML5 – Structure
CSS3 – Layout and styling
JavaScript (ES6) – Logic, API interaction
Unsplash Developer API – Image source


📦 How It Works

User enters a search term (e.g., “mountains”, “cars”, “cats”, etc.)
JavaScript captures the input and sends a request to Unsplash:

https://api.unsplash.com/search/photos

Unsplash returns JSON results containing:

*Image URLs
*Photographer profile
*Links to full image pages

The script dynamically creates image elements and displays them on the page.
Clicking Show More loads the next page of results.


