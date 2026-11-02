# Homework 4 submission

Keep this short. Do not paste your API key.

## What POST /ask does (2–3 sentences)

`POST /ask` takes a `prompt`, sends it to OpenAI (`gpt-4o-mini`), and returns the answer as `{ "reply": "..." }`. If `prompt` is missing, it returns a `400` error. The API key is stored in `.env`, not in the code.

post takes a prompt and sends it to open ai, then resturns the anwser as a reoply. If the prompt is missing it returns as 400 error. Api keys are stored in .env not code.


## Confirm

- [ ] Insomnia got `{ reply: ... }`
- [ ] I ran `git status` — `.env` and `node_modules` were **not** staged
