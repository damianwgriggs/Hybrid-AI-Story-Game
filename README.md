The Generative Bard: A Two-Tiered AI Mind
The Generative Bard is more than a text-based adventure game; it is a working demonstration of a new cognitive architecture for AI. By engineering a system with distinct short-term and long-term memory, this project solves the fundamental problem of contextual amnesia in large language models, enabling truly coherent, long-form interactive narratives.

This project is the proof-of-concept for the principles outlined in the article, "The Two-Tiered Mind: How I Built an AI That Can Finally Remember Its Own Story."

The Core Innovation: A Two-Tiered Cognitive Architecture
Modern LLMs are brilliant sprinters but poor marathon runners. They forget key details and lose the plot over time. This application solves that by modeling its AI's "mind" after the human brain, separating memory into two distinct, cooperative layers.

1. The Bard (Short-Term / Tactical Memory)
The "Bard" is the front-line AI persona. It handles the immediate, turn-by-turn interaction with the user.

Function: Reacts to the player's current action.

Context: Sees the player's inventory and a rolling window of the last 5-10 turns.

Analogy: Human working memory—fast, fluid, and focused on the now.

2. The Chronicler (Long-Term / Strategic Memory)
The "Chronicler" is the historian AI persona, powered by the Perceptual Grid Engine (PGE). It works in the background to build a persistent world history.

Function: Activates periodically (e.g., every 10 turns) to read the last "act" of the game.

Context: Synthesizes the key plot points, characters, and decisions into a concise summary.

Analogy: Human long-term memory—the repository of knowledge and experience that gives the present meaning.

Every decision the Bard makes is informed by the comprehensive history maintained by the Chronicler, creating a deeply coherent and endlessly engaging experience.

Getting Started
Follow these steps to run your own instance of The Generative Bard.

Step 1: Prerequisites
Python 3.9+

An active Google AI Gemini API Key.

Step 2: Clone the Repository
Open your terminal and clone this repository to your local machine:

git clone [https://github.com/YOUR_USERNAME/the-generative-bard.git](https://github.com/YOUR_USERNAME/the-generative-bard.git)
cd the-generative-bard

Step 3: Install Dependencies
This project uses Streamlit and Google's Generative AI library. Install them using pip:

pip install streamlit google-generativeai

Step 4: Configure Your API Key
Open the super_dnd_game.py file in a code editor and locate the following line:

# line 11
API_KEY = "AIzaSyCzpbppeKtGPnCatdhAHjIXkA1YFd1nAHM" 

Replace the placeholder key with your actual Gemini API key.

Step 5: Run the Application
In your terminal, from the project's root directory, run the following command:

streamlit run super_dnd_game.py

The application should automatically open in a new tab in your web browser.

The Philosophy: An Experiment in Value Creation
This project is an open-source demonstration of my core theory: the most efficient path to long-term value is to give so much to the world that it is compelled to respond. This is a powerful piece of intellectual property, released freely to showcase the power of architecting better systems.

By building with it, you are participating in this experiment.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Author & Innovator
Damian Griggs - Architect & Developer

Website

Contact
