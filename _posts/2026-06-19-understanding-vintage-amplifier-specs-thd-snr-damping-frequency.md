---
layout: post
title: 'Understanding vintage amplifier specs: THD, SNR, damping factor, and frequency'
description: Decode vintage amplifier specifications - learn what THD, damping factor, frequency response, and SNR actually mean for sound.
date: 2026-06-19
image: /assets/images/2026-06-19-understanding-vintage-amplifier-specs-thd-snr-damping-frequency-hero.jpg
tags: [hifi, vinyl, vintage, audio, amplifier]
author: Analog Revivalist
---
*Disclosure: As an Amazon Associate, I earn from qualifying purchases.*

Vintage amplifier specifications read like hieroglyphics to most people. THD, SNR, damping factor, frequency response, impedance - they're listed on spec sheets, but what do they actually mean for the sound you hear? Many collectors assume all specs matter equally. They don't. Some directly impact sound quality. Others are marketing noise.

This guide decodes the specs that matter and explains what they tell you about an amplifier's performance. You'll learn which numbers predict lifespan, which predict sound character, and which you can safely ignore.

![Vintage amplifier measurement and testing setup](/assets/images/2026-06-19-understanding-vintage-amplifier-specs-thd-snr-damping-frequency-hero.jpg)
<p class="image-credit">Photo by <a href="https://unsplash.com/@jakubzerdzicki?utm_source=analogrevivalist&utm_medium=referral">Jakub Żerdzicki</a> on <a href="https://unsplash.com/?utm_source=analogrevivalist&utm_medium=referral">Unsplash</a></p>

## THD: what distortion really means

Total Harmonic Distortion (THD) measures how much the amplifier adds harmonic overtones not present in the original signal. An undistorted 1 kHz sine wave contains only a fundamental 1 kHz component. THD adds second, third, fourth harmonics - 2 kHz, 3 kHz, 4 kHz, etc.

Manufacturers specify THD as a percentage, often at a specific power level and frequency. A common spec: "0.1% THD @ 50W, 20Hz-20kHz." This means at 50 watts output across the audio range, the amplifier adds 0.1% harmonic content.

Here's the critical part: some distortion is inaudible, and some is actually pleasant. Below 0.1% THD, most listeners can't hear the distortion, even on quality speakers. Between 0.1% and 0.5%, the distortion character becomes slightly noticeable but often musically appealing - this is why some people prefer [tube amplifiers](https://www.amazon.com/dp/B07YQ2V2BK?tag=analogrevivalist-20) (which typically run 1-3% THD) to transistor amps (which often run 0.01-0.1% THD). Tube distortion is predominantly second-harmonic, which adds warmth. Transistor distortion is higher-order, which sounds harsh.

Above 0.5% THD, distortion becomes objectively audible - muddy bass, harsh treble, listener fatigue. A vintage amplifier claiming 0.3% THD is likely accurate to that spec and will sound clean and transparent. One claiming 1.5% THD will have a colored character - not bad, just colored. An amp with no THD spec listed should raise a flag: either the manufacturer never measured it, or the number is worse than competitors'.

When shopping for vintage amps, look for THD specs below 0.5%. Higher-than-that specs signal likely issues: either the amp is heavily colored (which might be desired, but should be intentional), or the amp is worn out. A well-serviced 30-year-old amplifier should still meet its original THD spec.

## SNR: signal-to-noise ratio and background silence

Signal-to-Noise Ratio (SNR) measures the difference in level between your music and the noise floor - hum, hiss, and other background garbage. Specifications typically read: "100 dB SNR" or "SNR >90 dB."

A higher number is better. 90 dB SNR is excellent for vintage gear - it means the music is 90 decibels louder than the background noise. At listening volume, you won't hear any hiss between tracks. Below 80 dB SNR, hiss becomes noticeable in quiet passages, especially with sensitive speakers. Below 70 dB SNR, the background noise is distracting.

SNR degrades over time. A 1975 amplifier with a 95 dB SNR spec might measure 85 dB SNR today because electrolytic capacitors have degraded. This is why amplifier recapping (replacing old capacitors) is so common: it restores the noise floor.

Practical advice: if you're considering a used vintage amp, check whether it's been serviced. A recent recap should restore SNR to near-original spec. If it hasn't been serviced in 20+ years, expect SNR to be 5-10 dB lower than factory spec. This is audible as a faint hiss, especially in small rooms with efficient speakers.

Some amplifiers list A-weighted SNR (dB-A) and unweighted SNR. A-weighted SNR ignores frequencies the human ear is less sensitive to, so the number looks better. Unweighted SNR is more honest. Compare apples to apples when cross-shopping amps.

## Damping factor: control over the speaker

Damping factor describes how well the amplifier controls speaker motion after a signal ends. High-frequency transients - drum hits, cymbals, plucks - ring at the speaker's resonant frequency if the amp doesn't actively suppress that ringing. Damping factor quantifies this suppression.

Damping factor is calculated as the speaker impedance (typically 4 or 8 ohms) divided by the output impedance. A spec of "damping factor >100" means the output impedance is less than 0.04 ohms (if 4-ohm speakers). This low impedance allows the amp to quickly stop speaker motion.

In practice, damping factor matters most in the bass. A high damping factor (>50) gives tight, articulate bass - the speaker cone stops moving as soon as the signal ends, preventing boom. Low damping factor (<10) allows the speaker to ring after the signal, adding bass bloom and smear. This can sound pleasant on some music and muddy on others.

Most vintage solid-state amplifiers have damping factors between 20 and 100. Most vintage tube amplifiers have lower damping factors (5-20) because tube output stages have higher output impedance. This is one reason tube amps often sound warmer and more forgiving - the lower damping factor adds some bass bloom naturally.

A damping factor spec under 10 signals a worn output stage (transistor amps) or a design choice toward warmth (tube amps). This isn't bad - just be aware that bass will be less controlled. For critical listening, aim for damping factors >40.

## Frequency response: the audio range covered

Frequency response describes the range of frequencies the amplifier reproduces at consistent volume. A spec of "20Hz-20kHz +/- 3dB" means the amplifier reproduces everything from 20 Hz (lowest bass note humans can perceive) to 20 kHz (highest treble) with less than 3 dB of level variation.

The "+/- X dB" part matters. A narrower tolerance (like +/- 1 dB) means flatter response - what goes in comes out unchanged. A wider tolerance (like +/- 5 dB) means the amp emphasizes or de-emphasizes certain frequencies. De-emphasizing treble would read as "falling off" in the highs, which sounds dull. Emphasizing midrange (as some vintage amps do) makes vocals jump out but adds coloration.

Frequency response limitations are usually at the extremes. A spec like "40Hz-20kHz +/- 3dB" means the amp doesn't amplify strongly below 40 Hz. For turntable listening, this is often fine - vinyl records don't contain much energy below 30 Hz anyway. But for full-range music or modern recordings with extended bass, you want 20 Hz response.

Treble response matters more for subjective tone. An amp rolling off above 15 kHz will sound dull and smooth. One boosted above 12 kHz will sound bright and possibly fatiguing. A flat response from 20 Hz to 20 kHz is ideal for transparency, but many listeners prefer gentle coloration. Be honest about your preference and choose accordingly.

Check frequency response specs carefully. Some manufacturers list the -3dB point without showing the tolerance band, which makes comparison difficult. Request full spec sheets from dealers - asking is free.

## Amplifier design: impedance, power, and supply

**Output impedance and speaker sensitivity.** Output impedance is the amplifier's electrical resistance at the speaker terminals. This spec doesn't often get listed but is crucial for speaker matching. Low output impedance (<0.1 ohms) allows the amp to control speakers predictably. High output impedance (>1 ohm) makes the impedance curve of the speaker part of the amplifier's behavior.

Most solid-state amplifiers have output impedance below 0.1 ohms, so this is rarely an issue. Tube amplifiers often ship with multiple output transformer taps for different speaker impedances (4 ohms, 8 ohms, 16 ohms). Always match the amp tap to your speakers' nominal impedance. Mismatching adds coloration and can damage the amp.

Speaker sensitivity (measured in dB/1W/1M - decibels at 1 meter with 1 watt input) determines how loud the amp must drive to achieve your desired listening level. A sensitive speaker (>90 dB) gets loud with 20 watts. An insensitive speaker (<85 dB) needs 100+ watts to reach the same volume. For vintage speakers, consider [Polk Audio T15 bookshelf speakers](https://www.amazon.com/dp/B002RJLHB8?tag=analogrevivalist-20) that pair well with lower-power tube designs.

**Power output: watts and measurement.** Vintage amplifiers list power in watts, but "watts" can mean different things. RMS watts (continuous power) is what matters - this is what the amp can sustain indefinitely. Peak watts (music power) is a higher, less realistic number. Some manufacturers list only peak watts to fluff specs.

A spec of "50W RMS @ 8 ohms, 20Hz-20kHz, <0.1% THD" is honest and comparable. A spec of "100W music power" is less useful - you don't know the actual continuous output. RMS watts are the standard; always compare using RMS.

For vintage vinyl listening, 20-50 watts RMS is sufficient in most rooms. 50-100 watts gives headroom for occasional peaks without distortion. Above 100 watts, you're paying for power you probably don't need in a living room. The audible difference between 50W and 100W is marginal on quality speakers at normal listening levels.

Channel balance (left vs. right power output) matters, though it's rarely specified. A well-designed amp delivers equal power to both channels. Worn-out amps sometimes show imbalanced channels (one channel 10% louder than the other). This is a red flag for service - get the amp recapped and rebiased before committing.

**Power supply quality and transformer rating.** The transformer is the amplifier's heart. It steps down wall voltage to usable levels and isolates the audio circuits from AC mains. A massive, heavy transformer signals quality design - it indicates less stress on the power supply and lower hum/noise potential.

Transformer weight is a rough proxy for quality. A quality power transformer for 50-100 watts typically weighs 3-8 pounds. A lightweight transformer (under 2 pounds) suggests cost-cutting. This doesn't disqualify an amp - modern designs are more efficient - but it's one data point.

Look for transformers with EI (or C-core) laminations rather than cheaper designs. Quality vintage amplifiers from the 1970s onward nearly always feature proper transformer design. Cheap 1960s portable units sometimes cut corners, resulting in poor power supply regulation and higher hum.

An amp's ability to maintain stable output as voltage sags (brownout) depends on power supply regulation. This isn't usually specified, but it's audible: a poorly regulated amp sounds congested and compressed when input voltage drops (as happens on summer afternoons). A well-regulated amp sounds consistent.

## How to evaluate a vintage amplifier: step-by-step

Evaluating a vintage amplifier before purchase requires systematic checks against its specification sheet. Follow this process to determine if an amp is worth buying:

1. **Gather the original spec sheet.** Find the manufacturer's original specifications - ask the seller, check online resources like [AudioKarma](https://www.audiokarma.org/) or [Vintage Audio resources](https://www.vintagewhatnot.com/), or search the model number. Write down the factory-rated THD, SNR, damping factor, frequency response, and RMS power. These become your benchmark.

2. **Check for service history.** Ask the seller whether the amp has been recently serviced, recapped, or rebiased. An amp serviced within 5 years is likely close to original spec. One that hasn't been serviced in 20+ years should be evaluated carefully - expect degraded SNR and possibly increased THD.

3. **Measure or request measurements.** Many audio repair shops offer affordable testing ($50-100) to measure current THD, SNR, frequency response, and damping factor. This is the most reliable evaluation method. If the amp measures within 10% of original spec, it's in good shape. More than 20% drift signals aging or issues. Be aware of common pitfalls when interpreting specs: don't confuse THD with noise (they're different), don't assume higher watts always means better sound (a 100-watt poorly-designed amp sounds worse than a 50-watt well-designed amp), and always check the measurement context (0.05% THD at 1 watt differs significantly from the same spec at 50 watts).

4. **Listen for noise and distortion.** Power on the amp in a quiet room and listen for hum (60 Hz buzz) or hiss (faint white noise). These indicate transformer hum or degraded capacitors. Play vinyl at normal volume and listen for harshness or compression - signs of distortion or power supply sag. Your ears should confirm that measurements tell a positive story.

5. **Check channel balance.** Using [a handheld audio signal generator](https://www.amazon.com/dp/B0015VARFG?tag=analogrevivalist-20) or music you know well, verify that both speakers play at similar volume. If one channel is noticeably louder, the amp likely needs rebiasing or channel balance adjustment.

6. **Evaluate impedance matching.** Confirm the amp's output impedance specification and speaker sensitivity together. A 20-watt tube amp matches well with 90dB-sensitive vintage bookshelf speakers; the same amp struggles with modern 85dB-sensitive floor speakers. Match the pair carefully.

7. **Factor in repair costs.** If the amp measures poorly, get an estimate for service work (typically $200-400 for recapping and rebiasing). Quality [electrolytic capacitor assortment kit](https://www.amazon.com/dp/B07PBQXQNQ?tag=analogrevivalist-20) and replacement components are affordable and widely available. Add service costs to the purchase price to calculate true cost. A $400 amp needing $300 service costs $700 total - compare that to other options.

This process transforms spec sheets from abstract numbers into actionable information about whether a specific amp is a good investment.

When interpreting specs critically, remember: an amplifier can be low-THD but high-noise (or vice versa), so don't confuse these different measures. Trust specs only within their measurement context - always check whether THD was measured at 1 watt or 50 watts, at what frequency. And recognize that a 50-year-old spec sheet assumes fully functional capacitors; those same capacitors are degraded today, so real performance is worse than written. Use specs to set a minimum threshold: stay above 80 dB SNR, below 0.5% THD, and with damping factor >20. Within those bounds, pick the amp whose sound appeals to you. Specs eliminate the obviously broken gear; your ears make the final call.

Vintage amplifiers are also generally over-spec'd by modern standards. A 30-year-old 50-watt amp will typically measure better than a cheap modern 50-watt amp, because the vintage unit was engineered with analog circuitry and quality components throughout. Digital switching power supplies are efficient but noisier. Vintage transformer-based supplies are heavier and less efficient but quieter.

## Troubleshooting: Common Mistakes When Reading Specs

Even experienced vintage audio enthusiasts stumble when interpreting amplifier specifications. Here are the most frequent mistakes:

**Confusing THD at different power levels.** A spec sheet might list "0.05% THD @ 1W" and "0.3% THD @ 50W." These are the same amplifier at different operating points. THD increases at higher power outputs; comparing only the lower number is misleading. Always check the measurement context and compare apples to apples.

**Assuming higher specs always mean better sound.** A 100-watt amplifier with poor power supply regulation will sound worse than a 50-watt amp with excellent regulation. Raw wattage is only one variable. A poorly designed 100W amp compressed and distorted at moderate listening levels will sound worse than a well-engineered 30W amp running clean.

**Ignoring measurement conditions and frequency.** THD can vary dramatically across the frequency spectrum. An amp might measure 0.1% THD at 1 kHz but 0.5% at 20 Hz or 20 kHz. Request spec sheets that show THD across multiple frequencies, or assume the worst-case scenario applies across the range.

**Not accounting for age and capacitor degradation.** Comparing a 1980 amp's original 95 dB SNR spec to today's measurement of 82 dB SNR and concluding the amp is failing is incorrect. Capacitor aging explains the 13 dB difference. Plan on 5-15 dB SNR degradation in unserviced vintage gear. This doesn't mean the amp is bad - it means the aging is expected and predictable.

**Mixing RMS watts with peak watts.** Advertisements sometimes conflate "100W music power" with "100W RMS" to mislead buyers. Music power (peak watts) can be 2-3 times higher than RMS watts. Always verify you're comparing RMS-to-RMS when evaluating power output between amplifiers.

**Overlooking measurement context - impedance and frequency range.** A spec of "0.1% THD @ 8 ohms" is not the same as "0.1% THD @ 4 ohms." Driving 4-ohm loads increases THD. Similarly, frequency response specs sometimes exclude the extremes - check whether "20Hz-20kHz" includes ±3dB limits or is just stated as a marketing range.

**Assuming missing specs mean the amp is broken.** Vintage amplifiers from the 1960s often lack comprehensive spec sheets because manufacturers didn't publish all measurements. Missing specs don't indicate failure. However, if a modern amplifier has no published specs, that's a red flag - modern manufacturers always publish specs, so absence suggests hidden poor performance.

When evaluating a vintage amp, cross-reference specs against [audio test and measurement references](https://www.amazon.com/dp/0980622395?tag=analogrevivalist-20) and service manuals. These resources provide context and reveal what specifications truly matter for the amp you're considering. Getting measurements done by a professional audio shop eliminates guesswork entirely.

## FAQ

**Q: Does a vintage amp spec of 1% THD mean it will sound obviously colored?**

A: Not necessarily. One percent THD is at the edge of audibility for most listeners. If the distortion is predominantly even-order (second harmonic), it adds pleasant warmth. If it's odd-order (third, fifth harmonics), it adds harshness. A tube amp at 1% THD with even-order distortion sounds warmer than audibly colored. The same spec in a solid-state amp usually sounds neutral because solid-state generates less even-order distortion.

**Q: Should I prioritize damping factor or output impedance when shopping?**

A: They're related - lower output impedance means higher damping factor. Focus on output impedance if it's listed (aim for <0.1 ohms). If only damping factor is listed, aim for >40 with solid-state amps or >20 with tube amps.

**Q: What happens if I use an amp with a 40Hz frequency response with a turntable?**

A: You lose very little. Vinyl records have minimal energy below 40Hz, so the amp's lack of response at 20-40 Hz won't affect most music. You might lose a tiny bit of kick drum deepness on some recordings, but most listeners won't notice. This is fine for vinyl-only systems.

**Q: Can an old amplifier's specs have drifted over time?**

A: Yes, especially SNR and THD. Capacitor degradation increases noise floor and adds slight distortion. A 1980 amp with a 95 dB SNR spec might measure 85 dB today. THD might increase from 0.1% to 0.2-0.3%. None of this usually matters audibly, but if you're buying vintage gear, factor in that specs are probably slightly worse than advertised.

**Q: Is frequency response flatness more important than bandwidth?**

A: For vinyl listening, they're equally important. A flat response from 20Hz-20kHz (within +/- 1dB) is ideal. An amp with a 30Hz-20kHz response that's only +/- 0.5dB is probably better than one spec'd as 20Hz-20kHz +/- 3dB. Look at both numbers together.

**Q: Should I be concerned about an amp with no published specs?**

A: Yes, unless it's a rare vintage unit where the manufacturer never published specs. If modern gear has no published specs, that's suspicious - it usually means the manufacturer is hiding poor performance. For vintage units, missing specs just reflect old documentation practices.

### Specs and reliability

Beyond sound, specs predict longevity. An amplifier measuring to original spec after 40 years has a good design and has been maintained. One measuring significantly below original spec needs service (likely capacitor replacement and bias adjustment).

When evaluating a used vintage amplifier, invest in testing. Many audio shops offer affordable testing - they'll measure THD, SNR, and damping factor against the original spec. This costs $50-100 but tells you if the amp is worn out or ready for another 20 years of life. Consider purchasing [a Fluke true-RMS digital multimeter](https://www.amazon.com/dp/B00NSD6VA4?tag=analogrevivalist-20) if you plan to evaluate multiple units yourself - it helps verify basic voltage and impedance readings. Quality [oxygen-free copper speaker wire](https://www.amazon.com/dp/B00APEG9M4?tag=analogrevivalist-20) also matter when connecting evaluated amps to test speakers, as poor cables can mask or add coloration.

Read the specs with a critical eye: they're a tool, not gospel. A well-engineered vintage amplifier with modest specs (0.3% THD, 85 dB SNR) will outperform a modern bargain amp with impressive-looking numbers. Specs matter, but context matters more.

---

<div class="author-bio">
  <p><strong>About the Author</strong></p>
  <p>The Analog Revivalist team researches vintage audio restoration, drawing on service manual documentation, technician community knowledge, and comparative equipment reviews. Our guides focus on what the evidence supports - not just received wisdom.</p>
</div>

**Subscribe for more:** Spec decoding guides and equipment reviews appear every Monday, Wednesday, and Friday.

**Related reading:**
- [Vintage integrated amplifier buying guide](/2026/03/24/vintage-integrated-amplifier-buying-guide/)
- [Vintage receiver guide: what to look for on the used market](/2026/03/30/vintage-receiver-guide-used-market/)