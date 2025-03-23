AI-Powered Travel Planner🚀 OverviewThe AI-Powered Travel Planner is a Streamlit-based web application that provides travel options between two locations. Using Google Generative AI (Gemini), it suggests different modes of transport, estimated costs, travel duration, and useful travel tips.
🛠 FeaturesAccepts source and destination locations as input.
Uses Google GenAI (Gemini) to suggest travel options.
Provides recommendations for cab, train, bus, and flights.
Displays estimated cost, duration, and travel tips.
Built with Streamlit for an interactive web UI.
📌 InstallationTo run this project, ensure you have Python 3.8+ installed. Then, install the required dependencies:
🔑 Setting Up API KeyYou need a Google GenAI API Key to use this application.
Get your API key from Google AI Studio (https://ai.google.dev/).
Set your API key in an environment variable:
Windows (Command Prompt):
Mac/Linux:
Alternatively, you can hardcode the key in travel_planner.py:
▶️ Running the ApplicationOnce installed, navigate to the project folder and run:
This will open the app in your browser at http://localhost:8501.
📂 Project Structure✨ UsageEnter the Source Location (e.g., New York)
Enter the Destination Location (e.g., Los Angeles)
Click "Find Travel Options"
View AI-generated travel recommendations
📌 DependenciesLangChain (langchain-google-genai, langchain_core)
Streamlit (for the UI)
Google GenAI API (Gemini)
📜 LicenseThis project is open-source and free to use under the MIT License.
💡 Future EnhancementsAdd real-time price & availability using travel APIs.
Support for hotel recommendations.
Integration with Google Maps for route visualization.
Feel free to contribute or suggest improvements! 🚀

