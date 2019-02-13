---
theme: jekyll-theme-slate
---


# Welcome to Poodle TTS

## ~Jan 2019

### DCTTS

Samples

### Baseline Tacotron

This model is from Google's paper [Tacotron: Towards End-to-End Speech Synthesis](https://arxiv.org/pdf/1703.10135.pdf)

![./image/tacotron.png](Model Architecture of Tacotron)

<figure>
  <figcaption>Tacotron Sample:</figcaption>
  <audio controls><source src="audio/Tacotron/tacotron.wav" type="audio/wav">Your browser does not support the audio element.</audio>
</figure>

### Expressive Tacotron

This model is from Google's paper [Towards End-to-End Prosody Transfer for Expressive Speech Synthesis with Tacotron](https://arxiv.org/pdf/1803.09047.pdf)

![./image/extaco.png](Model Architecture of Expressive Tacotron)

<figure>
  <figcaption>Expressive Tacotron Samples:</figcaption>
  <audio controls><source src="audio/Expressive-Tacotron/kss-1.wav" type="audio/wav">Your browser does not support the audio element.</audio>
  <audio controls><source src="audio/Expressive-Tacotron/kss-2.wav" type="audio/wav">Your browser does not support the audio element.</audio>
  <audio controls><source src="audio/Expressive-Tacotron/ytn-fast.wav" type="audio/wav">Your browser does not support the audio element.</audio>
  <audio controls><source src="audio/Expressive-Tacotron/ytn-mad.wav" type="audio/wav">Your browser does not support the audio element.</audio>
  <audio controls><source src="audio/Expressive-Tacotron/ytn-slow.wav" type="audio/wav">Your browser does not support the audio element.</audio>
</figure>

<figure>
<figcaption>Corresponding Reference Audios:</figcaption>
<audio controls><source src="audio/Expressive-Tacotron/ref/kss-1.wav" type="audio/wav">Your browser does not support the audio element.</audio>
<audio controls><source src="audio/Expressive-Tacotron/ref/kss-2.wav" type="audio/wav">Your browser does not support the audio element.</audio>
<audio controls><source src="audio/Expressive-Tacotron/ref/ytn-fast.wav" type="audio/wav">Your browser does not support the audio element.</audio>
<audio controls><source src="audio/Expressive-Tacotron/ref/ytn-mad.wav" type="audio/wav">Your browser does not support the audio element.</audio>
<audio controls><source src="audio/Expressive-Tacotron/ref/ytn-slow.wav" type="audio/wav">Your browser does not support the audio element.</audio>
</figure>


### Multispeaker Tacotron with Global Style Tokens

<figure>
  <figcaption>Multispeaker Samples:</figcaption>
  <audio controls><source src="audio/GST+Multispeaker/sadder/speaker27+sadder.wav" type="audio/wav">Your browser does not support the audio element.</audio>
  <audio controls><source src="audio/GST+Multispeaker/neutral/speaker5+neutral.wav" type="audio/wav">Your browser does not support the audio element.</audio>
  <audio controls><source src="audio/GST+Multispeaker/neutral/speaker30+neutral.wav" type="audio/wav">Your browser does not support the audio element.</audio>
  <audio controls><source src="audio/GST+Multispeaker/scared/speaker13+scared.wav" type="audio/wav">Your browser does not support the audio element.</audio>
</figure>

<figure>
 <figcaption>Mimic prosody with GST:</figcaption>
 <audio controls><source src="audio/GST+Multispeaker/mimic_prosody/sadder.wav" type="audio/wav">Your browser does not support the audio element.</audio>
 <audio controls><source src="audio/GST+Multispeaker/mimic_prosody/sadder_syn.wav" type="audio/wav">Your browser does not support the audio element.</audio>
</figure>



### Griffin-Lim + WSOLA

<figure>
  <figcaption>Only Griffin-Lim:</figcaption>
  <audio controls><source src="audio/GL+WSOLA/before.wav" type="audio/wav">Your browser does not support the audio element.</audio>
</figure>

<figure>
  <figcaption>With WSOLA postprocessing:</figcaption>
  <audio controls><source src="audio/GL+WSOLA/after.wav" type="audio/wav">Your browser does not support the audio element.</audio>
</figure>

## Feb 2019

### Pitch and Tempo control

<figure>
  <figcaption>Speaker 1 (KSS)</figcaption>
  <audio controls><source src="audio/Pitch+Tempo/slow-low-speaker1.wav" type="audio/wav">Your browser does not support the audio element.</audio>
  <audio controls><source src="audio/Pitch+Tempo/fast-high-speaker1.wav" type="audio/wav">Your browser does not support the audio element.</audio>
</figure>

<figure>
  <figcaption>Speaker 2 (Zeroth)</figcaption>
  <audio controls><source src="audio/Pitch+Tempo/slow-low-speaker2.wav" type="audio/wav">Your browser does not support the audio element.</audio>
  <audio controls><source src="audio/Pitch+Tempo/fast-high-speaker2.wav" type="audio/wav">Your browser does not support the audio element.</audio>
</figure>

### Pausing

<figure>
<figcaption>Spacing</figcaption>
<audio controls><source src="audio/Pause/0-spaces" type="audio/wav">Your browser does not support the audio element.</audio>
<audio controls><source src="audio/Pause/1-space" type="audio/wav">Your browser does not support the audio element.</audio>
<audio controls><source src="audio/Pause/2-spaces" type="audio/wav">Your browser does not support the audio element.</audio>
</figure>

<figure>
<figcaption>Comma</figcaption>
<audio controls><source src="audio/Pause/1-comma" type="audio/wav">Your browser does not support the audio element.</audio>
<audio controls><source src="audio/Pause/2-commas" type="audio/wav">Your browser does not support the audio element.</audio>
</figure>

### Wavenet

## Q2

Data collection and Speaker adaptation

## Q3

Generate text in your own voice! app
