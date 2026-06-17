# Vocab Builder

Generate Burmese-English vocabulary lists for Pyaw lessons.

## When to use
Activate when the user asks to "generate vocab", "build vocabulary", or "add words" for a topic or lesson.

## How to run
1. Ask for the topic (e.g. "at the market", "job interview", "daily greetings")
2. Ask for the level: beginner / intermediate
3. Generate 8-10 vocabulary items in this JSON format:

```json
[
  {
    "english": "hello",
    "phonetic": "heh-LOH",
    "burmese": "မင်္ဂလာပါ",
    "example_en": "Hello, how are you?",
    "example_my": "မင်္ဂလာပါ၊ နေကောင်းလား?"
  }
]
```

## Rules
- Always use Unicode Burmese script (not Zawgyi)
- Keep English simple and practical for everyday use
- Phonetic guides help beginners who cannot read IPA
- Output valid JSON suitable for import into src/data/vocab/
