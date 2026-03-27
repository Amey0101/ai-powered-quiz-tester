# ai-powered-quiz-tester
Smart MCQ Practice Tool 🧠
A dynamic, feature-rich web application designed for students and educators to practice, edit, and master Multiple Choice Questions (MCQs). Built with a focus on active recall and continuous improvement, this tool features an integrated "Hardcore Practice" mode and AI search capabilities to deeply understand difficult questions.
✨ Key Features
 * 📁 Local JSON Upload: Load your own question banks instantly without needing a server.
 * 🔥 Hardcore Practice Mode: Wrong answers are automatically sent to "Hardcore" mode. To remove a question from Hardcore, you must answer it correctly 6 times in a row, building true mastery through spaced repetition.
 * 🤖 AI Search Integration: Instantly search a question and its options using top AI engines (Perplexity, Phind, You.com, Google, Bing Copilot, Genspark) with a single click.
 * ✏️ In-App Editing: Spot a mistake? Edit questions, options, and correct answers directly in the UI.
 * 💾 Export Updated MCQs: Download your edited and corrected question bank back into a fresh JSON file.
 * 📊 Detailed Analytics: Post-submission tabs for Correct, Wrong, and Unsolved questions with progress tracking.
 * 🌙 Dark Mode UI: Eye-friendly interface built with Tailwind CSS.
🚀 How to Use
 * Clone the repository:
   git clone https://github.com/yourusername/your-repo-name.git
 * Open the App: Double-click the MCQ_test.html file to open it in any modern browser.
 * Upload Questions: Click on "Choose File" and upload a properly formatted .json file (see the format below).
 * Practice: * Choose "रँडम प्रश्न" (Random 10 Questions) or "सर्व प्रश्न" (All Questions).
   * Submit your quiz to see the results.
   * Check the "Practice Hardcore" tab to master the questions you got wrong.
📄 Required JSON Format
Your question bank must be an array of objects. Each object must contain question, options (an array of strings), and correct_answer (a string that exactly matches one of the options).
[
{
"question": "महाराष्ट्राची राजधानी कोणती आहे?",
"options": ["पुणे", "मुंबई", "नागपूर", "नाशिक"],
"correct_answer": "मुंबई"
}
]
🛠️ Tech Stack
 * HTML5 / CSS3 / JavaScript (Vanilla)
 * Tailwind CSS (via CDN for styling)
 * FontAwesome (via CDN for icons)
 * Local Storage (for tracking Hardcore mode progress)
🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.
📝 License
This project is open-source and available under the MIT License.
