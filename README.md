# 📚 University of YouTube
A dynamic learning platform that allows users to search for educational videos on topics like Data Analysis, Cloud Computing, Artificial Intelligence, and more.
🔗 Live Demo: University of YouTube

✨ Features

  ▫ 🔍 Search Videos: Enter any keyword and view the top 5 related YouTube videos.

  ▫ ➕ Load More: Easily load more videos in batches of 5.

  ▫ 💡 Trending Topics: Quick suggestions for trending learning topics like AI, Cloud, and DevOps.

  ▫ 🎨 Modern UI: Clean, responsive, and interactive user interface.

                                        ____________________________________________________________
## 🛠️ Tech Stack

  ▫ Frontend: React.js

  ▫ API: YouTube Data API v3

  ▫ Styling: CSS (Flexbox, Gradients, Hover Effects)
Deployment: Netlify

                                        ____________________________________________________________

## 🚀 Getting Started

1. Clone the Repository
bash

git clone https://github.com/your-username/university-of-youtube.git
cd university-of-youtube

2. Install Dependencies
bash

npm install

3. Configure YouTube API Key

  ▫ Create a file src/api/youtube.js

  ▫ Add your YouTube API key:
  
javascript

import axios from 'axios';

const KEY = 'YOUR_YOUTUBE_API_KEY';

export default axios.create({
  baseURL: 'https://www.googleapis.com/youtube/v3',
  params: {
    part: 'snippet',
    maxResults: 5,
    key: KEY,
  },
});


4. Start the Project
bash
npm start

Open http://localhost:3000 to view it in your browser.

                                        ____________________________________________________________

🌐 Live Deployment
The project is live and deployed on Netlify:
🔗 University of YouTube

                                        ____________________________________________________________

📸 Screenshots
1. Search and Suggestions:
Explore trending topics and search for learning videos.

2. Video Results:
Videos are displayed with thumbnails, titles, and smooth hover effects.

## 💡 Future Enhancements

  ▫ 🎯 Add category filters (e.g., tutorials, webinars)

  ▫ 🌙 Dark/Light mode toggle

  ▫ 📈 Video analytics (views, likes)

## 🤝 Contributing

  ▫ Fork the repository.

  ▫ Create a feature branch (git checkout -b feature-name).

  ▫ Commit changes (git commit -m 'Add new feature').

  ▫ Push to the branch (git push origin feature-name).

  ▫ Open a Pull Request.

                                        ____________________________________________________________

## 📞 Contact
For feedback or queries, feel free to reach out!
Developer: Yash Sharma
🔗 LinkedIn | 📧 Email

                                        ____________________________________________________________

📄 License
This project is open-source and available under the MIT License.
