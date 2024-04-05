# ollama-offline-installation
Ollama restricts the online installation in some cases such as while using VPN or having a high ping, this is a workaround to install it offline. First download the binaries and transfer it to your device:
- For x86: https://ollama.com/download/ollama-linux-amd64
- For arm: https://ollama.com/download/ollama-linux-arm64

On your device run the commands:
```
chmod +x ollama-linux-arm64
mv ollama-linux-arm64 /usr/local/bin/ollama
```
Run Ollama as a server:
```
ollama serve
```
Run the client in other terminal:
```
ollama run tinyllama
```
