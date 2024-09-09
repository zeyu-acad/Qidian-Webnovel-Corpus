# Qidian-Webnovel-Corpus

An brief introduction to the Qidian-Webnovel Corpus

The corpus creation process involved a manual search for translated novels available on Webnovel.com within the NOVEL category, only targeting completed works.
Subsequently, each identified translated novel was mapped with its original counterpart on Qidian.com. 
As a result, we got 120 novels (from which 10 of these novels' copyright on Qidian.com had expired, so no data for this 10 novels on Qidian) 
The final corpus consists of 110 stories. 

According to WebNovel’s categorization, these 110 stories consist of 103 Male Lead and 7 Female Lead. 
We scraped the metadata from each platform and the respective comments and replies for each story, including the user profile of the readers who left the comments. 

Source	CommentId	Comment Content	ReplyId	Reply Content	BookId	UserId	User Level	Rating Score	Reply Amount	Like Amount	Create Time	Quote	ReviewId	Quote Content	Quote UserId
WebNovel (EN)	✓	✓	✓	✓	✓	✓	✓	✓	✓	✓	✓	✓	✓	✓	✓
Qidian (CN)	✓	✓	✓	✓	✓	✓	✓	-	✓	✓	✓	✓	✓	✓	✓

Table 1 has shown the metadata for
comments and replies, based on the information provided, we could also map the interactions between
comments and their replies.
Source CommentId Comment Content ReplyId Reply Content BookId UserId User Level Rating Score Reply Amount Like Amount Create Time Quote ReviewId Quote Content Quote UserId WebNovel (EN) ✓ ✓ ✓ ✓ ✓ ✓ ✓ ✓ ✓ ✓ ✓ ✓ ✓ ✓
Qidian (CN) ✓ ✓ ✓ ✓ ✓ ✓ ✓ - ✓ ✓ ✓ ✓ ✓ ✓
Table 1
Corpus Metadata for WebNovel (EN) and Qidian (CN)
The length of the novels exhibits a wide range, spanning from 288 to 3,588 chapters, with correspond￾ing word counts varying between 1,027,000 and 8,448,900 (measured in Chinese characters). Notably,
there is a slight difference in the genres and categories of stories on Qidian and WebNovel.
We also collected the user profiles of readers who has left comments or replies on the stories, as
shown in Table 2.
Source UserId User Name Gender Level/levelInfo Writing Days Reading Hours Num of Read Books Description Date Joined Location Num Followers
WebNovel (EN) ✓ ✓ ✓ ✓ ✓ ✓ ✓ ✓ ✓ ✓ -
Qidian (CN)✓ ✓ ✓ ✓ ✓ - - ✓ ✓ - ✓ ✓
Table 2
User Metadata for WebNovel(EN) and Qidian(EN)
Unlike Qidian where the readership is mainly native Chinese speakers or overseas Chinese-using
groups, readers on WebNovel do not necessarily come from the same region. We looked into the
location distribution of readers in the dataset, using the location available on the users profiles. For the
WebNovel dataset, we have the readers from 244 countries, and the top 10 locations with the most users
are shown in Table 3.
Location Number Percentage (%)
Global 55100 42.80
United States 15891 12.30
Philippines 14425 11.20
India 9591 7.40
Indonesia 3231 2.50
Nigeria 2972 2.30
Malaysia 2277 1.70
Canada 2046 1.50
Australia 1602 1.20
United Kingdom 1584 1.20
Brazil 1478 1.10
Table 3
Location Distribution of users on WebNovel(EN)
We have also taken into account that book comments left on WebNovel are not necessarily in English,
so we looked into the language distribution of comments and replies using automatic language detection.
1The corpus metadta and the code for the analysis are available at https://github.com/redacted
Source Genres Categories/Tags Total Comments Replies Primary Language Comments Language Distribution Replies Language Distribution
Qidian.com 14 27 2,791,837 855,577 Chinese Chinese: 95.7%, English: 0.1% Chinese: 97.2%, English: 0.05%
Webnovel.com 8 40 327,988 96,250 English English: 72.7%, Others: 27.3% English: 68.2%, Others: 31.8%
Table 4
Metadata for stories on both platforms
The results (Table 4) show that English comments accounted for 72.7% of the total replies, and English
replies accounted for 68.2% of the total replies. All other languages only account for no more than 2%
of the comments/replies each. Given that our research is focused on comparing Chinese and English
readerships, we only consider replies and comments written in English.
