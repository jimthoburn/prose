---
title: Sierra High School, Bringing aspiration into reality
layout: default
has_wide_content: true
image: "/images/photos/one-student-art.png"
image_focus: bottom
images:
- "/images/photos/one-student-academics.png"
- "/images/photos/one-student-art.png"
- "/images/photos/one-student-book.png"
- "/images/photos/one-student-computer.png"
- "/images/photos/one-student-microscope.png"
- "/images/photos/one-student-science.png"
images_reverse:
- true
- false
- true
- false
- true
- false
---

<style>
/*
body > main::before {
  content: "";
  background-color: white;
  height: 1.5em;
  width: 120%;
  margin-top: -2.25em;
  position: absolute;
  z-index: 3;
  left: -10%;
  transform: rotate(-2deg);
}
  @media (min-width: 60em) {
    body > main::before {
      margin-top: -4.5em;
      height: 3em;
    }
  }

*/
body {
  background-color: rgb(244, 209, 81); /* --gold */
  background-color: rgb(237, 237, 239);
}
body > main::before,
body > main {
  background-color: rgb(244, 209, 81); /* --gold */
  background-color: rgb(237, 237, 239);
}
/*
body > .image {
  background-color: rgb(237, 237, 239);
  background-image: url(/images/athletics.jpg);
  background-position: center;
  background-size: cover;
}
*/
body > .image {
  background-color: rgb(46, 127, 182); /* --ocean */
  background-color: white;
  background-color: rgb(244, 209, 81); /* --gold */
  background-color: rgb(237, 237, 239);
  /*
  transform: skew(0, -2deg) translate(0, -5vh);
  */
  height: 10em;
  min-height: 65vh;
}
/*
body > .image img {
  transform: skew(0, 2deg) translate(0, 5vh);
}
*/
body > .image::before,
body > .image::after {
  display: none;
}
body > .image img {
  height: auto;
  width: 50%;
  position: absolute;
  top: 30vh;
  right: -2.25em;
  z-index: 9999;
}

body.image-reverse > .image img {
  left: 0.75em;
}
@media (min-width: 60em) {
  body.image-reverse > .image img {
  lefteft: 3em;
  }
}

body > main > div:first-of-type {
  background: white;
  position: relative;
  z-index: 9999999999;
  padding: 1.5em 1.5em 0;
  margin: 0 -1.5em -3em;
}
@media (min-width: 60em) {
  body > main > div:first-of-type {
    padding: 3em 3em 0;
    margin-left: -3em;
    margin-right: -3em;
    margin-bottom: -3em;
  }
}
body > main > div:first-of-type p:first-child {
  margin-top: 0;
}
body.image-reverse main h1 {
  left: auto;
  right: 1.5rem;
  max-width: none;
  text-align: right;
  margin-left: 50vw;
}
@media (min-aspect-ratio: 1/1) {
  body > .image {
    height: 65vh;
    min-height: 65vh;
  }
  body > .image img {
    top: 30vh;
  }
  body > .image img {
    width: 40vw;
    height: auto;
    right: -3em;
  }
  body > main > div:first-of-type {
    background: transparent;
    position: static;
    padding: 0;
    margin: 0;
    margin-right: 35%;
  }
  body.image-reverse main h1 {
    margin-left: 0;
    left: 50vw;
    right: auto;
    margin-right: 3rem;
    text-align: left;
  }
  body.image-reverse > main > div:first-of-type {
    margin-right: 0;
    margin-left: 50vw;
    margin-left: calc(50vw - 1.5em);
  }
  @media (min-width: 60em) {
    body.image-reverse > main > div:first-of-type {
      margin-left: calc(50vw - 3em);
    }
  }
}
/*
@media (min-width: 35em) {
  body.image-reverse main h1 {
    margin-left: 0;
    left: 50vw;
    right: auto;
    margin-right: 3rem;
    text-align: left;
  }
  body.image-reverse main > div:first-of-type p,
  body.image-reverse main > div:first-of-type ul {
    max-width: none;
    margin-left: 50vw;
    margin-left: calc(50vw - 3em);
    margin-right: 0;
  }
}
*/

/*
body > header h2,
body > header h2 + p {
  color: black;
  text-shadow: none;
}
body > header > a {
  margin-top: 1em;
}
*/
body > header h2,
body > header h2 + p {
  color: rgb(244, 209, 81); /* --gold */
  color: white;
  color: rgb(46, 127, 182); /* --ocean */
  color: rgb(40, 41, 43); /* --tungsten */
  text-shadow: none;
}
body > header h2 img {
  transform: translateY(-65%);
}
/*
body > main > p {
  margin-right: 50vw;
}
*/
main h1 {
  position: absolute;
  z-index: 3;
  max-width: 50vw;
  transform: translate(0, -100%);
  margin-top: -1.5rem;
  color: rgb(244, 209, 81); /* --gold */
  color: white;
  color: rgb(46, 127, 182); /* --ocean */
}
/*
@media (min-width: 50em) {
  main h1 {
    font-size: 3em;
  }
}
@media (min-width: 75em) {
  main h1 {
    font-size: 4em;
  }
}
*/
main h1 + h2,
main h1 + p {
  margin-top: 0;
}
figure {
  margin-top: 1.5em;
  margin-left: -4.5em;
  margin-right: -4.5em;
  margin-bottom: -4.5em;
  max-width: none;
  position: relative;
  z-index: 99999;
  transform: rotate(-2deg);
  overflow: hidden;
  background: rgb(51, 51, 51);
}
@media (min-width: 60em) {
  figure {
    margin-bottom: -7.5em;
  }
}
figure img {
  width: 100%;
  height: auto;
  max-width: none;
  transform: rotate(2deg) scale(1.125);
}
/*
figure {
  transform: rotate(-5deg) scale(0.85) translate(-6em, 0);
  margin-top: 1.5em;
  margin-bottom: 3em;
}
figure img {
  transform: rotate(5deg) scale(1.15);
}
*/
.staff-list {
  margin-top: 3em;
  padding: 1px 1.5em 3em 1.5em;
  margin-left: -1.5em;
  margin-right: -1.5em;
  background-color: white;
  position: relative;
  z-index: 99999;
}
@media (min-width: 60em) {
  .staff-list {
    padding-left: 3em;
    padding-right: 3em;
    margin-left: -3em;
    margin-right: -3em;
  }
}
.summaries {
  margin-top: 0;
  background-color: white;
  position: relative;
  z-index: 99999;
}
</style>

<style media="false">
.image {
  /*
  background-image: url(/images/background.png);
  background-position: center;
  background-size: cover;
  */
  padding-top: 35vh;
  box-sizing: border-box;
}
@media (min-width: 60em) {
  .image {
    padding-top: 35vh;
  }
}
.image::before,
.image::after {
  display: none;
}
body.has-image > header {
  height: 50vh;
  min-height: 50vh;
}
.image img {
  height: 100vmax;
  width: auto;
  margin-left: auto;
  margin-right: auto;
  position: absolute;
  left: 50%;
  z-index: 9999;
}
body.image-reverse .image img {
  left: -10%;
}
@media (min-width: 60em) {
  body.image-reverse .image img {
    left: 10%;
  }
}
/*
.image:after {
  content: "";
  background-image: linear-gradient(to top, rgba(255, 255, 255, 1), rgba(255, 255, 255, 1) 5%, rgba(255, 255, 255, 0) 55%, rgba(255, 255, 255, 0));
  height: 100vmax;
  width: 50vw;
  margin-left: auto;
  margin-right: auto;
  position: absolute;
  left: 50%;
  top: 5vh;
  z-index: 99999;
}
*/
/*
body > header h2,
body > header h2 + p {
  color: black;
  text-shadow: none;
}
*/
body > header > a {
  margin-top: 1em;
}
body > header h2,
body > header h2 + p {
  color: rgb(46, 127, 182); /* --ocean */
  text-shadow: none;
}
/*
body > header h2 + p {
  text-indent: -9999px;
  overflow: hidden;
}
body > header h2 img {
  transform: translateY(-65%);
}
*/
/*
body > main > p {
  margin-right: 50vw;
}
*/
/*
main h1 {
  position: absolute;
  transform: translateY(-150%);
  width: 75%;
  width: calc(75% - 1.5rem);
  font-size: 2em;
}
body.image-reverse main h1 {
  right: 1.5rem;
}
@media (min-width: 60em) {
  main h1 {
    width: 50%;
    width: calc(50% - 3rem);
  }
  body.image-reverse main h1 {
    right: 3rem;
  }
}
*/
main h1 {
  font-size: 2em;
  font-size: 5vmax;
  margin-bottom: 3rem;
}
@media (min-width: 55em) {
  main h1 {
    font-size: 3em;
    font-size: 5vmax;
  }
}
body.image-reverse main h1,
body.image-reverse main > p,
body.image-reverse main > ul {
  text-align: right;
}
@media (min-width: 30em) {
  body.image-reverse main h1,
  body.image-reverse main > p,
  body.image-reverse main > ul {
    text-align: left;
  }
}
/*
@media (min-width: 35em) {
  main h1 {
    transform: translateY(-175%);
  }
}
@media (min-width: 55em) {
  main h1 {
    font-size: 3em;
    transform: translateY(-200%);
  }
}
*/
main h1 + h2 {
  margin-top: 0;
}

main > h1,
main > p,
main > ul {
  max-width: 75%;
}
body.image-reverse main > h1,
body.image-reverse main > p,
body.image-reverse main > ul {
  margin-left: 20%;
}
@media (min-width: 60em) {
  main > h1,
  main > p,
  main > ul {
    max-width: 50%;
  }
  body.image-reverse main > h1,
  body.image-reverse main > p,
  body.image-reverse main > ul {
    margin-left: 45%;
  }
}
body {
  background-color: rgb(237, 237, 239);
}
.staff-list {
  margin-top: 3em;
  padding: 1px 1.5em 3em 1.5em;
  margin-left: -1.5em;
  margin-right: -1.5em;
  background-color: white;
  position: relative;
  z-index: 99999;
}
@media (min-width: 60em) {
  .staff-list {
    padding-left: 3em;
    padding-right: 3em;
    margin-left: -3em;
    margin-right: -3em;
  }
}
.summaries {
  margin-top: 0;
  background-color: white;
}
</style>

# Bringing aspiration <span class="avoid-break"><span class="lowercase">into</span> reality</span>

<div markdown="1">

Sierra High School is a place where students have a second opportunity to achieve academic success. To bring this aspiration into reality we:

*   model and build good relationships
*   develop skills and knowledge
*   foster independent thinking in a safe environment

Learn more [about our school](/about)

</div>

<div class="staff-list">
  <h2>Our Teachers</h2>
  <ul>
    <li>
      <img src="/images/staff/img_0218.jpg" width="200" alt="" />
      <h3>Mr. Charlie Callison</h3>
      <p class="title">Biology</p>
    </li>
    <li>
      <img src="/images/staff/img_0064.jpg" width="200" alt="" />
      <h3>Mrs. Shirley D’Avis</h3>
      <p class="title">English, Yearbook &amp; Leadership</p>
    </li>
    <li>
      <img src="/images/staff/img_0102.jpg" width="200" alt="" />
      <h3>Ms. Darla Elliott</h3>
      <p class="title">English</p>
    </li>
    <li>
      <img src="/images/staff/img_0119.jpg" width="200" alt="" />
      <h3>Ms. Barbara Klaus</h3>
      <p class="title">Science &amp; Math</p>
    </li>
  </ul>
  <p>See more <a href="/staff">staff members</a></p>
</div>


<div class="summaries">
  <div class="parents-summary text" markdown="1">
## Parents & students

Learn about attendance, handbooks, dress code and more on the [parents & students](/parents/) page.
  </div>

  <div class="calendar-summary text" markdown="1">
## Calendar

January 9
: Planning Day<br />_No School_

January 10
: Teacher PLC Day<br />_No School_

January 11
: Students Return from Break

[See full calendar](/calendar/)
  </div>
</div>

<section class="announcements">

<header>
<h2>News &amp; Announcements</h2>
</header>

<ul>
<li markdown="1">

### Winter break is from December 23, 2016 - January 10, 2017.

Students return to school on January 11th.

</li>
<li markdown="1">

### Tutoring is now available

Tuesdays and Thursdays in the computer lab, from 2pm to 3pm. Take advantage of this opportunity!

</li>
</ul>
</section>

<div class="feature">
  <h2>
    <svg class="icon" viewBox="0 0 24 24" width="48" height="48">
      <switch>
        <path fill="white" d="M22,19.4c0,1.4-1.2,2.6-2.6,2.6H4.6C3.2,22,2,20.8,2,19.4V4.6C2,3.2,3.2,2,4.6,2h14.9C20.8,2,22,3.2,22,4.6 V19.4z M19.7,10.5H18c0.2,0.5,0.3,1.1,0.3,1.7c0,3.3-2.8,6-6.2,6c-3.4,0-6.2-2.7-6.2-6c0-0.6,0.1-1.2,0.3-1.7H4.2v8.4 c0,0.4,0.4,0.8,0.8,0.8h13.9c0.4,0,0.8-0.4,0.8-0.8V10.5z M12,8.1c-2.2,0-4,1.7-4,3.9c0,2.1,1.8,3.9,4,3.9c2.2,0,4-1.7,4-3.9 C16,9.8,14.2,8.1,12,8.1z M19.7,5.1c0-0.5-0.4-0.9-0.9-0.9h-2.3c-0.5,0-0.9,0.4-0.9,0.9v2.1c0,0.5,0.4,0.9,0.9,0.9h2.3 c0.5,0,0.9-0.4,0.9-0.9L19.7,5.1L19.7,5.1z"></path>
        <foreignObject>Instagram</foreignObject>
      </switch>
    </svg>
    @sierrahighschool
  </h2>

  <a href="https://www.instagram.com">
    <img src="https://cdn.schoolloop.com/uimgcdn/aHR0cDovL3Nocy1hdXNkLWNhLnNjaG9vbGxvb3AuY29tL3VpbWcvaW1hZ2UvMTMwMTc1MjUxMDY3OC8xNDUyMzI4MTYzNTgyLzE0NTU0Mzk4ODcwNDguanBlZz9jcm9wVG9wPTM3JmNyb3BSaWdodD05NTAmY3JvcEJvdHRvbT03MTImY3JvcExlZnQ9NTAmYmFzaXNXaWR0aD0xMDAw" alt="Rotary Speech Contest Winners" />
    <p>Congratulations to Sierra High School's Violet Vargas for her Third Place Finish in The Rotary Club’s speech contest…</p>
  </a>

  <a href="https://www.instagram.com" class="icon">
    <svg class="comment icon" viewBox="0 0 24 24" width="24" height="24">
      <path fill="white" d="M2.2,8.9c0,1,0.3,1.9,1,2.8c0.7,0.9,1.6,1.5,2.8,2c1.2,0.5,2.5,0.7,3.9,0.7c0.4,0,0.8,0,1.3-0.1c1.1,1,2.5,1.7,4,2.1
        c0.3,0.1,0.6,0.1,1,0.2c0.1,0,0.2,0,0.3-0.1c0.1-0.1,0.1-0.1,0.2-0.3v0c0,0,0-0.1,0-0.1c0,0,0-0.1,0-0.1c0,0,0,0,0-0.1L16.5,16
        c0,0,0,0-0.1-0.1c0,0-0.1-0.1-0.1-0.1c0,0-0.1-0.1-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.3s-0.2-0.2-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.4
        c-0.1-0.1-0.1-0.3-0.2-0.5s-0.2-0.4-0.2-0.7c0.9-0.5,1.6-1.2,2.1-1.9s0.8-1.6,0.8-2.4c0-0.8-0.2-1.5-0.6-2.2s-1-1.3-1.7-1.8
        S14,4.1,13,3.8s-2-0.4-3-0.4c-1.4,0-2.7,0.2-3.9,0.7S4,5.2,3.3,6.1S2.2,7.9,2.2,8.9z"></path>
    </svg>
    2
  </a>

  <a href="https://www.instagram.com" class="icon">
    <svg class="heart icon" viewBox="0 0 24 24" width="24" height="24">
      <path fill="white" d="M17.631 5.93c-0.394-0.913-1.185-1.682-2.281-2.158-0.968-0.422-2.012-0.471-2.96-0.214s-1.801 0.956-2.388 1.767c-0.588-0.811-1.44-1.511-2.389-1.767-0.949-0.258-1.991-0.207-2.96 0.214-1.096 0.476-1.885 1.243-2.281 2.158-0.394 0.912-0.397 1.974 0.103 3.027 1.062 2.257 7.494 7.55 7.529 7.64 0.033-0.090 6.466-5.383 7.53-7.64 0.498-1.053 0.496-2.115 0.101-3.027z"></path>
    </svg>
    115
  </a>
</div>

<ul class="news-summary">
  <li>
    <a href="https://www.instagram.com">
      <img src="https://cdn.schoolloop.com/uimgcdn/aHR0cDovL3Nocy1hdXNkLWNhLnNjaG9vbGxvb3AuY29tL3VpbWcvaW1hZ2UvMTMwMTc1MjUxMDY3OC8xNDUyMzI4MTYzNTgyLzE0NTU0Mzk4OTYzNjEuanBnP2Nyb3BUb3A9MzcmY3JvcFJpZ2h0PTk1MCZjcm9wQm90dG9tPTcxMiZjcm9wTGVmdD00OSZiYXNpc1dpZHRoPTEwMDA=" alt="Building Cardboard Chairs" />
      <span>Building Cardboard Chairs</span>
    </a>

    <a href="https://www.instagram.com" class="icon">
      <svg class="comment icon" viewBox="0 0 24 24" width="24" height="24">
        <path fill="white" d="M2.2,8.9c0,1,0.3,1.9,1,2.8c0.7,0.9,1.6,1.5,2.8,2c1.2,0.5,2.5,0.7,3.9,0.7c0.4,0,0.8,0,1.3-0.1c1.1,1,2.5,1.7,4,2.1
          c0.3,0.1,0.6,0.1,1,0.2c0.1,0,0.2,0,0.3-0.1c0.1-0.1,0.1-0.1,0.2-0.3v0c0,0,0-0.1,0-0.1c0,0,0-0.1,0-0.1c0,0,0,0,0-0.1L16.5,16
          c0,0,0,0-0.1-0.1c0,0-0.1-0.1-0.1-0.1c0,0-0.1-0.1-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.3s-0.2-0.2-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.4
          c-0.1-0.1-0.1-0.3-0.2-0.5s-0.2-0.4-0.2-0.7c0.9-0.5,1.6-1.2,2.1-1.9s0.8-1.6,0.8-2.4c0-0.8-0.2-1.5-0.6-2.2s-1-1.3-1.7-1.8
          S14,4.1,13,3.8s-2-0.4-3-0.4c-1.4,0-2.7,0.2-3.9,0.7S4,5.2,3.3,6.1S2.2,7.9,2.2,8.9z"></path>
      </svg>
      2
    </a>

    <a href="https://www.instagram.com" class="icon">
      <svg class="heart icon" viewBox="0 0 24 24" width="24" height="24">
        <path fill="white" d="M17.631 5.93c-0.394-0.913-1.185-1.682-2.281-2.158-0.968-0.422-2.012-0.471-2.96-0.214s-1.801 0.956-2.388 1.767c-0.588-0.811-1.44-1.511-2.389-1.767-0.949-0.258-1.991-0.207-2.96 0.214-1.096 0.476-1.885 1.243-2.281 2.158-0.394 0.912-0.397 1.974 0.103 3.027 1.062 2.257 7.494 7.55 7.529 7.64 0.033-0.090 6.466-5.383 7.53-7.64 0.498-1.053 0.496-2.115 0.101-3.027z"></path>
      </svg>
      115
    </a>
  </li>
  <li>
    <a href="https://www.instagram.com">
      <img src="https://cdn.schoolloop.com/uimgcdn/aHR0cDovL3Nocy1hdXNkLWNhLnNjaG9vbGxvb3AuY29tL3VpbWcvaW1hZ2UvMTMwMTc1MjUxMDY3OC8xNDUyMzI4MTYzNTgyLzE0NTU0Mzk3Njk1NDkuanBnP2Nyb3BUb3A9MzcmY3JvcFJpZ2h0PTk1MCZjcm9wQm90dG9tPTcxMiZjcm9wTGVmdD00OSZiYXNpc1dpZHRoPTEwMDA=" alt="Installation Art at the Grocery Store" />
      <span>Installation Art at the Grocery Store</span>
    </a>

    <a href="https://www.instagram.com" class="icon">
      <svg class="comment icon" viewBox="0 0 24 24" width="24" height="24">
        <path fill="white" d="M2.2,8.9c0,1,0.3,1.9,1,2.8c0.7,0.9,1.6,1.5,2.8,2c1.2,0.5,2.5,0.7,3.9,0.7c0.4,0,0.8,0,1.3-0.1c1.1,1,2.5,1.7,4,2.1
          c0.3,0.1,0.6,0.1,1,0.2c0.1,0,0.2,0,0.3-0.1c0.1-0.1,0.1-0.1,0.2-0.3v0c0,0,0-0.1,0-0.1c0,0,0-0.1,0-0.1c0,0,0,0,0-0.1L16.5,16
          c0,0,0,0-0.1-0.1c0,0-0.1-0.1-0.1-0.1c0,0-0.1-0.1-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.3s-0.2-0.2-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.4
          c-0.1-0.1-0.1-0.3-0.2-0.5s-0.2-0.4-0.2-0.7c0.9-0.5,1.6-1.2,2.1-1.9s0.8-1.6,0.8-2.4c0-0.8-0.2-1.5-0.6-2.2s-1-1.3-1.7-1.8
          S14,4.1,13,3.8s-2-0.4-3-0.4c-1.4,0-2.7,0.2-3.9,0.7S4,5.2,3.3,6.1S2.2,7.9,2.2,8.9z"></path>
      </svg>
      2
    </a>

    <a href="https://www.instagram.com" class="icon">
      <svg class="heart icon" viewBox="0 0 24 24" width="24" height="24">
        <path fill="white" d="M17.631 5.93c-0.394-0.913-1.185-1.682-2.281-2.158-0.968-0.422-2.012-0.471-2.96-0.214s-1.801 0.956-2.388 1.767c-0.588-0.811-1.44-1.511-2.389-1.767-0.949-0.258-1.991-0.207-2.96 0.214-1.096 0.476-1.885 1.243-2.281 2.158-0.394 0.912-0.397 1.974 0.103 3.027 1.062 2.257 7.494 7.55 7.529 7.64 0.033-0.090 6.466-5.383 7.53-7.64 0.498-1.053 0.496-2.115 0.101-3.027z"></path>
      </svg>
      115
    </a>
  </li>
  <li>
    <a href="https://www.instagram.com">
      <img src="https://cdn.schoolloop.com/uimgcdn/aHR0cDovL3Nocy1hdXNkLWNhLnNjaG9vbGxvb3AuY29tL3VpbWcvaW1hZ2UvMTMwMTc1MjUxMDY3OC8xNDUyMzI4MTYzNTgyLzE0NTU0MzkzODk5MjMuanBlZz9jcm9wVG9wPTM3JmNyb3BSaWdodD05NTAmY3JvcEJvdHRvbT03MTImY3JvcExlZnQ9NTAmYmFzaXNXaWR0aD0xMDAw" alt="PBIS R-Buck exchange" />
      <span>PBIS R-Buck exchange</span>
    </a>

    <a href="https://www.instagram.com" class="icon">
      <svg class="comment icon" viewBox="0 0 24 24" width="24" height="24">
        <path fill="white" d="M2.2,8.9c0,1,0.3,1.9,1,2.8c0.7,0.9,1.6,1.5,2.8,2c1.2,0.5,2.5,0.7,3.9,0.7c0.4,0,0.8,0,1.3-0.1c1.1,1,2.5,1.7,4,2.1
          c0.3,0.1,0.6,0.1,1,0.2c0.1,0,0.2,0,0.3-0.1c0.1-0.1,0.1-0.1,0.2-0.3v0c0,0,0-0.1,0-0.1c0,0,0-0.1,0-0.1c0,0,0,0,0-0.1L16.5,16
          c0,0,0,0-0.1-0.1c0,0-0.1-0.1-0.1-0.1c0,0-0.1-0.1-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.3s-0.2-0.2-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.4
          c-0.1-0.1-0.1-0.3-0.2-0.5s-0.2-0.4-0.2-0.7c0.9-0.5,1.6-1.2,2.1-1.9s0.8-1.6,0.8-2.4c0-0.8-0.2-1.5-0.6-2.2s-1-1.3-1.7-1.8
          S14,4.1,13,3.8s-2-0.4-3-0.4c-1.4,0-2.7,0.2-3.9,0.7S4,5.2,3.3,6.1S2.2,7.9,2.2,8.9z"></path>
      </svg>
      2
    </a>

    <a href="https://www.instagram.com" class="icon">
      <svg class="heart icon" viewBox="0 0 24 24" width="24" height="24">
        <path fill="white" d="M17.631 5.93c-0.394-0.913-1.185-1.682-2.281-2.158-0.968-0.422-2.012-0.471-2.96-0.214s-1.801 0.956-2.388 1.767c-0.588-0.811-1.44-1.511-2.389-1.767-0.949-0.258-1.991-0.207-2.96 0.214-1.096 0.476-1.885 1.243-2.281 2.158-0.394 0.912-0.397 1.974 0.103 3.027 1.062 2.257 7.494 7.55 7.529 7.64 0.033-0.090 6.466-5.383 7.53-7.64 0.498-1.053 0.496-2.115 0.101-3.027z"></path>
      </svg>
      115
    </a>
  </li>
</ul>
