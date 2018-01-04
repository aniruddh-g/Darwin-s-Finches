# Darwin-s-Finches

There are many important observtions to lead Charles Darwin towards the theory of evolution are made in the Galapagos archiepelago. Particularily in the study of a number of small brids finches that inhabit them. These isalnds have 2 ground finch species, Geospiza Fortis and Geospiza Scandens, Grant have measured them every year of physiological measurements, taking samples for genetic sequencing and more. In 2014 a book was published 40 Years of Evolution: Darwin’s Finches on Daphne Major Island. Its great to learn statistical and data science insight about evolution.

We will focus on the primary two species of ground finch on Daphne Major, Geospiza fortis and Geospiza scandens. In this finch_beaks.csv, you will find measurements of the beak length (tip to base) and beak depth (top to bottom) of these finches in the years 1973, 1975, 1987, 1991, and 2012. Also included in that data set is the band number for the bird, which gives a unique identifier.

a) We start with a little tidying of the data. Think about how you will deal with duplicate measurements of the same bird and make a decision on how those data are to be treated.
b) Plot ECDFs of the beak depths of Geospiza scandens in 1975 and in 2012. Then, estimate the mean beak depth in for each of these years with confidence intervals.
c) Perform a hypothesis test comparing the G. scandens beak depths in 1975 and 2012. Carefully state your null hypothesis, your test statistic, and your definition of what it means to be at least as extreme as the test statistic. Comment on the results. It might be interesting to know that a severe drought in 1976 and 1977 resulted in the death of the plants that produce small seeds on the island.
d) Devise a measure for the shape of a beak. That is, some scalar measure that combines both the length and depth of the beak. Compare this measure between species and through time. (This is very open-ended. It is up to you to define the measure, make relevant plots, compute confidence intervals, and possibly do hypothesis tests to see how shape changes over time and between the two species.)
e) Introgressive hybridization, occurs when a G. scandens bird mates with a G. fortis bird, and then the offspring mates again with pure G. scandens. This brings traits from G. fortis into the F. scandens genome. As this may be a mode by which beak geometries of G. scandens change over time, it is useful to know how heritable a trait is. Heritability is defined as the ratio of the covariance between parents and offsprings to the variance of the parents alone. To be clear, the heritability is defined as follows.

Compute the average value of a trait in a pair of parents.

Compute the average value of that trait among the offspring of those parents.

Do this for each set of parents/offspring. Using this data set, compute the covariance among all average offspring and the variance among all average parents.

This is a more apt definition than, say, the Pearson correlation, because it is a direct comparison between parents and offspring.

Heritability data for beak depth for G. fortis and G. scandens are fortis_beak_depth_heredity.csv and scandens_beak_depth_heredity.csv, respectively. From these data, we will compute the heritability of beak depth in the two species, with confidence intervals and see how do they differ, and what consequences might this have for introgressive hybridization.
