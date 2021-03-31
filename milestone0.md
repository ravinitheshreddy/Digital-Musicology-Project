# Digital Musicology - Milestone 0

## Tonality in non-Western music

## Research Questions

The phenomenon of tonality is one of the vastest topic in the field of music theory and many Western musicologists consider it to be the principal theoretical foundation in Western music. However, the definition of tonality itself is disputed. While it is established that tonality denotes the organization of music compositions around a tonic, some theorists argue it is restrained to the Western major and minor scale systems, and others pledge for a more embracing definition that encompasses systems of different cultures. This disagreement takes root in part because this _organization of music_ generally includes music concepts that are specific to Western music, such as cadence, counterpoint, or modulation. Other concepts however can be applied to modal pieces of any culture, like for example the scale degrees or intervals.

Therefore, this project will endeavour to provide some insights on the cross-culturality of tonality by statistically analyzing modal music from different cultures. More specifically, we will first study how different music concepts interfere with tonality in each examined culture. Afterwards, we will evaluate how each of these concepts, if applicable, compare cross-culturally in order to establish a possible answer as to whether it is relevant to expand the concept of tonality to non-Western scale systems.

As we will notably evaluate the distribution of scale degrees, one possible outcome might be that we observe that the perfect fifth above the tonic is prevalent in non-Western scale systems, thus showing a cross-cultural similarity in the way to express tonality. However, we may also expect to find out that the Western dominant scale degree is infrequent in other scale-systems, thus hinting at a different expression of tonality.

## Concepts and Data

In this project, we will compare one or two corpora of non-Western modal pieces with Western ones. This comparison revolves around the very important music concept of tonality, which, for the scope of this project, we will understand in its broad meaning, i.e., the organization of compositions around a central pitch. To evaluate this organization, we will be careful to not apply concepts of Western music that do not relate to other cultures. Therefore, we will focus on concepts that are inherently shared cross-culturally in modal pieces. We will mainly focus on the use of scale degrees in each corpus by translating each tonic to a reference pitch. We will then be able to learn properties of modal music organization in each examined culture by analyzing their frequency as well as their transitions. This analysis will then lead to a comparison which will allow us to state whether or not there is a similar expression of tonality in different cultures.

To conduct this analysis, we will first need a dataset of Western modal music in symbolic format labelled with the tonic. Then we will pick one or two datasets of different cultures labelled the same way. We were thinking of choosing Indian and/or Chinese music. However we have been unable so far to find such labelled datasets for non-Western music. If they do not exist, we may need to annotate the tonic ourselves or to infer it.

## Methods
As stated above, all of our methods will rotate around the use of scale degrees. First we will conduct statistical analyses of their distributions. We will then analyze how each scale degrees transitions to another. This will allow us to build a graph or a table depicting the most likely transitions and to compute a notion of entropy.

Comparing the results of all of these analyses will lead us to a possible answer as to whether or not tonality is expressed similarly in different cultures.

## Literature

The basic concepts summarizing the early studies on tonality, more specific analysis on scale tone, are presented in chapter 9 of Huron (2006). This will serve as a reference baseline for our study. More recently, Moss et al. (2019) have performed a corpus study of Beethoven's string quartets to obtain the statistical characteristics of tonal harmony. This recent study would provide us with the characterization of western music.

In the above-mentioned studies, the research has been restrained to Western music. As Huron states, no such analysis has been performed for non Western pieces, and our project will strive to fill that void.
### References

1. Huron, D. B. & MIT Press. (2006). Sweet Anticipation. Amsterdam University Press.
2. Moss FC, Neuwirth M, Harasim D, Rohrmeier M (2019) Statistical characterthe istics of tonal harmony: A corpus study of Beethoven's string quartets. PLoS ONE 14(6): e0217242. https://doi.org/10.1371/journal.pone.0217242

## Two more things

We would like to have the support of the teaching team in the following aspects:

1. We would like to know if there would any other relevant musical concept that would help us comparing the tonality in different cultures.
2. Does the DCML lab already know of any non-Western modal music dataset labelled with the tonic that could be beneficial to us?
