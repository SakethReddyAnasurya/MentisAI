# MentisAI

# The MentisAI project is a responsive, web-based chatbot designed to provide real-time conversational support using Google Gemini's language model API. Here’s a breakdown of the project’s components and key technical details:

Backend Setup with Flask: The backend of MentisAI is built using Flask, a lightweight Python web framework. The Flask server handles incoming user messages and routes them to Google Gemini API for generating responses. The /chat route in Flask processes user inputs, sends them to the AI model, and returns the response in JSON format, ensuring seamless communication between the frontend and backend.

Integration of Google Gemini API: MentisAI leverages Google Gemini API’s GenerativeModel to simulate real-time, human-like conversations. Using the send_message method, the chatbot interacts with users, analyzing the context and intent of each query to generate relevant responses. This API integration enables dynamic, on-the-fly responses that enhance the user experience by minimizing latency.

Interactive Frontend Interface: Built with HTML5, CSS, Bootstrap, and JavaScript, the frontend provides a polished, user-friendly chat interface. The HTML and CSS design elements create a professional, modern appearance, with smooth animations and user-specific color schemes. JavaScript (jQuery) functions manage message input, display, and scrolling, keeping the chat flow intuitive and efficient.
