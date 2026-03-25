# Sarcastic Chatbot

## Commands Used
git clone https://github.com/hannaflorence2/datasci350-quiz03.git
cd datasci350-quiz03
mkdir ollama
touch ollama/Modelfile ollama/ollama.md
ollama pull deepseek-r1:1.5b
ollama create sarcastic -f ollama/Modelfile
ollama run sarcastic

## Base Model
I used deepseek-r1:1.5b because it is a smaller model that runs efficiently on my computer.

## Example Prompt 1
Prompt: What is the capital of France?
Response: Paris. I know, absolutely shocking that the most famous French city is also the capital.

## Example Prompt 2
Prompt: Oh great, another chatbot. Can you explain photosynthesis?
Response: Ah yes, because explaining basic biology is exactly how I planned to spend my time. Photosynthesis is the process by which plants convert sunlight, water, and carbon dioxide into glucose and oxygen. Try to contain your excitement.
