Slide Generator Web App
Transform your formatted notes into professional PowerPoint presentations with this easy-to-use web application.

🚀 Quick Start with GitHub Codespaces
Click the green "Code" button above
Select "Codespaces" tab
Click "Create codespace on main"
Wait for setup (about 1-2 minutes)
Run the app:
bash
python app.py
Open the forwarded port (Codespaces will show a popup)
📁 Expected File Format
Your input text file should follow this structure:

0. Title Slide
Slide Bullets:
- First bullet point
- Second bullet point
- Third bullet point

Speaker Notes:
Your detailed speaker notes go here...

1. Second Slide Title
Slide Bullets:
- More bullet points
- Additional content

Speaker Notes:
More detailed notes for this slide...
🎨 Features
Drag & Drop Interface - Easy file uploads
Multiple Themes - Professional Blue, Clean Gray, Medical Green
Speaker Notes Support - Automatically adds notes to slides
Real-time Processing - Live progress updates
Automatic Download - PowerPoint file downloads when ready
Mobile Responsive - Works on any device
🛠️ Local Development
If you want to run this locally:

bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/slide-generator-web.git
cd slide-generator-web

# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py
Then open your browser to http://localhost:5000

📖 Usage Instructions
Upload your text file using the drag & drop area or file selector
Choose a theme from the dropdown menu
Click "Generate Slides" to create your presentation
Download the PowerPoint file automatically
🔧 Technical Details
Built with Flask (Python web framework)
Uses python-pptx for PowerPoint generation
Responsive HTML/CSS/JavaScript frontend
Runs in GitHub Codespaces or any Python environment
📝 License
This project is open source and available under the MIT License.

🤝 Contributing
Feel free to submit issues and pull requests to improve this tool!

Note: This app is designed for educational and professional use. Make sure your text files follow the expected format for best results.

