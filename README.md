
# AI Chat Wave 🌊

**AI Chat Wave** is an AI-powered chat application that allows users to engage in dynamic conversations with an intelligent virtual assistant. Built with **React** and powered by the **Gemini API**, this app demonstrates the power of modern conversational AI by providing real-time, insightful responses.

## 🎉 Features
- **Interactive Chat Interface**: A smooth, responsive chat interface for real-time conversations.
- **AI-Powered Responses**: Leveraging the Gemini API's NLP capabilities, the chat provides natural, contextual responses.
- **User-Friendly Design**: Simple and intuitive design for a seamless user experience.
- **Responsive Layout**: Optimized for both desktop and mobile devices.
- **Customizable Themes**: Choose from different themes to personalize the chat experience.

## 🛠️ Built With
- **React** - Frontend library for building user interfaces.
- **Gemini API** - Provides AI-powered, natural language processing for chatbot responses.
- **CSS Modules** - Used for scoped and modular styling.
- **Axios** - HTTP client for making API requests.

## 📂 Project Structure
- **/src**: Contains all main application files.
  - **components**: Reusable UI components for building the chat interface.
  - **services**: Logic for interacting with the Gemini API.
  - **assets**: Static files, including images, icons, and theme assets.
  - **App.js**: Core application logic for rendering and managing chat state.
  - **index.js**: Main entry point for rendering the app.

## 📄 Usage
1. **Start a Conversation**: Type a message in the chat box to begin.
2. **Real-Time Responses**: The AI will respond instantly, using Gemini's contextual language processing.
3. **Customize Your Chat**: Choose your preferred theme for a personalized look.

## 🚀 Getting Started

### Prerequisites
- **Node.js** and **npm** installed on your local machine.
- **Gemini API Key**: Sign up and get your API key at [Gemini](https://www.gemini.com/).

### Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/AnkushjainAj/ai-chat-wave.git
   cd ai-chat-wave
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**:
   - Create a `.env` file in the root directory.
   - Add your Gemini API key to the file:
     ```bash
     REACT_APP_GEMINI_API_KEY=your_gemini_api_key
     ```

4. **Start the Development Server**:
   ```bash
   npm start
   ```
   - This will start the application on [http://localhost:3000](http://localhost:3000), where you can access the chat interface.

### Running Tests
To ensure everything works as expected, run the test suite:
```bash
npm test
```
- This will run any unit and integration tests configured for the application.

### Building for Production
To create an optimized build of the app:
```bash
npm run build
```
- This will generate a `build` folder containing the production-ready files.

### Deploying the Application
To deploy the application, you can use hosting services like Netlify or Vercel:
1. Go to your hosting provider and create a new project.
2. Link your repository or upload the contents of the `build` folder.

## 🌌 Technologies Used
- **React**: For building the responsive and interactive UI.
- **Gemini API**: To fetch AI-driven responses.
- **CSS Modules**: For modular and scoped component styling.
- **Axios**: For handling API requests.

## 🤝 Contributing
Contributions are welcome! To contribute:
1. Fork the project.
2. Create a feature branch.
3. Commit your changes.
4. Open a pull request.

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ✨ Acknowledgments
Thanks to [Gemini](https://www.gemini.com/) for the powerful NLP API and support for this project.
