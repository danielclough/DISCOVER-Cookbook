---
layout: page
title: Taxonomy
tags: 
 - Taxonomy
---

## Taxonomy
Throughout the cookbook, we have tagged the individual recommendations with tags from the taxonomy below.

**Conference Logistics**
  * Registration
  * Check-in
  * Accommodation
  * Location & Venue
  * Organization and Program Committees
  * Scholarships
  * Participant Diversity
  * Talks
  * Poster Sessions
  * Social Events
  * Catering
  * Bathrooms
  * Calls for papers/proposals
  * Code of Conduct
  * Presenter Line-up
  
**Diverse Groups**
  * Parents & Carers
  * Women
  * LGBTQ+
  * Racial Minorities
  * Ethnic Minorities
  * Religious Groups
  * Newcomers & First-Timers
  * People with Disabilities
    * Visual Impairments
    * Hearing Impairment
    * Mobility Impairment
    * Other Impairments
  * People with Allergies
  * Global South & Developing Countries
  * Dietary Restrictions

**Potential Challenges**
  * Unconscious and Implicit Bias
  * Discrimination
  * Sexual Harassment
  * Bullying
  * Stereotyping
  * Tokenizing

**Inclusive Atmosphere**
  * Giving Participants Room to Be Who They Are
  * Being Respectful
  * Being Open
  * Embracing Diverse Voices and Experiences

## Tags

    {% for page in site.pages %}
    {% if page.tags %}
### Tags <a href='{{ page.url }}'>***{{ page.title }}***</a> <br/><span style="color:red"> {{ page.tags | array_to_sentence_string }}</span>     
     {% endif %}
     {% if page.committee %}
### Committee <a href='{{ page.url }}'>***{{ page.title }}***</a> <br/><span style="color:red"> {{ page.committee | array_to_sentence_string }}</span>     
     {% endif %}
     {% if page.welcome %}     
### Welcome <a href='{{ page.url }}'>***{{ page.title }}***</a> <br/><span style="color:red"> {{ page.welcome | array_to_sentence_string }}</span>   
{% endif %}
     {% if page.mobility %}
### Mobility <a href='{{ page.url }}'>***{{ page.title }}***</a> <br/><span style="color:red"> {{ page.mobility | array_to_sentence_string }}</span>     
{% endif %}
     {% if page.disability %}
### Disability <a href='{{ page.url }}'>***{{ page.title }}***</a> <br/><span style="color:red"> {{ page.disability | array_to_sentence_string }}</span>     
{% endif %}
     {% if page.bathroom %}
### Bathroom <a href='{{ page.url }}'>***{{ page.title }}***</a> <br/><span style="color:red"> {{ page.bathroom | array_to_sentence_string }}</span>     
{% endif %}
     {% if page.nursing-pumping %}
### Nursing/Pumping <a href='{{ page.url }}'>***{{ page.title }}***</a> <br/><span style="color:red"> {{ page.nursing-pumping | array_to_sentence_string }}</span>     
{% endif %}
     {% if page.nursing-bottle %}
### Nursing/Bottle <a href='{{ page.url }}'>***{{ page.title }}***</a> <br/><span style="color:red"> {{ page.nursing-bottle | array_to_sentence_string }}</span>     
{% endif %}
     {% if page.quite %}
### Quite <a href='{{ page.url }}'>***{{ page.title }}***</a> <br/><span style="color:red"> {{ page.quite | array_to_sentence_string }}</span>     
{% endif %}
     {% if page.catering %}
### Catering <a href='{{ page.url }}'>***{{ page.title }}***</a> <br/><span style="color:red"> {{ page.catering | array_to_sentence_string }}</span>     
{% endif %}
     {% if page.childcare %}
### Childcare <a href='{{ page.url }}'>***{{ page.title }}***</a> <br/><span style="color:red"> {{ page.childcare | array_to_sentence_string }}</span>     
{% endif %}
     {% if page.code-of-conduct %}
### Code-of-Conduct <a href='{{ page.url }}'>***{{ page.title }}***</a> <br/><span style="color:red"> {{ page.code-of-conduct | array_to_sentence_string }}</span>     
{% endif %}
     {% if page.grants-scholarships %}
### Grants/Scholarships <a href='{{ page.url }}'>***{{ page.title }}***</a> <br/><span style="color:red"> {{ page.grants-scholarships | array_to_sentence_string }}</span>     
{% endif %}
     {% if page.speakers %}
### Speakers <a href='{{ page.url }}'>***{{ page.title }}***</a> <br/><span style="color:red"> {{ page.speakers | array_to_sentence_string }}</span>     
{% endif %}
     {% if page.selecting-speakers %}
### Selecting Speakers <a href='{{ page.url }}'>***{{ page.title }}***</a> <br/><span style="color:red"> {{ page.selecting-speakers | array_to_sentence_string }}</span>     
{% endif %}
     {% if page.new-speakers %}
### New Speakers <a href='{{ page.url }}'>***{{ page.title }}***</a> <br/><span style="color:red"> {{ page.new-speakers | array_to_sentence_string }}</span>     
{% endif %}
     {% if page.attendees %}
### Attendees <a href='{{ page.url }}'>***{{ page.title }}***</a> <br/><span style="color:red"> {{ page.attendees | array_to_sentence_string }}</span>     
{% endif %}
     {% if page.proposals %}
### Proposals <a href='{{ page.url }}'>***{{ page.title }}***</a> <br/><span style="color:red"> {{ page.proposals | array_to_sentence_string }}</span>     
{% endif %}
     {% if page.accessibility %}
### Accessibility <a href='{{ page.url }}'>***{{ page.title }}***</a> <br/><span style="color:red"> {{ page.accessibility | array_to_sentence_string }}</span>     
{% endif %}
     {% if page.grants %}
### Grants <a href='{{ page.url }}'>***{{ page.title }}***</a> <br/><span style="color:red"> {{ page.grants | array_to_sentence_string }}</span>     
{% endif %}
     {% if page.dietary %}
### Dietary <a href='{{ page.url }}'>***{{ page.title }}***</a> <br/><span style="color:red"> {{ page.dietary | array_to_sentence_string }}</span>     
{% endif %}
     {% if page.t-shirts %}
### T-shirts <a href='{{ page.url }}'>***{{ page.title }}***</a> <br/><span style="color:red"> {{ page.t-shirts | array_to_sentence_string }}</span>     
{% endif %}
     {% if page.demographic %}
### Demographic <a href='{{ page.url }}'>***{{ page.title }}***</a> <br/><span style="color:red"> {{ page.demographic | array_to_sentence_string }}</span>     
{% endif %}
    {% if page.photography %}
### Photography <a href='{{ page.url }}'>***{{ page.title }}***</a> <br/><span style="color:red"> {{ page.photography | array_to_sentence_string }}</span>   
    {% endif %}
     {% if page.pronouns %}
### Pronouns <a href='{{ page.url }}'>***{{ page.title }}***</a> <br/><span style="color:red"> {{ page.pronouns | array_to_sentence_string }}</span>   
{% endif %}
     {% if page.assessment %}
### Assessment <a href='{{ page.url }}'>***{{ page.title }}***</a> <br/><span style="color:red"> {{ page.assessment | array_to_sentence_string }}</span>   
    {% endif %}
    {% endfor %}