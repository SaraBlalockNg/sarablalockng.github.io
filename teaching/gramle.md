---
layout: page
title: Gramle Breakdown
sidebar_link: false
toc: true
---

# About

This blog archives my performance on [gramle](https://nascl.rc.nau.edu/gramle/), a Wordle-style spectrogram game. The goal of this blog is to help phonetics students and fellow gramle lovers see one phonetician's thought process.

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

# May 8, 2025

## Original Spectrogram
{:.no_toc}
![Original](gramle-pics/050825.png "Original")

## Graphics
{:.no_toc}

### Segmentation
{:.no_toc}
![Segmentation](gramle-pics/050825-segmentation.png "Segmentation")

### Voicing
{:.no_toc}
![Voicing](gramle-pics/050825-voicing.png "Voicing")

### Formants
{:.no_toc}
![Formants](gramle-pics/050825-formants.png "Formants")

## First Guess
{:.no_toc}

Wow, is is a super sonorant word. The only easy part of segmenting this is the central segment, where the formants drop off. I'm assuming that the silence at the beginning is just a little bit of prevoicing, because I don't see a strong closure on the waveform and I already have 5 segments without a stop. I tried to learn from yesterday and use the waveform as a primary guide for segmentation this time.

* **Segment 1**: This is in a syllable onset position, so should be some kind of consonant. It is fairly high amplitude, with clear formants, very low F2 and mid-low F1. I believe that this makes it an approximant, and based on the F2 value I think [w] is most likely (should look like [u]).
* **Segment 2**: This is a high amplitude, long sound with clear formants, so must be our stressed vowel. F2 is super high and F1 is still mid-low. This puts us at the front top of the vowel space. Based on how high F2 is I'm going to start with [i].
* **Segment 3**: This is the only segment where the formants seem to die down. There is a voicing bar, and a center of gravity of the frequencies above 5000 Hz. So me that sounds like a textbook [z].
* **Segment 4**: I believe this is the unstressed vowel, since it is still fairly high amplitude with clear formants, and is just a little shorter than segment 2. F2 has only dropped off slightly. Since it's unstressed and still in the front of the vowel space, I'm very confident in guessing [ɪ].
* **Segment 5**: Here we see the amplitude dropping off, but the formants are staying clear. It doesn't look quiet enough for a non-sibilant fricative, so it's either a nasal, approximant, or a fading vowel. I can almost hallucinate velar pinch, which I would love because it goes well with the previous guess to make the \<ing\> morpheme.

My first guess is 
```diff
+w
+i
+z
+ɪ
+ŋ
```

Woohoo! I feel vindicated from my poor performance yesterday.

# May 7, 2025

## Original Spectrogram
{:.no_toc}
![Original](gramle-pics/050725.png "Original")

## Graphics
{:.no_toc}

### Segmentation
{:.no_toc}
![Segmentation](gramle-pics/050725-segmentation.png "Segmentation")

### Voicing
{:.no_toc}
![Voicing](gramle-pics/050725-voicing.png "Voicing")

### Formants
{:.no_toc}

![Formants](gramle-pics/050725-formants.png "Formants")

## First Guess
{:.no_toc}

The segmentation today is more confusing to me, but I drew these boundaries mainly going off of the strong vertical lines I see in the spectrogram, indicating release bursts.

* **Segment 1**: This has a smear of frequencies and a very high amplitude for an obstruent, so I think it must be a sibilant. I don't see a center of gravity very clearly, which may mean it's above 5000 Hz. Combined with the word position and lack of voicing bar, I think it's safe to say that this is [s]
* **Segment 2-3**: The second segment segment is clearly a stop, with a defined closure and release burst. It also looks like it precedes another closure. There are few consonant clusters in English that fit this pattern: \<spl\>, \<spr\>, \<str\>, \<skr\>, \<scl\>. Of those, ending in [l] I think is more likely for this spectrogram, as an unvoiced [l] is likely to look fricated. \<spl\> is more frequent than \<scl\>, so I go with the former.
* **Segment 4**: We see clear formants for a vowel, with a low F1 and VERY high F2. There's a little dip in F3 that could be rhoticity, but I'm not sure. What I do know is this should be at the very front of the vowel space.
* **Segment 5**: This is the segment I'm least confident in. The amplitude from the vowel dies gradually, so there may be a heavily released nasal, or some kind of word-final non-sibilant fricative, which is uncommon in English. I don't see evidence of a release burst in the spectrogram or the waveform, so learning against a stop.

I'm going to go with a word for my first guess.

```diff
+s
-p
-l
!i
-n
```

## Revision
{:.no_toc}

Huh, guess the double releases I saw in what I called segments 2-3 were a red herring. I'll have to pick another stop to go there, and since I don't see velar pinch I'll go with [t]. Now for the final 2 segments after the vowel. This is a nasal or an approximant followed by either a stop or a fricative. The words I'm thinking of that fit that are \<steals\> \<steeled\>, \<steams\>, and \<steamed\>. Of these, I think the energy is still too low for a final [z], so I'll say that the blip at 450 ms is a release for a [d]. Between [m] and [l], there are a couple of things I'm looking for. First, [l] and [d] have the same place of articulation, so I could envision a smooth transition with little visible closure, which works here. For [m], since the lips have to open and the tongue make a new closure, I'd expect more of a closure than I see here. Also, in this position in English I would expect [l] to be velarized, which is maybe why that F3 was dipping.

My second guess is
```diff
+s
-t
+i
-l
-d
```

Wow not a great day for the home team. I still have unused hypotheses, so let's try those.

My third guess is
```diff
+s
+k
+i
-m
-z
```

Rats, I am really batting zero out here today. I need to backtrack and look for more clues. Theres is a dip in the amplitude during what I've been calling "the vowel." What if this is a disyllabic word and the second syllable doesn't have an onset? That would explain the change in amplitude and also where this extra segment is coming from. The only word I can think of with that pattern is \<skiing\>, so I'll try that.

My fourth guess is
```diff
+s
+k
+i
+ɪ
+ŋ
```

Woo hoo!

## Postmortem
{:.no_toc}

What I learned from today is: don't ignore cues from the waveform! I am still chewing on why it looks like that [k] is released twice.

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

* **Segment 1**: This segment is loud, with clear formants, so probably a stressed vowel. F1 is lowish, and F2 is very low. We said that it looks a little low to be a diphthong with a lot of movement, but we're looking for a higher back vowel.
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
```diff
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
