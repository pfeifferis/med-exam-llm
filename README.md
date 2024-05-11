# med-exam-llm
## Activate virtual environment
```
python3 -m venv med-exam-llm-venv
source med-exam-llm-venv/bin/activate
```
## Install requirements
```
pip install -r requirements.txt
```
## Set up api keys
```bash
nano ~/.zshrc
```
```
export OPENAI_API_KEY='your-api-key-here'
export ANTHROPIC_API_KEY='your-api-key-here'
export GOOGLE_API_KEY='your-api-key-here'
```
```bash
source ~/.zshrc
```
```bash
echo $OPENAI_API_KEY
```
