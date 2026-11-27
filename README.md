# Specky by Summit Resume

Specky is the career agent for Summit Resume coaching clients and CareerOS
students. It tailors resumes, writes cover letters, builds and restyles career
walking decks, drafts networking messages, keeps your LinkedIn Profile doc up
to date, and helps you prepare interview stories, all in Summit Resume's
formats and saved to your own Google Drive.

## Set it up (once)

You need a paid Claude plan (Pro or above).

1. In Claude, open **Customize**, then **Plugins**, then **Add**, then
   **Add marketplace**, choose **Add from a repository**, enter `alexharlan27/specky`, leave
   **Sync automatically** on (that is how you get updates), and click
   **Sync**. Then install **Specky** from the **summit-resume** marketplace.
2. Connect **Google Drive** in your connectors.
3. Connect **Specky** and sign in with the email you use with Summit Resume.

Using Claude Code instead? Run:

```
/plugin install specky --marketplace alexharlan27/specky
```

Then just ask, for example: "Specky, tailor my resume to this posting."

## Privacy

Your documents stay in your own Google Drive. Specky only works for active
Summit Resume clients.
