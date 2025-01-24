# Resume Classifier

**Resume Classifier** is an AI-powered resume screening tool designed to empower candidates by pre-assessing their job suitability. It automates resume and job description comparisons to provide clear suitability decisions and personalized feedback. Additionally, the tool integrates with Gmail and Google Calendar to streamline the hiring process, from sending rejection emails to scheduling interviews through Google Meet.

## Features
- **Resume and Job Description Comparison**: Automates the comparison process to provide suitability decisions.
- **Personalized Feedback**: Offers candidates personalized feedback on their resumes.
- **Seamless Integration**: Integrates with Gmail and Google Calendar to handle rejection emails and interview scheduling.
- **Effort and Time Saving**: Boosts candidates' confidence and clarity while saving their time and effort.
- **Interview Scheduling**: Automatically sends Google Meet links for interviews if the candidate is shortlisted.

## Technologies Used
- **Python**
- **Gmail API**
- **Google Calendar API**
- **Groq API**
- **Langchain**

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your_username/resume-classifier.git
    ```
2. Navigate to the project directory:
    ```bash
    cd resume-classifier
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Run the main script to start the application:
    ```bash
    python main.py
    ```
2. The script will automatically compare resumes against job descriptions and provide suitability decisions.
3. If a candidate is shortlisted, the script will send a Google Meet link for the interview through email.

## Configuration
1. Update your `config.py` file with the necessary API keys and credentials:
    ```python
    GMAIL_API_KEY = 'your_gmail_api_key'
    GOOGLE_CALENDAR_API_KEY = 'your_google_calendar_api_key'
    GROQ_API_KEY = 'your_groq_api_key'
    LANGCHAIN_API_KEY = 'your_langchain_api_key'
    ```

## Contribution
Feel free to open issues or submit pull requests if you have any suggestions or improvements.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Special thanks to the creators and maintainers of the APIs and technologies used in this project.
