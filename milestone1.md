# Digital Musicology - Milestone 1

## Modal organization in Chinese Folks songs

## Research Questions

In this project, we will study the modal organization of Chinese Folk Songs across different regions.

The phenomenon of tonality is one of the vastest topics in the field of music theory and many Western musicologists consider it to be the principal theoretical foundation in Western music<sup>1</sup>. However, the definition of tonality itself is disputed. Some music theorists argue it is restrained to the Western major and minor scale systems, and others support a more embracing definition that encompasses systems of different cultures<sup>1</sup>. For the scope of this project, we will understand the tonality in its simplest meaning as "a system for interpreting pitches or chords through their relationship to a reference pitch"<sup>1</sup> and we will refer to the pitches' relationship to the tonic as the "modal organization".  While many analyses of modal organizations have been performed in Western music, this territory remains vastly unexplored in non-Western cultures<sup>1</sup>.

Therefore, this project will delve into this area by analyzing Chinese Folk Songs (hereafter CFS). More specifically, it will strive to provide answers as to what are the modal organizations in CFS and how they differ between different regions of China?

CFS stem from an oral tradition of people casually singing during their daily life. Therefore, CFS present diverse stylistic characteristics as their composition is closely related to the people's lifestyle and is influenced by geographical conditions, customs and habits. For instance, in the Northwest Plateau that throve with agriculture, folk songs were usually sung in the fields during their work. In contrast, in the Jiangsu and Zhejiang Plains, where culture was more developed and where life was more prosperous, singing folk songs became entertainment and a mean to sociliaze. This tradition gave birth to the _Xiao Diao_: folk songs with a soft and gentle style. In the Northeast Plain, where people are known to be very open and outgoing, a more dynamic style accompanied by dance called _Yangko_ developed. As a final example, in the Southeast of Guangxi and parts of Hainan, sea shanties were prominent amongst folk songs, as fishermen used to be a dominant social class in the area.<sup>2</sup>

Therefore, we hypothesize that the modal organization significantly differs between regions of China and that such a statistical analysis will provide a new perspective to view the CFS.

## Concepts and Data

In this project, we will analyze the modal organization of a corpus of monophonic CFS in pentatonic scale-system, in which each composition is characterized by its region. To do so, the most important and central music concept we will use is the scale degree. Indeed, by translating each composition to a reference pitch relative to their tonic, the scale degree will provide a common base to analyze all pieces together. More precisely, we will measure the distribution of scale degrees as well as the transitions between one another. Such an analysis will provide a characterization of the modal organization of Chinese Folk Songs for each studied region.

To conduct such an analysis, we will need a dataset of CFS annotated with the tonic. Moreover, it needs to be labeled with its geographical information. The [Essen Folksong Dataset](http://kern.ccarh.org/browse?l=essen) provides such data. The data set comprises of 2250 traditional CFS, from Han, Natmin, Shanxi, and Xinhua areas.

It is important to keep in mind that the CFS that can be studied in this project will be those compiled and published after the founding of New China in 1949. Indeed, most of the ancient CFS scores do not exist, since they have always been an oral tradition and people tended not to use the music transcriptions even if they existed. It was not until the end of the 19th century that folklorists started to record folk songs with gong-rule scores.<sup>2</sup>

## Methods

As stated above, all of our methods will rotate around the use of scale degrees. First, we will conduct statistical analyses of their distribution in order to determine which scale degrees are the most prevalent. We will also analyze how each scale degree transitions to another. This will allow us to build a graph or a table depicting the most likely transitions and to compute a notion of entropy<sup>1</sup>. The results of these analyses will allow us to interpret the modal organization of CFS in each studied region.

## Literature

The basic concepts summarizing the early studies on tonality, more specifically the analysis of the major mode, are presented in chapter 9 of Huron (2006). This will serve as a reference baseline for our study. The same chapter also summarizes tonality studies on non-Western music and states that only very little analysis has been performed so far. Our project will thus strive to fill this void.

Jones, S. (1999) shall help us to gain insights into the Chinese folk music and Bohlman (1988) to give us general expansive view of folk music.

Lastly, 王芳 (2015) shall provide us with reference in the spatial distribution characteristics and formation mechanism of CFS culture.

### References

1. Huron, D. B. & MIT Press. (2006). Sweet Anticipation. Amsterdam University Press.
2. '中国民歌 百度百科'. Accessed 11 April 2021. https://baike.baidu.com/item/%E4%B8%AD%E5%9B%BD%E6%B0%91%E6%AD%8C.
3. Jones, S. (1999). Folk Music of China: Living Instrumental Traditions Text and CD (Clarendon Paperbacks). Oxford University Press.
4. Bohlman, Philip V. (1988) The Study of Folk Music in the Modern World. Indiana University Press.
5. 王芳, 周年兴, 关健, 彭鹏. (2015). 中国民歌文化景观基因空间分布特征及形成机理. 热带地理, 35(6), 797-803.
