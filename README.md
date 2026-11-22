# PromptForge
A browser-based mock interview coach by NeuralForge for SCSE4041. Choose a role and experience level, answer an opening question, receive feedback on clarity, relevance, completeness and technical accuracy, then practice a follow-up.

## Run locally
Open `index.html` in a modern browser. Guided practice runs offline for software developers, data analysts and product managers at fresher and experienced levels.

For live interviews, select Gemini, Groq, OpenAI (ChatGPT), or OpenRouter under **Coach**. Enter your own provider API key and choose a model available to your account. The app sends the interview context directly from your browser to the selected provider. Use fictional practice data. Provider quota and access rules apply. Keep API keys out of repository files.

## Publish with GitHub Pages
1. Extract the ZIP and upload its contents to the root of your repository so `index.html` is at the top level.
2. In **Settings → Pages**, choose **Deploy from a branch**, select the branch containing the files and the **/(root)** folder, and save.
3. Open the published Pages URL and try a guided interview.

## Source
The interface, question bank, interview prompts and provider integrations are in `index.html`. No build step or dependencies are required. The repository includes the browser app and excludes the earlier notebook prototype.
