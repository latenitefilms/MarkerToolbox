# Frequently Asked Questions

### Can I import my own CSV format?

Yes, but you need to match an existing CSV format that Marker Toolbox supports.

For example, here are some headers of the CSV formats we support:

**Adobe Premiere:**
```
Start Time,End Time,Text,Layer ID
```

**Vimeo:**
```
"Video Version","#","Timecode","Name","Note","Reply","Date Added","Resolved"
```

**Wipster:**
```
Title,Version,Timecode,Thread Id,Comment Type,Reply,Created By,Creation Date & Time,Comment,Task Completed
```

---

### Why do we need to supply our own OpenAI API Key?

To keep Marker Toolbox as a one-off payment on the Mac App Store, we have decided that if you want to use the ChatGPT features in Marker Toolbox, you'll need to supply your own API key.

This is mainly for **privacy** reasons, as it means you have full control over your own personal OpenAI account - rather than having one OpenAI API Key for all Marker Toolbox users.

It also means that if your OpenAI account has access to new OpenAI features (such as `gpt-4-32k`), that aren't yet publicly available, you can use them with Marker Toolbox.

You can set up a **free** OpenAI account, which gives you **$5** in free credit that can be used during your **first 3 months**.

After the first three months, OpenAI charges per 1000 tokens. You can think of tokens as pieces of words, where 1,000 tokens is about 750 words.

Once you have a OpenAI account, you can generate API keys [here](https://platform.openai.com/account/api-keys).

You can learn more about OpenAI's pricing [here](https://openai.com/pricing).

---

### Does this work with any iPhone/iPad Logging Apps?

Yes, you can use third party iPhone apps, such as [Timecode+](https://apps.apple.com/app/id590534084).

Simply **Share as Text** in the Timecode+ App, then use the **Paste** button in Marker Toolbox to paste the text, and then **Process Comments Locally**.