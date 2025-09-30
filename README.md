# OpenTubeDL
   ____                  _______        __        ____  __    
  / __ \____  ___  _____/ ____(_)___   / /_____ _/ / /_/ /____
 / / / / __ \/ _ \/ ___/ /_  / / __ \ / __/ __ `/ / __/ __/ _ \
/ /_/ / /_/ /  __/ /  / __/ / / / / // /_/ /_/ / / /_/ /_/  __/
/_____/\____/\___/_/  /_/   /_/_/ /_/ \__/\__,_/_/\__/\__/\___/ 


**OpenTubeDL** is a lightweight and user-friendly **YouTube Video Downloader** built with **Flask (Python)** for the backend and **HTML/JavaScript** for the frontend.  

It lets you paste a YouTube link, fetch the video in the **highest quality**, and download it with a single click.  

---

## ✨ Features
- 🎥 Download YouTube videos in the **highest available resolution**.  
- ⚡ Fast and simple **web interface**.  
- 🖥️ Backend powered by **Flask**.  
- 🌐 Frontend built with **HTML + JavaScript (fetch API)**.  
- 📂 Videos stored locally in a `downloads/` folder with unique filenames.  

---

## 📂 Project Structure
.
├── app.py # Flask backend server
├── index.html # Frontend user interface
├── downloads/ # Folder where downloaded videos are saved


---

## 🔧 Requirements
- Python **3.7+**  
- [pip](https://pip.pypa.io/en/stable/)  

Install dependencies:
```bash
pip install flask pytube

⚠️ Note: If pytube fails due to YouTube changes, you can swap it out with yt-dlp (more reliable).


🚀 Getting Started
1.Clone the repository
git clone https://github.com/yourusername/OpenTubeDL.git
cd OpenTubeDL

2.Install dependencies
pip install flask pytube

3.Start the Flask server
python app.py

By default, it runs on:
👉 http://localhost:5000

4.Open the frontend
Open index.html in your browser.
Paste a YouTube URL.
Click Download to get your video.
