# AI-Powered Blog Paragraph Generator  

This Python script uses OpenAI's GPT-3.5 Turbo model to generate paragraphs on any topic you provide. It interacts with the user through the command line, allowing them to request multiple paragraphs until they choose to stop.  

## Features  
- Uses OpenAI's GPT-3.5 Turbo for text generation.  
- Interactive command-line interface.  
- Generates well-structured paragraphs based on user-provided topics.  

## Prerequisites  
- Python 3.x  
- An OpenAI API key (stored in a `.env` file).  
- Required dependencies:  
  - `openai`  
  - `python-dotenv`  

## Installation  
1. Clone this repository or copy the script.  
2. Install dependencies using pip:  
   ```bash
   pip install openai python-dotenv
   ```
3. Create a `.env` file in the project directory and add your OpenAI API key:  
   ```
   API_KEY=your_openai_api_key_here
   ```
4. Run the script:  
   ```bash
   python blog_generator.py
   ```

## Usage  
1. The script prompts you with:  
   ```
   Write A Paragraph? Y for yes, anything else for no.
   ```
2. Enter `Y` or `y` to generate a paragraph.  
3. Provide a topic when prompted.  
4. The script will generate and display a paragraph based on the topic.  
5. Repeat the process or enter any other key to exit.  

## Example Output  
```
Write A Paragraph? Y for yes, anything else for no.  
Y  
What should this paragraph be about? Artificial Intelligence
(Insert Paragraph about AI here...)
```

## Notes  
- The script uses OpenAI's `gpt-3.5-turbo-instruct` model.  
- `max_tokens` is set to 400, and `temperature` is set to 0.3 for controlled creativity.  
- Ensure you have an active OpenAI API key with sufficient quota to generate responses.  

## License  
This project is free to use and modify. Feel free to contribute or improve upon it! 🚀  
