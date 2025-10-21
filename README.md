# Qidian-Webnovel-Corpus

An brief introduction to the **Qidian-Webnovel** Corpus.

The corpus creation process involved a manual search for translated novels available on **Webnovel.com** within the **NOVEL** category, only targeting **completed works**.

Subsequently, each identified translated novel was mapped with its original counterpart on **Qidian.com**. 

As a result, we got 120 novels (from which 10 of these novels' copyright on Qidian.com had expired, so no data for this 10 novels on Qidian) 

The final corpus consists of **110** novels, and all the reader comments and replies to the novels. (Timestamp 01/09/2024)

Comments and replies are catergorised by **book-level**, **chapter-level** and **paragraph level**, and stored by per novel.

We also collected the user profiles of readers who has left comments or replies on the novels. 
**We only collect personal data that are necessary for the purpose of the scientific research, and strictly abid by the GDPR.**


**About the data**

**bookList**: This csv file contain the mapping link for the same story published on both qidian and webnovel. The final corpus consists of 110 stories. According to WebNovel’s categorisation visible on the website interface, these 110 stories consist of 103 Male Lead and 7 Female Lead. 

**qidianFreeChapterDates**: This zip file contains CSV files, each named by its corresponding Qidian bookID. Each CSV file contains the publication dates for all free available chapters of that story in the dataset.

**qidianFreeChapterIds**: This zip file contains text files, each named by its corresponding Qidian bookID. Each text file contains the unique IDs for all free chapters of that story.

**qidianFreeChapterMeta**: This zip file contains CSV files, each named by its corresponding Qidian bookID. Each CSV file contains metadata for all chapters of that book, including the number of reviews received for each paragraph (reviewNum), chapterID, and bookID.

**webnovelFreeChapterDates**: This zip file contains CSV files, each named by its corresponding WebNovel bookID. Each CSV file contains metadata for the free available chapters, including their publish time and update time.

**webnovelFreeChapterIds**: This zip file contains CSV files, each named by its corresponding WebNovel bookID. Each CSV file contains the chapterID and chapter title for all free available chapters.

**webnovelFreeChapterMeta**: This zip file contains CSV files, each named by its corresponding WebNovel bookID. Each CSV file contains metadata for all chapters of that book, including the number of reviews received for each paragraph (reviewAmount), paragraphID, chapterID, and bookID.





**License**


This dataset is partially (story metadata, chapter metadata, and story mappings) released under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

The depersonalized reader response data included in this dataset is subject to a separate **Data Transfer Agreement**. Users must review and accept the DTA before accessing or using the reader comments data. 

- Terms of Use
  -  Researchers affiliated with universities or not-for-profit research institutes may use the Qidian-Webnovel Corpus 110 dataset for conducting not-for-profit scientific research, in accordance with the Data Transfer Agreement provided by the University of Groningen.

- Restrictions
  -  The files with restricted access are not open in order to be able to comply with third party licenses and to mitigate a risk of re-identification in terms of the GDPR. It is not allowed to disclose the full version of the Qidian-Webnovel Corpus 110 dataset to any third party or otherwise use it for your own benefit or for the benefit of a third party, without first obtaining written consent from the University of Groningen. 

- Terms of Access
  -  Permission for access can be granted by the University of Groningen Digital Competence Centre on behalf of the researcher(s) responsible for this dataset after assessment of credentials of the applicant and the reasons for the request. The signing of a Data Transfer Agreement is part of the procedure before access can be granted.
The procedure starts with a request for access via this dataset at DataverseNL.

For more information about the dataset, you can reach out to z.yu@rug.nl.



