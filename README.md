# KrishiMitra – Your Smart Agricultural Assistant

“Empowering Farmers. Guiding Buyers. All with a Chat.”

KrishiMitra is the official chatbot of HaritSetu, a sustainable agri-commerce platform designed to simplify crop residue management for rural users. It provides real-time assistance to both farmers and buyers, helping them navigate the platform, understand price predictions, and use the features effectively.

Built with AI and a user-first approach, KrishiMitra brings conversational support directly to the heart of agri-tech.

## What KrishiMitra Can Do

For Farmers  
- Assist in logging crop details like Name, Phone, State, District, Crop Type, Residue Type, and Quantity  
- Explain how to use the listing form and what each field means  
- Provide guidance on AI-powered price prediction and how it benefits them  

For Buyers  
- Help in using search filters (by state, district, residue type)  
- Explain the Price Trends section and how to identify affordable sellers  
- Guide new users through login/signup and platform features  

AI-Powered Features  
- Explains the working of the machine learning model trained on 1000+ real samples  
- Prevents overuse/misuse of predictions with safeguards  
- Responds with helpful, context-aware answers based on HaritSetu's system

## Tech Stack

| Layer      | Technology Used                    |
|------------|------------------------------------|
| Chatbot    | Python, Flask                      |
| Frontend   | HTML, CSS (Minimal Interface)      |
| Backend    | Flask-based custom backend         |
| AI Model   | Trained regression model on crop residue dataset |
| Hosting    | Render (ML API + Chatbot backend)  |

## Live Demo

Access the chatbot on the deployed HaritSetu site:  
https://harit-setu.onrender.com  
Navigate to the KrishiMitra section on the homepage to try it live.

## Installation Guide

### Backend (Chatbot)

1. Clone the repository:
git clone https://github.com/ShantiKumariGautam/haritsetu-backend.git

2. Navigate to the chatbot folder:
cd haritsetu-backend/Chatbot_HaritSetu

3. Install dependencies:
pip install -r requirements.txt

4. Run the Flask app:
python chatbot.py


### Frontend

1. Use the `index.html` file inside the `templates/` directory to connect the chatbot UI.
2. Ensure the backend is running on the correct port and linked correctly.
3. Deploy the frontend using any static site hosting service (Render, Vercel, GitHub Pages, etc.)

## Why KrishiMitra?

KrishiMitra bridges the gap between technology and rural accessibility. Instead of navigating a complex app, users can just ask a question — and get help instantly. Whether it’s listing crops, checking prices, or filtering buyers, KrishiMitra makes the HaritSetu platform easier to use for everyone.

## Future Scope

- Voice-enabled chatbot for regional language support  
- WhatsApp integration for wider reach  
- Smart fallback responses for unseen queries  
- Analytics dashboard to improve conversation quality


## Conclusion

KrishiMitra is more than just a chatbot—it's a bridge between advanced technology and grassroots agricultural needs. By enabling intuitive, accessible, and AI-powered conversations, it simplifies the digital experience for both farmers and buyers. Whether it's listing crops, checking price trends, or getting help with navigation, KrishiMitra ensures no user feels left behind in the journey toward sustainable agri-commerce.

