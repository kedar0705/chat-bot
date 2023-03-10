# chat-bot(MathBot)
MathBot is a simple chatbot that can perform basic mathematical operations. It uses OpenAI's GPT-3 API to generate responses to user input.

The code requires the openai Python package to be installed. You can install it using the - "pip install openai"

Additionally, the code requires an OpenAI API key. You can obtain one by signing up for an OpenAI account and creating an API key in your dashboard. Once you have your API key, you can set it as an environment variable in your terminal or command prompt using the following command:

export OPENAI_API_KEY=<your_api_key>

Replace <your_api_key> with your actual API key. Alternatively, you can hardcode your API key in the code by replacing os.environ["OPENAI_API_KEY"] with a string containing your API key. However, this approach is not recommended for security reasons.

Once MathBot is running, you can enter various mathematical operations like "add", "subtract", "multiply", and "division" to perform calculations. MathBot will prompt you for the operands and generate a response using OpenAI's GPT-3 API.

To exit MathBot, simply type "bye".
