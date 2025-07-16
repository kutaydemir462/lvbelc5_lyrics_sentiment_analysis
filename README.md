# Lvbel C5 Lyrics: Why Sentiment Analysis Flopped

This project started as a sentiment analysis experiment on the lyrics of Turkish rapper **Lvbel C5**.

I wanted to explore:
- How his tone and emotional themes changed over the years
- Whether lyrics got more positive (luxury, girls) or stayed dark (streets, struggle, police)

---

## But, It Didn’t Work.

I tried:
- Lexicon-based sentiment scoring (Turkish wordlists)
- Pretrained Turkish BERT model from HuggingFace

### Results:
- BERT predicted `"neutral"` for almost everything
- It couldn’t handle slang, sarcasm, or long poetic lyrics
- AI doesn't really get Lvbel's world — yet

---

## Why I Still Published This

This project reflects a real-world data challenge:
- Not everything works out as expected
- Pretrained models aren’t always a plug-and-play solution
- Understanding your data (and its limits) is part of being a data analyst

---

## Files

- `lyrics_analysis.ipynb`: Main notebook
- `lvbelc5_lyrics_database.db`: SQLite database of 40+ Lvbel C5 songs and lyrics
- `README.md`: This file

---

## What's Next?

I'll continue this exploration with:
> How often does Lvbel talk about "sarışın kızlar" (blonde girls)?  
> Does he really flex more now than before?  
> What topics dominate his music?

That will be uploaded as a follow-up project here on GitHub.


