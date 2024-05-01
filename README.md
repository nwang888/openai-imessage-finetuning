# send-my-texts

given a chat.db file, filters iMessage texts appropriately for a GPT 3.5-Turbo Finetune and sends it to OpenAI

1. drag and drop your chat.db file, found at `/Library/Messages/chat.db` into the `/data` folder
2. obtain an OpenAI Key, and add that to your `./zshrc` as specified here: https://help.openai.com/en/articles/5112595-best-practices-for-api-key-safety
3. run each cells individually, and by section.
4. ensure that you pass all the checks in the validation portion.
5. ensure that you copy and paste the returned file name from `client.files.create` into the `client.fine_tuning.jobs.create` and `client.fine_tuning.jobs.retrieve` parameters
6. Now you have a model that is being finetuned on OpenAI! You can view it on your finetuning dashboard once you log into your account
