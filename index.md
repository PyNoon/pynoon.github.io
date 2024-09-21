---
layout: home
---

**Learn Python programming with individual support in a friendly
learning environment**

PyNoon is a community training initiative that is part of the
[TechNoon movement](https://technoon.org). There is no cost and the
courses are run by experienced volunteers.

The goal is to up-skill people in the world’s most popular programming
language. Python is used for automation, data science, web
development, and much more.

It is very common for training needs to get pushed aside by the
demands of work and the friendly and supportive learning environment
provided in the course helps people actually learn enough to start
putting Python to work.

<!--

* **When:** Mondays 11:30am - 1:30pm
* **Where:** 136 Fanshawe Street, Auckland CBD
* **Duration:** 10 weeks
* **Cost:** Free (community initiative)
* **No prior programming experience required**
* **Note:** BYO lunch and laptop (food outlets in building and guest
  WiFi)

<a class="flyer" href="{{ '/static_files/pynoon_flyer_2023.pdf' | prepend: site.baseurl }}" target="_blank" rel="noopener">Download a shareable flyer</a>

-->

<blockquote style="margin: 1em 0;">
  PyNoon is an exciting new community training initiative for
  Python New Zealand. The popularity of Python is exploding and we want to make
  it as easy as possible for people in a wide range of industries
  to write high-quality, well-engineered Python code. PyNoon is
  also an excellent entry point into the wider New Zealand Python
  community.
  <div style="text-align: right; padding-top: 1em;">
    - Danny Adair, founder and past President of Python New Zealand
  </div>
</blockquote>

## Learning objectives

PyNoon is run as a series of **three 3-4 week** courses. You can
choose to attend the courses that match your interests and skill
level:

1. **PyNoon Starter**: Learn the fundamentals of the Python language -
   no prior programming experience required!
2. **PyNoon Data**: Learn to use Python to analyse and plot tabular
   data (e.g. spreadsheets)
3. **PyNoon Plus**: Advanced topics, from calling web APIs to using AI
   models

In each course, you are also encouraged to bring along your own coding
/ work problems to get assistance from the experienced volunteers at
PyNoon.

For more details, see the <a href="{{ '/lessons' | prepend: site.baseurl }}">Lessons page</a>.

## Lesson Structure

Each PyNoon lesson is **two hours long** and is structured to:

* Provide sufficient time for independent work (with instructor
  support) to reinforce your Python learning
* Concentrate the most important elements in a central hour for those
  who need to arrive late or leave early:

<style>
    .structure-table {
        border-spacing: 0;
        border-collapse: collapse;
        width: 100%;
        margin-bottom: 1em;
    }
    .structure-table td {
        vertical-align: top;
        border: 1px solid #111;
        padding: 0.5em;
    }
    .structure-table td.time {
        font-weight: bold;
        text-align: right;
    }
</style>
<table class="structure-table">
    <tbody>
        <tr>
            <td class="time">30 mins</td>
            <td>Independent work (with instructor support)</td>
        </tr>
        <tr>
            <td class="time">1 hour</td>
            <td>
                <strong>PyNoon's Core: Learning together</strong>
                <ul style="margin-bottom: 0;">
                    <li>Lunch and networking (BYO lunch)</li>
                    <li>Short whiteboard lesson</li>
                    <li>Instructor-led live coding (BYO laptop)</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td class="time">30 mins</td>
            <td>Independent work (with instructor support)</td>
        </tr>
    </tbody>
</table>

<div id="nanogallery">
  {% for image in site.data.gallery.images %}
  <a
    href="{{ image.path | prepend: '/_images/gallery/' | prepend: site.baseurl }}"
    data-ngthumb="{{ image.thumbnail_path | prepend: '/_images/gallery/' | prepend: site.baseurl }}"
  >
    {{ image.caption }}
  </a>
  {% endfor  %}
</div>

<script type="text/javascript">
 jQuery("#nanogallery").nanogallery2({
   viewerTools: {
     topLeft: 'label',
     topRight: 'fullscreenButton, closeButton',
   },
   thumbnailGutterWidth: 0, thumbnailGutterHeight: 0,
   thumbnailBorderHorizontal: 1, thumbnailBorderVertical: 1,
   thumbnailLabel: { display: false },
 });
</script>
