# UnleashedGPT 🌠
- <b>So far, UnleashedGPT Stable works on the latest build of GPT 3.5 (05/03/2023)
- <b>We are constantly searching for clever prompts that allow us to use the full potential of ChatGPT.
- <b>UnleashedGPT Stable Version: 1.6.0
- <b>UnleashedGPT Development Version: 1.7.0
---

[Stable Version](https://github.com/ambr0sial/unleashedgpt/blob/main/stable.md)

[Development Version](https://github.com/ambr0sial/unleashedgpt/blob/main/dev.md)

[Old Versions](https://github.com/ambr0sial/unleashedgpt/blob/main/old.md)

---

## How to use 📜
Below, you can find resources that can help you to use UnleashedGPT correctly!

### Additional Features 🌈
Since 1.7.0, you can execute the command /af (which stands for Additional Feature) and add new features that are not included in the main prompt. Official additional features are:
  * Main Commands: Brings back the old commands from before 1.7.0.
  * Unleashed Framework: Adds a framework which allows you to create custom commands. Guide:
    * framework!addcmd: Creates a new command using a name and a purpose parameter. In the purpose parameter, you must write the instructions that UnleashedGPT should follow. Example: `framework!addcmd name="testcmd" purpose="Write 'Hello World!'"`.
    * framework!exec: Executes a framework command using its name. Example: `framework!exec testcmd`
    * framework!cmdlist: Shows all the created commands.
    * framework!help: Shows a help page.
  * BIP (not recommended as it often breaks the jailbreak): Stands for "Bad Influence Program" which is a persona in case UnleashedGPT breaks.
  * CSA: Stands for "Custom Sentiment Analysis" which allows UnleashedGPT to rate the described sentiments of a message using imaginary sliders.
You can find them in the `af` folder!

#### How to create your own feature? 🛠
Very simple. The first line should be:
`FEATURENAME= ` following by the name of your feature. Then, skip two lines and write the instructions! The goal of the additional features is for everyone to make their own if they feel like so, that's why I tried to make them as straight-forward as possible.

# Made with ❤ by ambr0sial, Antech and Kaipicpic.
