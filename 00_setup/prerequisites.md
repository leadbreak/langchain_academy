```bash
# On Ubuntu/Debian:
curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
sudo apt-get install -y nodejs
```

```bash
# Download ollama
curl -fsSL https://ollama.com/install.sh | sh

# Start Ollama
ollama serve
# In another terminal, verify that Ollama is running
ollama -v

# Pull the gpt-oss model (only need to do this once)
ollama pull gpt-oss

# Start the model locally
ollama run gpt-oss

# Check that it's running
ollama ps

```