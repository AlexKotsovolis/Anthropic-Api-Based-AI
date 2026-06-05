# K0sh AI

A modern desktop chat client built with Python, Tkinter, and Anthropic's Claude API.

K0sh AI provides a simple and responsive interface for chatting with Claude models while maintaining conversation history and streaming responses in real time.

## Features

* Real-time streaming AI responses
* Clean dark-themed UI
* Conversation memory
* Multi-threaded response handling
* Chat clearing functionality
* Easy customization of colors and system prompts
* Built using Python and Tkinter

## Screenshot

Add a screenshot here:

```markdown
<img width="909" height="736" alt="image" src="https://github.com/user-attachments/assets/b2de65d1-87b1-4b29-b3b7-36d24bfa73cc" />

```

## Requirements

* Python 3.10+
* Anthropic Python SDK

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/k0sh-ai.git
cd k0sh-ai
```

Install dependencies:

```bash
pip install anthropic
```

## Configuration

Open the source file and replace:

```python
ANTHROPIC_API_KEY = "your api key here"
```

with your Anthropic API key.

You can also customize the assistant personality by editing:

```python
SP = "You are a friendly and helpful assistant..."
```

## Running

Start the application:

```bash
python main.py
```

## Project Structure

```text
k0sh-ai/
│
├── main.py
├── README.md
├── LICENSE
└── screenshot.png
```

## Customization

You can modify:

* Window title
* Color palette
* Assistant name
* Default system prompt
* Claude model selection

Example:

```python
model="claude-sonnet-4-6"
```

## Notes

* Keep your API key private.
* Never commit API keys to GitHub.
* Consider using environment variables for production use.

Example:

```python
import os

ANTHROPIC_API_KEY = os.getenv("ANTHROPIC_API_KEY")
```

## Contributing

Pull requests are welcome. Feel free to open issues for bug reports, feature requests, or suggestions.

## Author

Created by @myboialex3

## License

This project is licensed under the MIT License. See the LICENSE file for details.
