# HackEd-Immersive-Cyber-Learning

HackEd-Immersive-Cyber-Learning transforms abstract security concepts into interactive, personalized adventures. By leveraging LLMs, intelligent AI agents, and an intuitive Streamlit interface, CyberSaga creates an engaging learning experience that adapts to each user's needs and learning style.

## Overview
HackEd takes users on narrative journeys through realistic cybersecurity scenarios where their decisions have meaningful consequences. Instead of passively consuming information about threats like phishing, ransomware, or social engineering, users become active participants in stories that teach practical security skills through experience.

## Features
- **Adaptive Narrative Engine**: Uses large language models to generate dynamic, branching security scenarios.
- **Security Guide AI Agent**: Maintains narrative coherence while tracking learning objectives.
- **Personalized Learning**: Adapts content based on the user's industry, role, and skill level.
- **Multi-Perspective Learning**: Experience security scenarios from different viewpoints.
- **Progress Tracking**: Dashboard showing security skills mastered and areas for improvement.

## Getting Started

### Prerequisites
- Python 3.8+
- Virtual environment (recommended)

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/CyberSaga.git
   cd CyberSaga
   ```
2. Create and activate a virtual environment (recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install the required packages:
   ```sh
   pip install -r requirements.txt
   ```
4. Create a `.env` file in the project root with your API keys:
   ```sh
   GROQ_API_KEY=your_groq_api_key_here
   ```

### Running the Application
Start the Streamlit application:
```sh
streamlit run app.py
```
The application will be available at [http://localhost:8501](http://localhost:8501).

## Project Structure
```
CyberSaga/
│── app.py          # Main Streamlit application
│── agent.py        # Security Guide AI Agent implementation
│── scenarios.py    # Scenario classes and factory
│── user_profile.py # User profile management
│── prompts.py      # Prompts for AI interactions
│── .env            # API keys and configurations
│── requirements.txt # Required dependencies
```

## Usage
1. Complete the onboarding process to personalize your experience.
2. Select a cybersecurity scenario that interests you.
3. Navigate through the scenario by making decisions.
4. Receive feedback and learning moments based on your choices.
5. Track your progress and skill development.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Built with [Streamlit](https://streamlit.io/)
- Powered by [Groq LLMs](https://groq.com/)
- [Agno](https://agno.io/) framework for agent capabilities
