---
layout: default
title: "CROSS-DOMAIN AUDIO WATERMARKING FOR REAL-WORLD APPLICATIONS"
---

# CROSS-DOMAIN AUDIO WATERMARKING FOR REAL-WORLD APPLICATIONS

<p class="authors">
	Ruolan Leslie Famularo &nbsp;&nbsp;
	Jianbo Ma<sup class="author-note">*</sup> &nbsp;&nbsp;
	Andrea Fanelli
</p>

<p class="affiliation">
	ATG, Dolby Laboratories
</p>

## Abstract

Audio content provenance calls for watermarks that survive common edits while remaining imperceptible in high-fidelity audio. Existing models are vulnerable to alignment-shifting cropping transforms and neural resynthesis such as neural vocoders. In this paper, we propose XDomainMark, where we introduce a cross-domain embedder and detector, with the embedder operating on time-domain data, and detector on frequency-domain data. We pair this with an audio activity detection module to further suppress audible artifacts. Evaluations on two datasets of varied fidelity and audio content show substantial gains in watermark robustness after cropping and vocoder attacks, and perceptual transparency was observed in objective scores and subjective listening results. Additionally, ablations show that the cross-domain design is crucial for the success on vocoder attacks. These results highlight the potential to separate signal representations in the embedder and detector while jointly training them with shared information.

## Audio Samples

<div class="sample-list">
	<section class="audio-sample" aria-labelledby="sample-044">
		<h3 id="sample-044">Sample 044 (Music) </h3>
		<div class="audio-grid">
			<div class="audio-option">
				<h4>Reference</h4>
				<audio controls preload="metadata"><source src="{{ '/assets/audio/044-Reference.wav' | relative_url }}" type="audio/wav"></audio>
			</div>
			<div class="audio-option">
				<h4>AudioSeal</h4>
				<audio controls preload="metadata"><source src="{{ '/assets/audio/044-AudioSeal.wav' | relative_url }}" type="audio/wav"></audio>
			</div>
			<div class="audio-option">
				<h4>XAttnMark</h4>
				<audio controls preload="metadata"><source src="{{ '/assets/audio/044-xAttnMark.wav' | relative_url }}" type="audio/wav"></audio>
			</div>
			<div class="audio-option">
				<h4>XDomainMark (Ours)</h4>
				<audio controls preload="metadata"><source src="{{ '/assets/audio/044-XDomainMark.wav' | relative_url }}" type="audio/wav"></audio>
			</div>
		</div>
	</section>

	<section class="audio-sample" aria-labelledby="sample-013">
		<h3 id="sample-013">Sample 013 (Environmental Sounds)</h3>
		<div class="audio-grid">
			<div class="audio-option">
				<h4>Reference</h4>
				<audio controls preload="metadata"><source src="{{ '/assets/audio/013-Reference.wav' | relative_url }}" type="audio/wav"></audio>
			</div>
			<div class="audio-option">
				<h4>AudioSeal</h4>
				<audio controls preload="metadata"><source src="{{ '/assets/audio/013-AudioSeal.wav' | relative_url }}" type="audio/wav"></audio>
			</div>
			<div class="audio-option">
				<h4>XAttnMark</h4>
				<audio controls preload="metadata"><source src="{{ '/assets/audio/013-xAttnMark.wav' | relative_url }}" type="audio/wav"></audio>
			</div>
			<div class="audio-option">
				<h4>XDomainMark (Ours)</h4>
				<audio controls preload="metadata"><source src="{{ '/assets/audio/013-XDomainMark.wav' | relative_url }}" type="audio/wav"></audio>
			</div>
		</div>
	</section>

	<section class="audio-sample" aria-labelledby="sample-003">
		<h3 id="sample-003">Sample 003 (Speech and Noise)</h3>
		<div class="audio-grid">
			<div class="audio-option">
				<h4>Reference</h4>
				<audio controls preload="metadata"><source src="{{ '/assets/audio/003-Reference.wav' | relative_url }}" type="audio/wav"></audio>
			</div>
			<div class="audio-option">
				<h4>AudioSeal</h4>
				<audio controls preload="metadata"><source src="{{ '/assets/audio/003-AudioSeal.wav' | relative_url }}" type="audio/wav"></audio>
			</div>
			<div class="audio-option">
				<h4>XAttnMark</h4>
				<audio controls preload="metadata"><source src="{{ '/assets/audio/003-xAttnMark.wav' | relative_url }}" type="audio/wav"></audio>
			</div>
			<div class="audio-option">
				<h4>XDomainMark (Ours)</h4>
				<audio controls preload="metadata"><source src="{{ '/assets/audio/003-XDomainMark.wav' | relative_url }}" type="audio/wav"></audio>
			</div>
		</div>
	</section>
</div>

## Detailed Results

For detailed results, please refer to the [results page]({{ '/results/' | relative_url }}).


<p class="author-footnote">
	* Jianbo Ma contributed to this work while at Dolby Laboratories and is now at Canva Research.
</p>