# color-palette-generator 🖌️
A color palette generator made with ChatGPT and Python 

Description:
This portfolio project is an AI-powered color palette generator that leverages the capabilities of OpenAI's GPT-3 model. 
The web application, built using Flask, allows users to input text prompts 
describing a color palette and receive a JSON response containing a list of corresponding hexadecimal color codes.

Key Features:

Utilizes the OpenAI GPT-3 model for natural language processing.
Accepts user input in the form of text prompts describing color palettes.
Generates a 5-color palette in response to each prompt.
Provides responses in JSON format for easy integration with other applications.
Includes an interactive web interface for user interaction.

Technologies Used:

Flask: A Python web framework for building the web application.
OpenAI API: To interact with the GPT-3 model for natural language understanding.
dotenv: To securely manage environment variables.
HTML/CSS: For the frontend design and user interface. 
JSON: For exchanging data between the application and users.
Usage:

Users enter a text prompt describing a color palette.
The application sends the prompt to the OpenAI GPT-3 model.
The model responds with a JSON array of 5 hexadecimal color codes.
The color palette is displayed to the user on the web interface.


Future Improvements:

Enhanced user experience with real-time updates and previews of color palettes.
Integration with design tools and applications for practical use cases.
Option to save or download generated color palettes.
Improved error handling and validation for user input.
