# AI-Powered Resume Generator

#### Video Demo: <URL HERE>

#### Description:

This project is an AI-powered resume generator built with Python, Streamlit, and Cohere's AI API. It helps users create professional resumes by leveraging artificial intelligence to generate compelling content based on their input.

## Features

- This project features on User-Friendly Interface, AI-powered text improvement, AI-powered Resume-Builder, Multiple-Themes for Resume, Easy-to-understand logic-flow.

## How It Works

## How It Works

1. **User Input**: The user fills out a structured form in the Streamlit interface with the following fields:
   - Name
   - Email ID
   - Profession/Career objective
   - Education background
   - Internship experience
   - Projects completed
   - Skills and other relevant information

2. **AI Enhancement**: When the user submits their information, the application sends it to Cohere's AI API (command-a-03-2025 model). The AI processes the raw input and generates enhanced, professional descriptions for each section, making the content more compelling and polished.

3. **Review and Edit**: The AI-generated enhanced content is displayed back to the user in the Streamlit interface. Users have the option to review the enhanced descriptions and make any changes or modifications they want before finalizing their resume.

4. **Theme Selection**: Users can choose from 4 different professional resume themes/templates to customize the visual appearance of their resume, allowing them to select a style that best fits their preferences and industry.

5. **PDF Generation**: Once the user is satisfied with the content and has selected their preferred theme, they can generate a downloadable PDF version of their resume. The application formats all the information professionally according to the chosen theme and creates a clean, print-ready resume document.

6. **Download**: The user can download their finalized resume as a PDF file, ready to be sent to potential employers or used for job applications.


## Design Choices

**Streamlit**: Chosen for its simplicity and ease of use. Streamlit provides a straightforward Python framework for building web interfaces without requiring extensive web development knowledge, allowing me to focus on functionality rather than frontend complexity.

**Cohere AI API**: Selected for its powerful natural language generation capabilities. The command-a-03-2025 model effectively enhances user input into professional, polished resume content. I initially used the command-r model but had to update to command-a-03-2025 after the older model was deprecated in September 2025.

**PDF Generation**: Implemented to provide users with a downloadable, professionally formatted document ready for job applications.

**Multiple Themes**: Offering 4 different resume themes gives users flexibility to choose a style that matches their profession and personal preference, making the tool more versatile.

**Editable AI Output**: Rather than forcing users to accept AI-generated content as-is, I included an editing step. This ensures users maintain control over their resume while still benefiting from AI enhancement.


## Technologies Used

- Python
- Streamlit (for web interface)
- Cohere AI API (model: command-a-03-2025)


## Installation and Usage

1. Clone this repository
   
2. Install dependencies: ``` pip install -r requirements.txt ```
   
3. Set up your Cohere API key:
   - Create a `.env` file in the project root directory
   - Add your Cohere API key:``` COHERE_API_KEY=your_api_key_here ```
   - You can get a free API key from [Cohere's website](https://cohere.com)
     
4. Run the application:
```
   streamlit run app.py
```

## Files

- `app.py` - Main application file
- `requirements.txt` - Python dependencies
- `README.md` - This file
