---
layout: page
title: The PyNoon Vision
permalink: /vision/
---


The purpose of PyNoon is to help professionals learn Python, the
world's most popular programming language, in a friendly and
convenient learning environment to the level where they can actually
start using Python at work.

**Accessible:** To make them as accessible as possible, PyNoon courses
are scheduled around lunchtime and in central locations such as the
CBD.

**Community:** The secret sauce is the community dimension. It is easy
to have good intentions about learning Python on our own but doing it
alongside others makes it much easier to actually learn enough to
achieve useful results.

**Supported Self-Learning:** The course is centred around on-line
resources but friendly and knowledgeable volunteers will be available
to assist learners. There will also be instructor-led live coding to
help people bridge the gap between learning simple syntax and actually
writing working programs. It is also assumed that learners will aim to
do an hour of extra on-line learning between sessions.

**Practical:** The latter weeks of the course will shift towards
independent project work according to individual interests and work
needs. This is the chance to consolidate learning into something
useful.


To learn more about the TechNoon movement behind PyNoon, check out the
[TechNoon manifesto](https://technoon.org/manifesto/).


<div class="profile-pic-gallary">
    <h2>Founders</h2>
    <div class="instructor-list">
        {% for ins in site.data.people.instructors %}
        <div class="image--cover-container">
            <div class="profile-pic">
                <img src="{{ins.profile_pic | prepend: site.baseurl }}" class="image--cover">
                {% if ins.webpage %}
                <p><a href="{{ ins.webpage }}">{{ins.name}}</a></p>
                {% else %}
                <p>{{ins.name}}</p>
                {% endif %}
            </div>
            <p class="bio">{{ins.bio}}</p>
        </div>
        {% endfor %}
    </div>
</div>
