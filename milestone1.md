# Digital Musicology - Milestone 1

## Modal organization in Chinese Folks songs

## Research Questions

The phenomenon of tonality is one of the vastest topics in the field of music theory and many Western musicologists consider it to be the principal theoretical foundation in Western music<sup>1</sup>. However, the definition of tonality itself is disputed. Some music theorists argue it is restrained to the Western major and minor scale systems, and others pledge for a more embracing definition that encompasses systems of different cultures<sup>1</sup>. For the scope of this project we will understand the tonality in its simplest meaning as "a system for interpreting pitches or chords through their relationship to a reference pitch"<sup>1</sup>. While many analysis of such relationships to the tonic (the modal organization) have been performed in Western music, this territory remains vastly unexplored in non-Western cultures<sup>1</sup>.

Therefore, this project will delve into this area by analyzing Chinese Folk Songs. More specifically, it will strive to provide answers as to what is the modal organization in Chinese Folk Songs and how does it differ between different regions of China ?

Chinese Folk songs stem from an oral tradition of people casually singing during their daily life. Therefore, Chinese folk songs present diverse stylistic characteristics as their composition is closely related to the people's lifestyle and is influenced by the geographical conditions, customs and habits. For instance, in the Northwest Plateau that thrives with agriculture, folk songs are usually sung in the fields during or after work. In contrast, in the Jiangsu and Zhejiang Plains, where the culture is more developed and where life is more prosperous, singing folk songs became more of an entertainment and socializing mean. This tradition gave birth to the *Xiao Diao*, folk songs with a soft and gentle style. In the Northeast Plain, where people are known to be very open and outgoing, a style called *Yangko* that is accompanied by dance developed. As a final example, in the Southeast of Guangxi and parts of Hainan, as fishermen used to be a dominant social class in the area, sea shanties are prominent amongst folk songs.<sup>6</sup>

Therefore, we hypothesize that the modal organization significantly differ between regions of China and that such a statistical analysis will provide a new perspective to define regional characteristics of Chinese Folk Songs.

## Concepts and Data

In this project, we will analyze the modal organization of a corpus of Chinese Folk Songs where each composition is characterized by its region. To do so, the most important and central music concept we will use is the scale degree. Indeed, by translating each composition to a reference pitch relatively to their tonic, the scale degree will provide a common factor to analyze all pieces together . More precisely, we will measure the distribution of scale degrees as well as the transitions between one another. Such an analysis will provide us a characterization of the modal organisation of Chinese Folk Songs for each labeled region.

To conduct such an analysis, we will need a dataset of Chinese Folk Songs annotated with the tonic. Moreover, it will need to be labeled with its geographical information. Luckily, the [Essen Folksong Dataset](http://kern.ccarh.org/browse?l=essen) provides such data.

It is important to note that the Chinese Folk Songs that can be studied in this project will be those compiled and published after the founding of New China in 1949. Indeed, most of the ancient Chinese folk song scores no longer exist, since they have always been an oral tradition and people tended to not use the music transcriptions even if they existed. It was not until the end of the 19th century that folklorists started to record folk songs with gong-rule scores.<sup>6</sup>
## Methods

As stated above, all of our methods will rotate around the use of scale degrees. First, we will conduct statistical analyses of their distribution in order to determine which scale degrees are the most prevalent. We will also analyze how each scale degree transitions to another. This will allow us to build a graph or a table depicting the most likely transitions and to compute a notion of entropy<sup>1</sup>. The results of these analyses will allow us to interpret the modal organization of Chinese Folk Songs in each studied region.

## Literature

The basic concepts summarizing the early studies on tonality, more specifically the analysis of the major mode, are presented in chapter 9 of Huron (2006). This will serve as a reference baseline for our study. More recently, Moss et al. (2019a) have performed a corpus study of Beethoven's string quartets to obtain the statistical characteristics of tonal harmony. This recent study would provide us with the characterization of Western music. Similarly, chapters 9-12 in Moss (2019b) discuss the tonal relations that can be inferred from a large historical corpus of western music.

In these studies, the research was restrained to Western music. As Huron states, no such analysis has been performed for non-Western pieces, and our project will strive to fill this void.
### References

1. Huron, D. B. & MIT Press. (2006). Sweet Anticipation. Amsterdam University Press.
2. Moss FC, Neuwirth M, Harasim D, Rohrmeier M (2019a) Statistical characterthe istics of tonal harmony: A corpus study of Beethoven's string quartets. PLoS ONE 14(6): e0217242. https://doi.org/10.1371/journal.pone.0217242
3. Moss, F. C. (2019b). Transitions of Tonality: A Model- Based Corpus Study. Doctoral dissertation, École Polytechnique Fédérale de Lausanne, Lausanne, Switzerland. 
4. Butler, David. ‘Describing the Perception of Tonality in Music: A Critique of the Tonal Hierarchy Theory and a Proposal for a Theory of Intervallic Rivalry’. Music Perception 6, no. 3 (1 April 1989): 219–41. https://doi.org/10.2307/40285588.
5. Bohlman, Philip V. The Study of Folk Music in the Modern World. Indiana University Press, 1988.
6. 6. ‘中国民歌_百度百科’. Accessed 11 April 2021. https://baike.baidu.com/item/%E4%B8%AD%E5%9B%BD%E6%B0%91%E6%AD%8C.
7. 王芳, 周年兴, 关健, 彭鹏. (2015). 中国民歌文化景观基因空间分布特征及形成机理. 热带地理, 35(6), 797-803.
