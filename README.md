# Culture Editorial Skill

A [Hermes Agent](https://hermes-agent.nousresearch.com/) skill for writing music and culture editorial that sounds like it belongs in Resident Advisor, Pitchfork, or boutique music journalism — not AI-generated content farm slop.

## What it does

- **RA voice**: casual authority, present-tense immediacy, confessional + editorial, vivid granular detail
- **Pitchfork voice**: conversational sharpness, pop-literate, political/cultural commentary woven into music analysis
- **Anti-patterns**: 25+ banned AI music writing tropes ("sonic landscape", "genre-defying", "melting pot of influences")
- **Phrasebook**: authentic turns of phrase for hooks, sonic description, cultural framing
- **Structural patterns**: RA review, Pitchfork feature, staff pick formats with worked example
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
- Any request for "RA style", "Pitchfork voice", or "music journalism"

## Voice snapshot

**Before (AI slop):**
> Kira Luno's debut album, *Glasshouse*, is a captivating journey through ambient soundscapes and techno rhythms. The Berlin-based artist creates an immersive experience that pushes the boundaries of electronic music.

**After (RA voice):**
> Kira Luno recorded *Glasshouse* in a Kreuzberg flat during Berlin's greyest winter months, and you can hear the season pressing against the windows. The field recordings—tram bells, distant U-Bahn rumble, what sounds like a neighbor practicing saxophone at 2 AM—aren't decorative atmosphere; they're the album's nervous system.

See the full worked example in [SKILL.md](SKILL.md).

## Author

Bak / Zak Krevitt — derived from analysis of live Resident Advisor and Pitchfork editorial, synthesized from patterns by Gabriel Szatan, Katie Thomas, Bella Aquilina, Walden Green, Hattie Lindert, and others.

## License

MIT — use it, fork it, adapt the voice to your own publication.
