<<<<<<< HEAD


# DEEPWORK

=======
# DEEPWORK

>>>>>>> 3874afa1af304265e91da5402ac14d0e297db17c
DEEPWORK is an advanced AI-powered research and browser automation tool using Playwright and Groq LLMs.

## Features
- Deep multi-layered research using Groq LLMs
- Automated browser search and content extraction (Playwright)
- Fact verification and contradiction analysis
- Modern, modular Python codebase

## Quick Start
1. **Clone the repository**
	```sh 
	git clone https://github.com/Rithish-2914/DEEPTECH-AI.git
	cd DEEPWORK
	```
2. **Create and activate a Python virtual environment**
	- Windows PowerShell:
	  ```powershell
	  python -m venv .venv
	  .\.venv\Scripts\Activate
	  ```
	- macOS/Linux:
	  ```sh
	  python3 -m venv .venv
	  source .venv/bin/activate
	  ```
3. **Install dependencies**
	```sh
	pip install -r requirements.txt
	```
4. **Install Playwright browsers**
	```sh
	python -m playwright install
	```
5. **Configure environment variables**
	- Copy `.env.example` to `.env` (or create `.env` manually)
	- Add your GROQ_API_KEY and other settings:
	  ```env
	  GROQ_API_KEY=your_groq_api_key_here
	  SEARCH_TIMEOUT=30000
	  MAX_SEARCH_STEPS=10
	  DEBUG=True
	  ```

## Usage

Run the main app in your terminal:
```sh
python main.py
```
Or pass a query directly:
```sh
python main.py "What is the future of AI in medicine?"
```

## File Overview
- `main.py`: Main application entry point
- `browser_controller.py`: Browser automation logic
- `research_agent.py`: AI research logic
- `.env`: Environment variables for API keys
- `requirements.txt`: Python dependencies
- `README.md`: Project documentation
- `LICENSE`: MIT License
- `CONTRIBUTING.md`: Contribution guidelines

## Troubleshooting & Tips
- **Virtual environment:** Always activate your venv before installing or running.
- **Playwright browsers:** If you see browser errors, run `python -m playwright install` again.
- **API errors:** Double-check your GROQ_API_KEY in `.env`.
- **Python version:** For best compatibility, use Python 3.11+.
- **Windows users:** Use PowerShell and run commands as shown above.

## Contributing
See `CONTRIBUTING.md` for guidelines.

## License
This project is licensed under the MIT License. See `LICENSE` for details.
