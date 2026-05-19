# Culture Editorial Skill

A [Hermes Agent](https://hermes-agent.nousresearch.com/) skill for writing music and culture editorial that sounds like it belongs in a boutique music publication — not AI-generated content farm slop.

## What it does

- **Insider voice**: casual authority, present-tense immediacy, confessional + editorial, vivid granular detail
- **Conversational voice**: sharpness, pop-literate references, political/cultural commentary woven into music analysis
- **Anti-patterns**: 25+ banned AI music writing tropes ("sonic landscape", "genre-defying", "melting pot of influences")
- **EM DASH BAN**: double-emphasis rule against em dashes, a prototypical AI voice marker
- **Sentence rhythm AI tells**: banned patterns like uniform sentence length, overuse of present participles, triple-adjective lists
- **Direct writing samples**: real excerpts from music journalism to study and internalize
- **Phrasebook**: authentic turns of phrase for hooks, sonic description, cultural framing
- **Structural patterns**: insider review, conversational feature, staff pick formats with worked example
- **Voice calibration**: how to adapt to custom publications from a writing sample

## Usage

Drop this into your Hermes Agent skills directory:

```bash
# Clone into your skills path
git clone https://github.com/ZakKrevitt/culture-editorial-skill.git ~/.hermes/skills/culture-editorial

# Or use Hermes CLI
hermes skills install culture-editorial
```

Then reference it in your agent prompt or load it when writing about:
- Music reviews, album previews, festival coverage
- Club culture, scene reports, venue guides
- Artist profiles, staff picks, listicles
- Any request for "insider style", "conversational voice," or "music journalism"

## Voice snapshot

**Before (AI slop):**
> Kira Luno's debut album, *Glasshouse*, is a captivating journey through ambient soundscapes and techno rhythms. The Berlin-based artist creates an immersive experience that pushes the boundaries of electronic music.

**After (insider voice):**
> Kira Luno recorded *Glasshouse* in a Kreuzberg flat during Berlin's greyest winter months, and you can hear the season pressing against the windows: Ttram bells, distant U-Bahn rumble, what sounds like a neighbor practicing saxophone at 2 AM. Field recordings do the actual work on this album, feeding directly into beats that move like someone trying to keep warm.

See the full worked example in [SKILL.md](SKILL.md).

## Author

Bak / Zak Krevitt — derived from analysis of live music journalism, synthesized from professional editorial patterns.

## License

MIT — use it, fork it, adapt the voice to your own publication.
