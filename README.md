# nlp-resume-job-matcher
Matching relevant candidates to the Job for job portal sites using NLP:

Finding relevant job candidates for a particualr job is a headache especially if you're looking for niche candidates for your jobs
So the idea is to Rank how well the candidates match with the job description based on the resume they upload against that particular job.
This ranking mechanism can help you find most relevant candidates.

Steps:

1) Create word2vec model from scratch(and since this one is for technology related jobs) we can download data from stackoverflow websites
2) Download data from stackexchange sites(which is collection of QA websites like stackoverflow,  ai.stackexchange, softwareengineering.stackexchange etc.)
3) Train word2vec model on the data
4) Convert Job Description and Parsed resume to word2vec vectors 
5) Get document similarity scores between Job Description and Parsed Resumes and rank them.
