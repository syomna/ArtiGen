
# ArtiGen

ArtiGen is a React.js project for generating images from text using the power of AI. It provides a user-friendly interface that allows users to enter text or use speech-to-text functionality to generate images. The generated images can be downloaded by the users.

## Technologies Used

- React.js
- Material-UI (MUI)
- Eden AI
- react-speech-recognition

## Features

- Text input field for entering the text to generate images.
- Speech-to-text functionality for easy input using voice.
- Integration with Eden AI for generating images based on the entered text.
- Download option to save the generated images.

## Installation

To run the ArtiGen project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/syomna/ArtiGen.git` 

2.  Navigate to the project directory:
    
    
    `cd ArtiGen` 
    
3.  Install the dependencies:
    
    
    `npm install` 
2.  Add Eden AI API Key:
    
    -   Obtain an API key from Eden AI by signing up at [https://www.edenai.co/](https://www.edenai.co/).
        
    -   Copy the API key provided by Eden AI.
        
    -   In the project, open the file `src/components/Form.js`.
        
    -   Locate the line with the variable `token` and replace the placeholder text with your Eden AI API key:
        
        
        `const token = "YOUR_API_KEY_HERE";` 
        
    
4.  Start the development server:
    
    
    `npm start` 
    
    This will run the project locally on `http://localhost:3000`.
    

## Credits

-   React.js: [https://reactjs.org/](https://reactjs.org/)
-   Material-UI (MUI): [https://mui.com/](https://mui.com/)
-   Eden AI: [https://www.edenai.co/](https://www.edenai.co/)
-   react-speech-recognition: [https://www.npmjs.com/package/react-speech-recognition](https://www.npmjs.com/package/react-speech-recognition)