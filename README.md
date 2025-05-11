# ChatGPT History Backup

This repository contains a backup of my ChatGPT conversation history. Conversations are saved and organized in Markdown (`.md`) format for easy readability and reference.

## Structure

Conversations are organized individually as Markdown files:

```
chatgpt-history/
├── conversation-1.md
├── conversation-2.md
├── conversation-3.md
└── ...
```

## Setup Instructions

To clone and use this repository:

```bash
git clone https://github.com/YOUR_USERNAME/chatgpt-history.git
cd chatgpt-history
```

## Automation

The backup process is automated via a scheduled script that copies conversation files and pushes updates regularly to this repository.

- **Platform:** Windows Task Scheduler
- **Script Language:** Python

## Requirements

- Python 3.x
- Git

Install dependencies:

```bash
pip install requests
```

## Usage

Manually save conversations from ChatGPT as `.md` files to your specified folder. Automation scripts will handle committing and pushing updates to GitHub.

## Contributing

Feel free to suggest improvements or submit pull requests.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for more details.
