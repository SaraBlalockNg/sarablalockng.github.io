---
layout: page
title: Gramle Breakdown
sidebar_link: false
toc: true
---

<video controls="" autoplay="" name="media">
    <source src="https://sarablalockng.github.io/teaching/gramle-time.mp3" type="audio/mp3">
</video>

# Date Navigation
{:.no_toc}

* Placeholder for Table of Content (Must not be removed)
{:toc levels="1"}

## Archive of Previous Months
{:.no_toc}
[April 2025](./gramle-archive/april25.md)

# May 5, 2025

## Original Spectrogram
{:.no_toc}
![Original](gramle-pics/050525.png "Original")

## Graphics
{:.no_toc}

### Segmentation
{:.no_toc}
![Segmentation](gramle-pics/050525-segmentation.png "Segmentation")

### Voicing
{:.no_toc}
![Voicing](gramle-pics/050525-voicing.png "Voicing")

### Formants
{:.no_toc}

![Formants](gramle-pics/050525-formants.png "Formants")

## First Guess
{:.no_toc}

* **Segment 1**: This segment is loud, with clear formants, so I think it's the stressed vowel. F1 is mid-high, and F2 starts very low and ends high. That is the kind of movement I'd expect from a formant transition (so maybe velar pinch on the next segment), or from a diphthong with a back nucleus and advanced offglide, like [aɪ] or [ɔɪ]. It is a little short for a diphthong though... I'm going to start with a low monophthong.
* **Segment 2**: This has the classic appearance of a stop on the spectrogram: a closure where the only thing happening is voicing, followed by a strong vertical line for the release, and then a short period of aspiration. The release is fairly soft, but it is followed by a fricative show that doesn't rule out the voiceless stops. I think the voicing bar here is an unreliable cue, but should probably give higher priority to [b, d, g] just in case.
* **Segment 3**: This first one looks like an [ʃ] to me, because it is voiceless and the center of gravity is medium-high, around 3500 Hz.
* **Segment 4**: We see clear formants, a lower amplitud, and it's between two fricatives so I think this is the unstressed vowel. F1 is low and F2 is high and they're both stable, so it's a high front vowel and probably a monophthong, either [i] or [ɪ]. With the amount of creak we're seeing, I'm a little more inclined to say [ɪ].
* **Segment 5**: This looks a lot like segment 3, except the center of the frication energy is higher up. The lack of voicing would indicate that this should be [s] then, but since it's after a vowel it could also be phonemically a /z/.

Nothing is coming to mind, so I'll not start with a word.
My first guess is
```diff
-a
-k
-ʃ
+ɪ
-z
```
Wow, I don't think I've gotten so wrong so far.

## Revision
{:.no_toc}

The alternative to my idea about the fricativeis that we are actually looking at affricates. If that's the case, then when I thought was a closure for a stop is the closure for the affricate. On second loo, right at the beginning it does look like there's a release burst in the waveform so there might be a stop there. Since F2 starts low there might be lengthening for lip pursing. Combined with the short aspiration I'm guessing this is a [b].

### Resegmentation
{:.no_toc}

![Resegmentation](gramle-pics/050525-resegmentation.png "Resegmentation")


My second guess is
```diff
-b
-aɪ
-tʃ
+ɪ
!dʒ
```

I'm sort of at a loss for that last segment, but maybe it's a wildly aspirated [t] for \<budget\>

My third guess is 
```diff
+b
+ʌ
+dʒ
+ɪ
+t
```
## Postmortem
{:.no_toc}

<audio controls>
  <source src="https://nascl.rc.nau.edu/MALD/BUDGET.wav" type="audio/wav">
  Your browser does not support the audio element.
</audio>


If you listen to the [t], it is really weird. I think what I've learned is to make sure that I'm looking at both the waveform and the spectrogram, and to remember my own rule that weird things happen at the end of words.

# May 1, 2025

Today we did the whole gramle in my Phonetics class. I unfortunately forgot to take a screenshot but the word was \<furbish\>. We got the first fricative and the final coda very quickly. The first coda and second onset were really troubling for the class. We believed that the stressed vowel was something with a mid-F1 and mid-low-F2, and started with wedge based on that. In the end, it was a central vowel but we failed to see the rhoticity. What threw everyone off was the manner of articulation of the third segment. There were shadowy formants that had us going down the nasal, approximant, fricative line. We did notice at the very end what looked like a release burst in the waveform, that enabled us to guess \<foppish\>. But in the end we had a 50/50 toss up between fervish (I still don't know what that means) and furbish.

Our guesses were:

1:
```diff
+f
-ʌ
-n
-ə
-s
```

2:
```diff
+f
-u
-l
+ɪ
+ʃ
```

3:
```diff
+f
-æ
-m
+ɪ
+ʃ
```

4:
```diff
+f
-a
-p
+ɪ
+ʃ
```

5:
```diff
+f
+ɝ
-v
+ɪ
+ʃ
```
