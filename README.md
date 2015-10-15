polarHistogram builds many  histogram and arranges them around a circle to save space.
C. Ladroue, after Kettunen, J. et al. Genome-wide association study identifies multiple loci influencing human serum metabolite levels. Nat Genet advance online publication (2012). URL http://dx.doi.org/10.1038/ng.1073.
CC licence: http://creativecommons.org/licenses/by-nc-sa/3.0/ 
Attribution - You must attribute the work in the manner specified by the author or licensor (but not in any way that suggests that they endorse you or your use of the work).
Noncommercial - You may not use this work for commercial purposes.
Share Alike - If you alter, transform, or build upon this work, you may distribute the resulting work only under the same or similar license to this one. 

v. 21022012

The data frame is expected to have at least four columns: family, item, score and value. 
The three first columns are categorical variables, the fourth column contains non-negative values.
See testPolarHistogram.R for an example.
Each bar represents the proportion of scores for one item. Items can be grouped by families.
The resulting graph can be busy and might be better off saved as a pdf, with ggsave("myGraph.pdf").
