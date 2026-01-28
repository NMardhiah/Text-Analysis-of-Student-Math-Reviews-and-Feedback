## Key Insights from Analysis
Through the NLP pipeline, several critical patterns were identified:

The "Practice" Correlation: Word co-occurrence mapping showed that the term "Understand" was most frequently linked with "Practice" and "Exercises." This suggests students view repetitive application as the primary path to comprehension.

Sentiment Tension: While overall sentiment remained cautiously optimistic (high frequency of "Hope"), subjectivity scoring revealed that topics involving "Calculations" triggered the highest levels of negative polarity, correlating with "math anxiety."

Aspiration vs. Reality: The Word Cloud highlights that while students are "Worried," their goal is mastery ("Best," "Understand"), indicating a high level of student engagement despite the perceived difficulty.

## Technical Methodology
This project follows a standard NLP workflow:

Data Cleaning: Removal of stop-words and noise from student reviews.

Translation: Normalizing multilingual feedback (Malay to English) for consistent processing.

Tokenization & Frequency Mapping: Using NLTK to break down text and identify dominant themes.

Sentiment Scoring: Applying the VADER (Valence Aware Dictionary and sEntiment Reasoner) Lexicon to assign polarity scores to each review.

## Tools Used
Language: Python 3.x

Libraries: * Pandas (Data manipulation)

Matplotlib/WordCloud (Visualization)

NLTK (Natural Language Toolkit)

VADER (Sentiment Analysis)


<img width="1000" height="500" alt="student_feedback_wordcloud" src="https://github.com/user-attachments/assets/41459927-0578-4585-aab5-ff40894a59e6" />
