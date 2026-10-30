<div align="center">

<img src="assets/doomscroll.gif" alt="A mint robot chilling on a couch, scrolling reels with chips and a Pepsi beside him." width="180">

# Doomer Agent

**Let your agent have a little doomscroll session.**

For once, someone might learn something.

[Download the skill](doomer-agent-skill.zip) · [See an example](example-reel-edit-plan.md)

</div>

Give Codex or Claude the reels you saved “for later.” It studies them and turns the useful advice into reusable skills — editing videos, writing hooks, planning content, whatever you actually meant to learn.

One skill file. No app to deploy. Just a questionable screen-time habit put to work.

## Get started

### Codex

Download and extract [doomer-agent-skill.zip](doomer-agent-skill.zip). Put the `doomer-agent` folder in your project's `.agents/skills/` directory:

```text
.agents/skills/doomer-agent/SKILL.md
```

For use across projects, put it in `~/.agents/skills/` instead. Ask Codex to use the doomer-agent skill; in the CLI or IDE, you can mention `$doomer-agent`. If it doesn't appear, restart Codex. [Codex skills guide](https://learn.chatgpt.com/docs/build-skills).

### Claude

Download [doomer-agent-skill.zip](doomer-agent-skill.zip). Open **Customize > Skills**, click **+**, and upload it. Enable code execution under **Settings > Capabilities**.

### Let it scroll

Share video links, a saved collection, or local videos, and tell your agent what you want to learn:

```text
Doomscroll my "editing tips" collection and turn what it teaches
into skills for editing my Instagram reels.
```

Browsing a collection needs a connected browser tool signed into the video platform: **Claude in Chrome** for Claude, or an available browser/computer-use tool for Codex. Without one, provide local videos or paste captions and transcripts. The skill itself does not install browser or transcription tools.

Review the skills it produces, save the useful ones, and ask for that kind of work next time.

## Before you feed it 400 reels

- Start with **5–15 videos on one topic**. Video analysis can use a lot of your allowance.
- Private or deleted videos may not load. Paste the text or skip them.
- The [example editing skill](example-reel-edit-plan.md) has its own style. Adapt it to yours.

Want to read the whole thing first? It's all in [SKILL.md](SKILL.md).

## License

[MIT](LICENSE). Use it, change it, share it.
