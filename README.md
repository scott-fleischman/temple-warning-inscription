# Temple Warning Inscription Interactive Reader

I used Claude Opus 4.6 to create a working visualization of reading the Greek from the Temple Warning inscription that highlights text as it reads, and has a transcription with word spacing and dashes for line continuation, normalized Greek and English translation, with word highlighting through all of them. The original prompt was:

> Make a UI that will read outloud the greek in the inscription, and as it reads each word, it highlights it within the inscription. Furthermore, there are two text sections below. One has the inscription as is in Greek text (all caps just like the inscription) in the same letter layout as the inscription but with extra space between each word, and a dash at the end of a line to indicate words broken up by line. While the audio is being played, it highlights the word in this text part as well. Next there is a normalized Greek text section that lays out the text normally (not following the transcription) that as the audio reads the word, it is highlighted in this part. Finally there is an English translation that as the word is read in Greek, it highlights the English word/words that correspond to the Greek. Use high-quality voices, not system voices.

I also had follow-up prompts to improve the output.

It was then tweaked with GPT-5.4 to add a link for more information about the inscription and to allow hover highlighting and single-word Greek playback when not in play mode, with mobile tap support for the corresponding words. This README was also edited with GPT-5.4.

Wikipedia: https://en.wikipedia.org/wiki/Temple_Warning_inscription
