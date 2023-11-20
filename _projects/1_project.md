---
layout: page
title: Automatic Generation of Melodic and Chordal Chromaticism
img: assets/img/chrom_scale.png
importance: 1
category: work
---

Western popular and art music use the diatonic scale as their
foundation in both melody and harmony, and restricting to diatonic
scales can simplify both analysis and composition. However, even mostly
diatonic genres contain some limited use of chromaticism or accidentals.
Therefore I created this pipeline that, after creating diatonic music, auto-
matically alters selected notes chromatically to enhance the melody and
harmony. This project presents several deep learning models for generating
this chromaticism given a purely diatonic input melody and accompanying chord sequence. The altered melody and harmony from the model
are generally compelling and conform to musical syntax, making it a
work a potentially useful tool for both human and computer agents to
augment existing compositions or aid in the compositional process.

Diatonic input Example:

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include audio.html path= "assets/audio/diatonic_in.wav" controls=true %}
    </div>
</div>


Chromatized Ouput Example: 

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include audio.html path= "assets/audio/chromatic_out.wav" controls=true %}
    </div>
</div>



Check the code out here: https://github.com/antchristou/Automatic-Creation-Of-Chordal-and-Melodic-Chromaticism
