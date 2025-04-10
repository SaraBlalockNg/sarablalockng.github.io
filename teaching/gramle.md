---
layout: page
title: Gramle Breakdown
sidebar_link: false
toc: true
---

# Date Navigation
{:.no_toc}

* Placeholder for Table of Content (Must not be removed)
{:toc levels="1"}

# April 10, 2025

## Original Spectrogram

![Original](gramle-pics/041025.png "Segmentation")

## Step 1: Segmentation

Unlike yesterday, I am quite confident in the segmentation here. We have a strong pattern of changes in formant transition and another strong pattern of changes in amplitude of the waveform. From 0 to 80 milliseconds (red), there is low amplitude and no visible formants. Then from 80 to ~225 ms (orange), we have our highest amplitude in the waveform for this word, with clear formants. From 225-250 ms (yellow), the amplitude does a steep drop off. The formants are still visibe, but faint, and there's some zeros visible between the formants. From 250-350 ms (green), we no longer see formants, but a aperiodic pattern with concentrated frequencies. Finall from 350-475 ms, we have a medium amplitude sound with very visible formants.

![Segmentation](gramle-pics/041025-segmentation.png "Segmentation")

## Step 2: Voicing

There is prevoicing of the first segment, which persiss until ~ 300ms, drops, and picks back up by the 350 ms point. I suspect that because the voicing doesn't persist through the entirely of the centeral turbulent segment, that that segment is not actually voiced but that the voicing bar is bleed-over from the previous segment. This could even be true for the short segment before this one as well.

![Voicing](gramle-pics/041025-voicing.png "Voicing")


## Step 3: Manner of Articulation

The combination of prevoicing, a visible release burst in the waveform, and a short VOT make me very certain that the first segment is a voiced stop, one of [b], [d], or [g]. The visible formants, amplitude and length of the second segment look like a stressed vowel, possibly a diphthong. The third segment is tricker. We want something that has visible formants, low amplitude, and short. I'm thinking either a nasal, an [h], or an [l]. This is phonotactically a weird place for [h], so let's zoom in on nasals and l. The fourth segment is clearly some kind of fricative. It has a high concentration of energy in the higher frequencies, towards 5000 Hz, with a white gap in the lower frequencies. If I combine this information with the voicing hypothesis above, I think we're looking at [s]. For the final segment, the visible formants and low amplitude make this an unstressed vowel. There is glottal pulsing consistent with word-final creaky voicing, but I don't think that's a good hint about the specific vowel we're dealing with. 

![Manner](gramle-pics/041025-manner.png "Manner of Articulation")

## Step 4: Formants

The place of artculation of the first segment is going to be determined by the formants of the vowel after it.  For [b] I would expect formant lowering toward the release, which I can definitely see in F3 and F4, and I can convince myself of for F1. For the alveolar the transitions are more dependent on the quality of the following vowel, so I'll ignore that unless I need it. For [g], I would want to see velar pinch between F2 and F3, but there's a huge gap between F2 and F3 here.

For the stressed vowel, it looks like F1 is on the high end of the range and fairly consistent, so I think we're looking for a mid-low or low vowel. F2 shows a transition for 1200-2000 Hz. Part of that is the velarization I think, but could also mean a frontward-trending diphthong. The diphthongs with a low or midlow nucleus are [aɪ], [aʊ], [ɔɪ], and [oʊ]. Of those, [aɪ] and [ɔɪ] move frontward.

Let's look at the transitions toward the third segment. After a vowel, I would expect an [l] to be velarized. We do see velar pinch here, so that's good evidence that this is likely [l] or [ŋ]. The rise of F2 is inconsistent with a presentation of a bilabial like [m], so I'm eliminating that candidate. Diverving F1 and F2 is possible for alveolars like [n], but again is depending on preceding vowel quality so I don't want to consider that right away.

For the fifth segment, there's a lot of movement in the formants, especially F3. The could mean that this sound is rhotic, like schwar [ɚ]. F1 is relatively high and F2 decreases through its range. I don't have any strong hypothesis about this vowel quality. I might save that for phonotactics when I have more information

![Formants I](gramle-pics/041025-formants1.png "Formants I")

## Step 5: First Guess

My first guess is 

```diff
+[b]
-[ɔɪ]
-[l]
![s]
-[ɚ]
```
## Step 6-?: Revision

Wow, that is so confusing. I was really confident in my segmentation, but it looks like [s] has got to be the third segment. That means that little blip in amplitude that I thought was a velarized [ɫ] is actually just change in amplitude, and the final segment has got to be split in two. If there isn't velar pinch in the second segment, that means that shape is really just being caused by increasing F2, so I'd better keep going with diphthongs. For the final sonorant region, I'm guessing that the division happens when the glottal pulsing starts to widen. If I look at the first half, we've got mid-high F1 and mid-high F2, and it's really short and low amplitude. It could be something like an approximant, [j] or [w]? I'd want formants that look like [i] or [u], and neither pattern really fits my expectations. The second half has very high F1, and mid F2. It's also short, but maybe that's more about position and not quality.

My second guess is 

```diff
+[b]
+[aɪ]
+[s]
-[w]
-[eɪ]
```

On the right track! I am seeing in hindsight how my <way> syllable at the end of that guess was more based on knowledge of English and ignored the lack of evidence for those phones. A lesson in how to not be over-confident.  I'll step back here. I need two sonorants, the second of which someone is likely to creak at the end of a word. 

Sonorants:
* nasals - [m] [n] [ŋ]
* vowels
* liquids - [ɹ] [ɾ] ~~[l]~~
* other approximants - ~~[w]~~ [j]

The easiest permutations to go through are either [vowel] [consonant] or [consonant] [vowel]. I'll start with those and see if I can't think of a word

### Consonant-Vowel Permutations

[baɪsm-]
[baɪsn-]
(ŋ phonotactically impossible)
[baɪsɹ-]
(ɾ phonotactically impossible)
[baɪsj-]

### Vowel-Consonant Permutations
[baɪs-m]
[baɪs-n] - <bison>?
[baɪs-ŋ]
[baɪs-ɹ]
(ɾ phonotactically impossible)
(j phonotactically impossible)

My third guess is 

```diff
+[b]
+[aɪ]
+[s]
-[ə]
-[n]
```
Rats. Okay so it's a vowel-vowel permutation.

### Vowel-Vowel Permutations
[baɪsi-]
[baɪsɪ-]
[baɪsɛ-]
[baɪsæ-]
[baɪsa-]
[baɪsoʊ-]
[baɪsʊ-]
[baɪsu-]
[baɪsaʊ-]

I really can't think of anything, so I need to backtrack. Originally, I though this sound had a relatively high F1, and a high but decreasing F2. Since it's short I think it's a monophthong, so maybe that's [ɛ]. The only English word I can think of with that form is <bicep>, but where's the [p]? It could be unreleased, but I also don't see a closure. I guess I could be convinced that that little blip in the waveform is a closure., and that the line at 510 ms is a baby release.

![Second Stop](gramle-pics/041025-second-release.png "Second Stop")

My fourth guess is 

```diff
+[b]
+[aɪ]
+[s]
+[ɛ]
+[p]
```
Woohoo!

## Step 7: Postmortem

Again, led astray on the segmentation. I think what I learned from this day's exercise is that it's better to rely on the spectrogram and not play the lexical ``game'' part of Gramle until the very bitter end. I also learned that I need to keep in mind that visual patterns are harder to see at the end of words, where we tend to have things like low amplitude, creak, devoicing, and deletion change the visible patterns. My revisionist segmentation is below.

![Resegmentation](gramle-pics/041025-resegmentation.png "Resegmentation")

# April 9, 2025

## Original Spectrogram

![Original](gramle-pics/040925.png "Segmentation")

## Step 1: Segmentation

Segmentation is really tricky for this one. We've got a very very sonorant word, where formants are clear and transition smoothly throughout almost the entirety of the word. There does seem to be a short region right at the beginning where you can see a burst-like pattern in the waveform, and a lot of whitespace in the spectrogram. The next division I'm giving in orange is based off of the zeroing between what looks like F3 and F4, which we don't see in the region in yellow. There's more zeroing between F2 and F3 in the green region, and a lower amplitude in the waveform there as well. In the blue region, we see the amplitude increase, and the zeros go away. The final phone being very long is consistent with end of word behavior, but I will stay curious about this segmentation. One thing I will keep in mind is whether the aperiodic sound after the blue region is background noise (which is my current hypothesis) or some kind of turbulent consonant, like an [h] or a fricative.

![Segmentation](gramle-pics/040925-segmentation.png "Segmentation")


## Step 2: Voicing

Easy. I think everything is voiced here. We can clearly see the voicing bar in the first segment, and there's no sign of it going away.

![Voicing](gramle-pics/040925-voicing.png "Voicing")

## Step 3: Manner of Articulation

For the first segment, the short voicing bar and release shape in the waveform really make this look like a voiced stop in English. Now, for the rest of the word. With highly sonorant sounds, manner of articulation can only be a couple of things. We're looking for vowels, approximants, and nasals primarily. I think the 3rd and 5th segments are probably vowels based on their placement, amplitude, and lack of zeroing. The 5th segment I think is long enough that it could be a closed rime as well, maybe like [ɚ]. The zeros in the 2nd and 4th segment make me think that these could be nasals. It's also possible that they are approximants like [l] or [ɹ] given how vowel-like they are; I think phonotactics will be a good help for figuring that out.

![Manner](gramle-pics/040925-manner.png "Manner of Articulation")

## Step 4: Formants

The formants are tricky in this one two. Either F1 is very low, near the voicing bar, or extremely high. I think this last option is implausible based the how high the formant that starts at 1000 Hz ends up in the 5th segment. Since it goes between 800 and 2000 Hz, I think that's gotta be F2. 

![Formants I](gramle-pics/040925-formants1.png "Formants I")

For the second segment, I don't see any strong formant patterns. F1, F2, and F3 are all very low and fairly stable. There is a little dip in F3 and a little rise in F2, but they're subtle. That makes me think that this is an alveolar sound, like [n], [l], or [ɹ]. For the fourth segment, F1, and F2 are low but F3 is quite high. There's also a dip in F2, and it's hard to see what's happening in F1. Since F2 and F3 are nowhere near each other we can rule out a velar place of articulation. I wonder in the pitch in F3 is being caused by [l] here, which can have zeros but also I've noticed can have weird qualities in the higher formants.

![Formans II](gramle-pics/040925-formants2.png "Formants II")

For the segments I'm calling vowels, our first vowel has a low F1 and F2 and is pretty short. I think we're looking at a monophthong, in the top right of the vowel space. For the second vowel, F1 is a little higher, and F2 makes a transition for the lower third of its frequency range up towards F3. F3 also seems like it's taking a subtle drop. This could mean it's a diphthong that gets fronter, like [aɪ] and [ɔɪ], but those I would expect to have higher F1s that get lower.

![Formants III](gramle-pics/040925-formants3.png "Formants III")

## Step 5: First Guess

I'm gonna be brave and try a real word for my first try

My first guesses are: 
```diff
- [b]
! [l]
! [u]
- [m]
- [ɚ]
```
## Step 6-?: Revision

The placement issue on my first guess makes me think my segmentation may have been off. What if there esn't really a stop segment at the beginning? The only other options are [d] and [g]. Since it's short and probably next to an approximant, I think [g] is more likely (I think [d] would induce some frication that I don't see). I can also almost be convinced of velar pinch between F2 and F3. I'm guessing that the [l] is that central segment with the zeros between F2 and F3 now. But is it the third or fourth segment? I'll stick with my segmentation for my second guess, but the placement of [u] at the end of a word is pretty phonotactically weird.

My second guess is:
```diff
- [g]
! [ɹ]
- [ə]
! [l]
! [u]
```

Ugh. Okay. That [l] has gotta be the center segment, so it's going third this time. For the rest, I'm feeling very pessimistic about the segmentation What if the rime at the end has a nasal instead of a rhotic? [ŋ] could explain why F2 and F3 are so close at the end, and the [ɪ] vowel would explain the increase in F2. I'll just put the rest of the known segments in a phonotactically plausible position and see what happens.

My third guess is

```diff
+ [ɹ]
+ [u]
+ [l]
+ [ɪ]
+ [ŋ]
```

Woohoo!

## Step 7: Postmortem

I really let myself get led astray by a bad segmentation, really caused by putting too much faith in a little bit of prevoicing. And then got excited by the chance that I might be able to guess a word straightaway. In hindsight, the formant transition for the \<ing\> portion of the word are really clear: Low F1, increasing F2, and a close F2 and F3 by the end. With the new segmentation in mind (and that pesky hindsight), it's a lot easier to see what's going on.

![Resegmentation](gramle-pics/040925-resegmentation.png "Resegmentation")


# April 8, 2025

## Step 1: Segmentation

At first pass, the segmentation for this gramle seems pretty straightforward. 
In the first region (red) we see aperiodic sound, evenly distributed acros the visible frequencies, with no strong formants.
In the second region (orange) we see strong formants, very periodic waveform, with a transitory F2.
From the second to the third region (yellow), there is a noticible dropoff in overall intensity (much lighter spectrogram). The formants are still visible but are much lighter.
The intensity of the waveform picks back up in the fourth region (green) and we can see regular formant patterns, but this is a quieter sound than the second region.
The last region (blue) has a two-pattern temporal sequence. First, there's what looks to be a complete closure. Then we see a release of that closure into aperiodic sound.
While this has two specific patterns in the spectrogram, it is still consisten with a single phone. We'll see this next.

![Segmentation](gramle-pics/040825-segmentation.png "Segmentation")

## Step 2: Manner of Articulation

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
 
## Step 3: Voicing

To check for voicing on each segment, I am looking for a voice bar in the bottom of the spectrogram at a reasonable frequency for this speaker. The recordings for gramle come from the MALD database (Tucker et al. 2019), which are made by an adult Canadian male. It looks like theres consistent voicing throughout the entirety of the word up until the final release. Before 50 ms, it's hard to tell whether there's actually voicing or if it's just aperiodic noise in all frequencies including and overlapping with voicing frequencies. For now, I'll say that everything is voiced except maybe the first segment.

![Voicing](gramle-pics/040825-voicing.png "Voicing")

## Step 4: Formants

We should consider the formant ranges that ought to be associated to different vowel qualities, within the context of adult Canadian male speech. Formants will also be helpful in figuring out the place of articulation of the consonants.

For the first vowel, it looks like F1 is around 600-800 Hz, which is quite high. So I suspect this is a low vowwel. F2 goes from about 1800 Hz to 1200 Hz, really spanning the range for this speaker. This may mean it's a diphthong that goes from a front nucleus to a back offglide. The other option is that this quality is influenced by the sounds around it. If we look at F3, I can see something that looks like velar pinch between F2 and F3, though it's subtle. This could mean that the sound that comes before this vowel is velar, like a [k].

![Formants of vowel 1](gramle-pics/040825-formants1.png "Formants of Vowel 1")

The formants of the nasal are pretty boring. They transition smoothly between the vowels. If we were dealing with a bilabial nasal [m], I would expect all the the formants to dip down towards the nasal. For the velar nasal [ŋ], I'd wanna see velar pinch. And I don't see either of these.

![Formans of nasal](gramle-pics/040825-formants2.png "Formants of Nasal")

The formants of the unstressed vowel show a little bit of transition on either end, but are pretty horizontal. It looks like F1 is keeping around 500 Hz, and F2 is around 1500 Hz. I think for this speaker those are both middle of the pack ranges. The is a little scoop of F2 right at the end, which again may point to the sound after this vowel being velar.

![Formants of vowel 2](gramle-pics/040825-formants3.png "Formants of Vowel 2")

## Step 5: First guess

My first guesses are: 
```diff
+ [k]
- [a]
- [n]
- [ə]
- [g]
```
## Step 6-?: Revision

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

Getting closer, but I still don't have many guesses left. I need to change strategies. Looking back on my original assumptions, I thought the third segment was nasal because it was light and had formants. There's one other segment that does that in English: [h]. For the final segment, it really does look like voicing in the closure, I don't know why I was so quick to discount that. I'll go back and guess [d] since I still don't see bilabial transitions in the formants. The only English word that has those segments in that order is "cowherd." I like that because it agrees with my older belief that the unstressed vowel is centralized.

My fourth guess is 

```diff
+ [k]
+ [ɑʊ]
+ [h]
+ [ɚ]
+ [d]
```

Woohoo!

## Step 7: Postmorterm

Why didn't I see the schwar in the fourth segment? Well, for rhoticity I would want to look at F3. But F3 isn't really doing anything interesting in this segment. I think it's too short to see the wiggly pattern I associate with rhotics on F3.
