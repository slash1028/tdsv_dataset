---
---

# VoxCeleb is an audio-visual dataset consisting of short clips of human speech, extracted from interview videos uploaded to YouTube



{% include section.html %}

## Dataset

{% capture text %}

There are two versions of this dataset, VoxCeleb1 and VoxCeleb2. VoxCeleb1 consists of more than 150,000 utterances from 1251 celebrities, and VoxCeleb2 consists of more than 1,000,000 utterances from 6112 celebrities.
As shown in Table below, the SuperVox contains 1250 speakers, with 1210 speakers in the dev set, and 40 speakers in the test set. Compared with the original VoxCeleb, there is a tiny decrease in the number of speakers. This is because the proposed corpora contain only English audios, some speakers included in VoxCeleb have only samples of other languages, which results in slightly decrease in the amount of speakers.  Most of the audios are below 1 second.

image="images/dataset.jpg"

{%
  include button.html
  link="research"
  text="Download samples from here."
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/AboutPolyU_Campus1.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="In this page, a limited sample of the database is provided."
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/AboutPolyU_Campus10.png"
  link="projects"
  title="尝试一下1"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

qwfqwfwqfqa.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/AboutPolyU_Campus8.png"
  link="team"
  title="尝试一下2"
  text=text
%}
