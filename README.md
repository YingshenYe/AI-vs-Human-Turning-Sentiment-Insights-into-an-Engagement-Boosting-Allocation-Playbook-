## Overview

### The project studies linguistic and sentiment differences between AI-generated and human-written text to build a framework that decides which type of content should be produced by AI versus humans, with the goal of improving efficiency and reducing manual workload while maintaining engagement quality.

### The project analyzed about 487k texts labeled as AI-generated or human-written. I used topic modeling (LDA) and sentiment analysis (VADER) to identify differences in tone and themes between the two. One interesting finding was that AI-generated text tends to be more consistently positive and polite, while human-written text shows more variation in sentiment and emotional energy.

### Based on these features, I built a simple logistic regression framework that maps text into a content-allocation matrix. The idea is to determine which types of content (e.g., FAQs, ads, or storytelling) are better handled by AI versus humans. For example, the framework might assign AI to generate structured informational content such as FAQs, while human writers would be preferred for emotionally expressive content like advertisements or brand storytelling.

* The database source is mentioned in the jupite rnotebook file and it is from Kaggle.
* The project mainly focused on using text mining techniques, including NLP techniques to analize, including using vader score, cluster for topics etc...
* The project also investigates into whether human generated text is more energetic, while AI generated ones would be less energetic.
* Results showed that AI generated score would more be prone to positive sentiment and it is super polite, while human generated text may vary more with sentiments and energy.
