# FakeJobPredictor

This project is based on the dataset from Kaggle. Employment scams are on the rise, especially those which have started to be conducted online ever. According to the FBI, the overall susceptibility for employment scams is 15.6%, with the median dollar loss being over one thousand dollars. the number of job frauds more than doubled in 2018 compared to 2017. Unemployment is at an all-time high due to the present market condition and coronavirus. These scammers prey on individuals who are hoping for a job, creating lucrative websites and emails looking immensely real.  For many people, economic hardship and the impact of the coronavirus have drastically reduced work availability and resulted in job loss. The majority of fraudsters do this to obtain personal information or money from the person they are attempting to defraud. PII such as bank account numbers, ID pictures, social security numbers are some examples.

This gathers all the necessary characteristics that construe a job posting. These job listings are classified as either genuine or fraudulent. Fake job advertisements make up a small part of this data collection. The dataset contains over 18,000 job descriptions, with roughly 800 of them being false.  The dataset could be used to train classification algorithms that can detect bogus job descriptions. The data is a combination of integer, binary and textual data types. Our dataset has a multitude of attributes, such as department, location, company_profile, requirement, benefits, etc. To determine if the job ad is genuine or not, the machine must process the content.

For this dataset we will be using various different classification machine learning algorithms to see which will result in the highest accuracy of classifying if a job is fraudulent or not. Additionally, we will look into natural language processing techniques to see if we can identify similarities that occur with fraudulent job postings. Ultimately, our goal will be to classify whether or not a job posting is genuine or not with the least amount of false positives.

https://www.kaggle.com/shivamb/real-or-fake-fake-jobposting-prediction
Above is the downloadable link for the 50 MB csv file

Libraries used:
- Numpy
- Pandas
- Seaborn
- Matplotlib
- Sklearn

Conclusion:

Plotting incidence of fraud by the job function shows Administrative and Engineering, Full-time and mid-senior  have the highest levels of fraudulent postings. So we should ensure to strictly meet function, employment type and required experience.
Using Random forest, we inferred that “company_logo” is playing a significant role in identifying a job as fake or not. So companies should ensure to have a company logo while posting jobs.
Using Decision Tree by adjusting the threshold we are able to get overall accuracy 83. 03 for identifying for the jobs
After applying  text analytics, result prediction of all models indicated that this problem was high sensitivity and low specificity problem.
We identified different classification machine learning algorithms to see which would result in the highest classification accuracy if a job was fast.
