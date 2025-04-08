---
layout: page
title: Gramle Breakdown
sidebar_link: false
---
* TOC {:toc}

## April 8, 2025

### Step 1: Segmentation

At first pass, the segmentation for this gramle seems pretty straightforwards. 
In the first region (red) we see aperiodic sound, evenly distributed acros the visible frequencies, with no strong formants.
In the second region (orange) we see strong formants, very periodic waveform, with a transitory F2.
From the second to the third region (yellow), there is a noticible dropoff in overall intensity (much lighter spectrogram). The formants are still visible but are much lighter.
The intensity of the waveform picks back up in the fourth region (green) and we can see regular formant patterns, but this is a quieter sound than the second region.
The last region (blue) has a two-pattern temporal sequence. First, there's what looks to be a complete closure. Then we see a release of that closure into aperiodic sound.
While this has two specific patterns in the spectrogram, it is still consisten with a single phone. We'll see this next.

![Segmentation](gramle-pics/040825-segmentation.png "Segmentation")

### Step 2: Manner of Articulation

My guesses and rationale for the manners of articulation for each segment are as follows

* R1: Fricative or aspirated stop
  * aperiodic
  * at the beginning of the word (sometimes a release burst is hard to see at the beginning of a recording)
  * low amplitude
* R2: Stressed vowel
  * high amplitude
  * strong formants
  * long
* R3: Nasals
  * Lower amplitude
  * Visible, but faint formants
* R4: Unstressed vowel
  * medium amplitude
  * strong formants
  * longer than the consonants but not as long as the other vowel
* R5: Stop
  * Very low amplitude region (closure) followed by a sharp line (release burst) and aperiodic noise (aspiration)
 
### Step 4: Voicing

To check for voicing on each segment, I am looking for a voice bar in the bottom of the spectrogram at a reasonable frequency for this speaker. The recordings for gramle come from the MALD database (Tucker et al. 2019), which are made by an adult Canadian male. It looks like theres consistent voicing throughout the entirety of the word up until the final release. Before 50 ms, it's hard to tell whether there's actually voicing or if it's just aperiodic noise in all frequencies including and overlapping with voicing frequencies. For now, I'll say that everything is voiced except maybe the first segment.

![Voicing](gramle-pics/040825-voicing.png "Voicing")

### Step 3: Formants

We should consider the formant ranges that ought to be associated to different vowel qualities, within the context of adult Canadian male speech. Formants will also be helpful in figuring out the place of articulation of the consonants.

For the first vowel, it looks like F1 is around 600-800 Hz, which is quite high. So I suspect this is a low vowwel. F2 goes from about 1800 Hz to 1200 Hz, really spanning the range for this speaker. This may mean it's a diphthong that goes from a front nucleus to a back offglide. The other option is that this quality is influenced by the sounds around it. If we look at F3, I can see something that looks like velar pinch between F2 and F3, though it's subtle. This could mean that the sound that comes before this vowel is velar, like a [k].

![Formants of vowel 1](gramle-pics/040825-formants1.png "Formants of Vowel 1")

The formants of the nasal are pretty boring. They transition smoothly between the vowels. If we were dealing with a bilabial nasal [m], I would expect all the the formants to dip down towards the nasal. For the velar nasal [ŋ], I'd wanna see velar pinch. And I don't see either of these.

![Formans of nasal](gramle-pics/040825-formants2.png "Formants of Nasal")

The formants of the unstressed vowel show a little bit of transition on either end, but are pretty horizontal. It looks like F1 is keeping around 500 Hz, and F2 is around 1500 Hz. I think for this speaker those are both middle of the pack ranges. The is a little scoop of F2 right at the end, which again may point to the sound after this vowel being velar.

![Formants of vowel 2](gramle-pics/040825-formants3.png "Formants of Vowel 2")

### Step 4: First guesses

My first guesses are: 
```diff
+ [k]
- [a]
- [n]
- [ə]
- [g]
```
### Step 5-?: Revision

Okay so I only got the first segment [k] right. That tells me I was right about the formant movement in the first vowel being due to transition. I'm still loking for a low vowel, but not [a]. It is pretty long, so might be a flatter diphthong like [ɑʊ] or [oʊ]. I still feel like the segment in between the vowels is a nasal; the amplitude is too low for a vowel and it's too formant-y for most consonants. I guess it could be an approximant, but then I think the amplitude is still too low. For the unstressed vowel, I think I'll revise given that the final segment isn't [g], and treat F2 like it's highter (for a fronter sound). For the last stop, on second look there's a lot of aspiration for a voiced stop. Maybe that voicing bar is just bleed-over from the vowel. I'm going [t], because I don't see dips down for a bilabial transition like I'd expect for [p].

My second guess is: 

```diff
+ [k]
- [oʊ]
- [m]
- [ɪ]
- [t]
```

Wow, didn't do any better. I guess I'm giving up on this nasal idea, because there's still no sign of velarization. I'll move to an approximant [l] and try similar qualities for the vowels. I'll also soften my assumptions for the final segment, though I'm very sure it's a stop.

The third guess is: 
```diff
+ [k]
+ [ɑʊ]
- [l]
- [ɛ]
- [p]
```

Getting closer, but I still don't have many guesses left. I need to change strategies. Looking back on my original assumptions, I thought the third segment was nasal because it was light and had formants. There's one other segment that does that in English: [h]. For the final segment, it really does look like voicing in the closure, I don't know why I was so quick to discount that. I'll go back and guess [d] since I still don't see bilabial transitions in the formants. The only English word that has those for segments in that order is "cowherd." I like that because it agrees with my older beleif that the unstressed vowel is centralized.

My fourth guess is 

```diff
+ [k]
+ [ɑʊ]
+ [h]
+ [ɚ]
+ [d]
```

Woohoo!

### Step 6: Postmorterm

Why didn't I see the schwar in the fourth segment? Well, for rhoticity I would want to look at F3. But F3 isn't really doing anything interesting in this segment. I think it's too short to see the wiggly pattern I associate with rhotics on F3.
