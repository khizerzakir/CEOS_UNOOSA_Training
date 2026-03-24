---
title: Slides
---

<link rel="stylesheet" href="assets/site.css">

<div class="top-nav">
	<a href="index.md">Home</a>
	<a href="tutorial.md">Tutorial</a>
	<a href="slides.md">Slides</a>
</div>

# Presentation

Use the slide deck for the lecture part of the session, then switch to the notebook for the hands-on walkthrough.

<div class="actions">
	<div class="action-card">
		<strong>Download slides</strong>
		<a href="assets/cubo_xarray_dask_presentation.pptx">PowerPoint deck (.pptx)</a>
	</div>
	<div class="action-card">
		<strong>Google Slides</strong>
		<a href="https://docs.google.com/presentation/d/1MbLCZl65a0RlgKDsKgOieQ-J4rfpf8Mx/edit?usp=sharing&ouid=106019696090715174142&rtpof=true&sd=true">Google Slide Deck</a>
	</div>
	<div class="action-card">
		<strong>Open tutorial page</strong>
		<a href="tutorial.md">Go to tutorial overview</a>
	</div>
	<div class="action-card">
		<strong>Run notebook in Colab</strong>
		<a href="https://colab.research.google.com/github/khizerzakir/github_pages_cubo_tutorial/blob/main/cubo_xarray_dask_tutorial.ipynb" target="_blank" rel="noopener">Launch cubo tutorial in Colab</a>
	</div>
</div>

## View slides on this page

<div class="slide-embed">
	<iframe
		src="https://view.officeapps.live.com/op/embed.aspx?src=https%3A%2F%2Fkhizerzakir.github.io%2Fgithub_pages_cubo_tutorial%2Fassets%2Fcubo_xarray_dask_presentation.pptx"
		width="100%"
		height="620"
		frameborder="0"
		title="Embedded PowerPoint"
	></iframe>
</div>

<div class="inline-note">
	Use the built-in left/right arrows inside the embedded viewer to navigate slides.
</div>

## Slides swiper

<div class="png-swiper" id="png-swiper">
	<button class="swiper-btn" id="swiper-prev" aria-label="Previous image">&#10094;</button>

	<div class="swiper-stage">
		<img class="swiper-slide is-active" src="assets/gode_africa.png" alt="gode_africa">
		<img class="swiper-slide" src="assets/ban_asia.png" alt="ban_asia">
		<img class="swiper-slide" src="assets/montage.png" alt="montage">
		<img class="swiper-slide" src="assets/montage2.png" alt="montage2">
	</div>

	<button class="swiper-btn" id="swiper-next" aria-label="Next image">&#10095;</button>
</div>

<div class="inline-note" id="swiper-status">Image 1 of 4</div>

<script>
(function () {
	const root = document.getElementById('png-swiper');
	if (!root) return;

	const slides = Array.from(root.querySelectorAll('.swiper-slide'));
	const prevBtn = document.getElementById('swiper-prev');
	const nextBtn = document.getElementById('swiper-next');
	const status = document.getElementById('swiper-status');

	let index = 0;

	function render() {
		slides.forEach((slide, i) => {
			slide.classList.toggle('is-active', i === index);
		});
		if (status) status.textContent = `Image ${index + 1} of ${slides.length}`;
	}

	prevBtn.addEventListener('click', function () {
		index = (index - 1 + slides.length) % slides.length;
		render();
	});

	nextBtn.addEventListener('click', function () {
		index = (index + 1) % slides.length;
		render();
	});

	render();
})();
</script>

- [Go back to the home page](index.md)
