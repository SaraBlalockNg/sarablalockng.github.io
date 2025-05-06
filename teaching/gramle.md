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

# May 6, 2025

## Original Spectrogram
{:.no_toc}
![Original](gramle-pics/050625.png "Original")

## Graphics
{:.no_toc}

### Segmentation
{:.no_toc}
![Segmentation](gramle-pics/050625-segmentation.png "Segmentation")

### Voicing
{:.no_toc}
![Voicing](gramle-pics/050625-voicing.png "Voicing")

### Manner of Articulation
{:.no_toc}
![Manner](gramle-pics/050625-manner.png "Manner of Articulation")

### Formants
{:.no_toc}

![Formants](gramle-pics/050625-formants.png "Formants")

## First Guess
{:.no_toc}

Today I got to do the gramle with my incredible Phonetics class.  This is our rationale:

 **Segment 1**: This segment is loud, with clear formants, so probably a stressed vowel. F1 is lowish, and F2 is very low. We said that it looks a little low to be a diphthong with a lot of movement, but we're looking for a higher back vowel.
* **Segment 2**: This has the classic appearance of a stop on the spectrogram: a closure where the only thing happening is voicing, followed by a strong vertical line for the release, and then a short period of aspiration. We didn't see velar pinch or any other strong formant transitions. We were skeptical of the voicing but combined with the short positive VOT unwilling to rule it out. This made our candidates [p, b, t, d]. We said that there was only subtle donwturn of the formants following the segment, so we were less likely to pick a bilabial.
* **Segment 3**: We saw clear formants with lower amplitude than segment 1, suggesting that this is an unstressed vowel. We considered [ə] and [ɪ], and since F2 is fairly high especially nearer to the end of the segment decided to start with the latter.
* **Segment 4**: We saw light formants with lots of zeros and low amplitude overall. We discussed that the formants mean this is either a nasal, approximant, or a fricative. Because of the low amplitude we ruled out approximants. We also ruled out all of the voiceless fricatives because we saw a clear voicing bar, and ruled out sibilants because of the lack of high energy noise. We also ruled out [ŋ] since we don't see velar pinch. This left us with [m, n, v, ð], and we decided to use phonotactics to pick from these.
* **Segment 5**: We observed a smear across the frequencies, but no clear center of energy. We also saw what may be a release burst in the waveform, but no clear vertical line in the spectrogram. We concluded based on this that it is either a low frequency sibilant [ʃ, ʒ], or a really quietly released stop. We didn't make claims about voicing even though there is no voicing bar, since final devoicing is so common.

Our first guess was:
```diff
-u
!d
-ɪ
+n
-ʃ
```

## Revision
{:.no_toc}

After viewing what we got partially right, we were confident that the last segment should be [d]. We talked about not wanting to change the place in the vowel space we're looking for our first segment, but thought that maybe [oʊ] would work since the formants don't move very far and it can be on the shorter side for diphthongs. When we combined that with what was left in our hypothesized candidates for segments 2 and 3, we ended up on the word \<opened\>.

Our second guess was 
```
+oʊ
+p
+ə
+n
+d
```

Woo hoo!
## Postmortem
{:.no_toc}
We listened to the audio, and the final [d] was in fact devoiced. Not too shabby for only being in Week 6 of 10!

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
