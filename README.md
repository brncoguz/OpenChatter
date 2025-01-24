# OpenChatter - Very Simple Chatbot

A minimalistic chatbot built with Anthropics’ API, designed for basic text-based conversations in the terminal.

Features:
- Stores conversation history for contextual responses.
- Easy-to-use interface with a quit command to exit.

Installation:
- `git clone https://github.com/yourusername/very_simple_chatbot.git`
- `cd very_simple_chatbot`
- `pip install -r requirements.txt`
- `export ANTHROPIC_API_KEY=your_api_key`

Usage:
- `python bot.py`
- Type your messages, and the chatbot will respond. Type `quit` to exit

Example Interaction:
```
Simple Chatbot (type 'quit' to exit)
You: Hello
Assistant: Hi! How can I help you today?
You: who are you? 
Assistant: I'm Claude, an AI assistant created by Anthropic. I aim to be direct and honest about what I am. How can I help you today?
You: which model are you using? 
Assistant: I'm an AI model called Claude, created by Anthropic. Beyond that core information, I aim to be transparent in acknowledging that I'm not entirely certain about my exact model specifications. Is there something specific you'd like to know about my capabilities?
You: how many languages can you speak? 
Assistant: I can communicate primarily in English and can understand and engage with several other languages to varying degrees, particularly major European languages like French, German, and Spanish. However, I'm most fluent and reliable in English. While I can work with other languages, my capabilities in them may be more limited, and I might make more mistakes. If you'd like to test a specific language, feel free to do so, but I'll be upfront about any limitations I encounter.
You: can you give me a famous german quote from Einstein and then translate it to English?
Assistant: Here's a famous quote from Einstein in German:

"Phantasie ist wichtiger als Wissen, denn Wissen ist begrenzt."

In English, this translates to:

"Imagination is more important than knowledge, for knowledge is limited."

This is one of Einstein's most well-known quotes, emphasizing the value of creativity and imagination in scientific thinking and human progress.
You: Great, thanks 
Assistant: You're welcome! Let me know if you need anything else!
You: quit
Goodbye!
```

Notes:
- This is a simple implementation intended for demonstration or learning purposes.
