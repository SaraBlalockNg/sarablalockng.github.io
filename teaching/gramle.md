---
layout: page
title: Gramle Breakdown
sidebar_link: false
toc: true
toc_min_header: 1
toc_max_header: 1
---

* Placeholder for Table of Content (Must not be removed)
{:toc}

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
