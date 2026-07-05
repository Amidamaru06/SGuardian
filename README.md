#SGuardian

Protects older adults from AI-driven fraud scam texts, phishing links, and deepfakes. 
Runs locally on a Raspberry Pi 5 using Phi-4 Mini. No cloud. No cost.

## Usage

```bash
git clone https://github.com/YOUR_USERNAME/guardianai.git
cd sguardian
pip install -r requirements.txt
ollama pull phi4-mini
uvicorn backend.main:app --host 0.0.0.0 --port 8000
```

Then open `http://<your-pi-ip>:8000` on any device on the same network.

## Features

Link guard — checks URLs for threats before you click
Paste & check — paste any suspicious SMS or email, get a plain verdict
Deepfake shield — detects AI-manipulated images on-device

## License

MIT
