# Introduction to National Negro Health Week Workset

National Negro Health Week (NNHW) began 105 years ago in April of 1915, in response to disturbing findings by the Tuskegee Institute that highlighted the poor health status of African Americans in the early part of the 20th Century. National Negro Health Week was an 8-day period Sunday to Sunday.

The National Negro Health News and National Negro Health Week workset is an archive of the history of Black Public Health between 1915 and 1950.  The workset includes the full run (1933-1950 (v.1-18)) of National Negro Health News, which was a quarterly bulletin for release of announcements and data for release of announcements and data on National Negro Health Week and the National Negro Health Movement. Between 1933 and 1950, the National Negro Health News Week serves as a major repository for data on Black Public Health.
 The workset also includes National Negro Health Week Annual Observance 1923-1945 (1915-1922 and 1946-1951 are missing in the workset).

The workset is the culmination of efforts that transform the National Negro Health News Week and The National Negro Health Week Annual observance into an archive of Black public health history, which can be explored, interrogated, and taken apart with computational analytics in HTRC. HTRC Analytics support “exploding” the corpus–breaking it down into basic components for targeted exploration. This workset, in its various forms, can also be combined with outside data to form part of a larger dataset for investigating historical questions of Black public health. Using the HathiTrust identifiers (HTIDs) for each volume in the workset, their full text can be analyzed via the [HTRC Data Capsule](https://wiki.htrc.illinois.edu/x/SAFRAQ); bag-of-words representations of each volume can be access via the[HTRC Extracted Features Dataset](https://wiki.htrc.illinois.edu/x/kYC2B), and the full volume metadata can be gathered using links to the catalog record in HathiTrust (e.g. [https://catalog.hathitrust.org/Record/000053099.marc](https://catalog.hathitrust.org/Record/000053099.marc)). For a more hands-off approach, this workset can also be explored using the built-in [algorithms of HTRC Analytics](https://analytics.hathitrust.org/statisticalalgorithms).

This workset can support a myriad of research questions and methodologies, with distinctions in suitability depending on the form of the data chosen for analysis. When downloaded in Extracted Features, this workset would be suitable for topic modeling, lexical analysis (such as word, sentence, and part-of-speech counting), as well as a number of word vector approaches (TF-IDF, or other types of word embedding methods). Using word vectors, this workset would also be suitable for training a machine learning model, perhaps to test differences between the volumes within and other sources, such as [a larger collection of US Federal documents issued by the Department of Health and Human Services](https://catalog.hathitrust.org/Search/Home?lookfor=%22United+States.+Dept.+of+Health+and+Human+Services.%22&type=author&inst=).

In full-text form, this workset would be suitable for almost any analysis methodologies, though varying levels of pre-processing of the data would be required. The data would be an excellent candidate for robust named entity recognition to extract people, organizational, and geographic proper names, or in-depth semantic analysis such as information density or complexity. If this workset is accessed through its page images. rather than its plain text form, researchers could study the pictures and figures contained in the volumes, as well as study the processes that could automate this work.


## How to use this workset

These are just some of the research methods this workset is suitable for, with many others also possible.

### Patterns in Geography

Extract Place Names - Can extract at the sentence level
- Run Name Entity recognition
- Run Geographical location 
- Consult on Tools
   - Geographic
   - Named Extraction Tool
   - [Stanford Named Entity Recognizer](https://nlp.stanford.edu/software/CRF-NER.html) (NER)
   - [Named Entity Recognizer (v2.0)](https://analytics.hathitrust.org/algorithms) - more name recognition not geographical place  
      - People should also be extracted 

### An extraction of all the photos in National Negro Health Week News - Public Domain anything before 1925

HathiTrust custom data request which will enable me to download page images and plain text OCR. This particular method is key as I am interested in extracting specific images, graphs, tables and other illustrations for the purpose of analyzing and re-making these materials in other formats.

### Topic Modeling 

- HathiTrust+Bookworm tool
- InPhO Topic Model Explorer (v1.0b225)

### Token Count and Tag Cloud Creator (v2.0)