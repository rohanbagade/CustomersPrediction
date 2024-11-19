# CustomersPrediction
This is my second project I completed as part of the MIT Data Science and Machine Learning Certification. The project predicts whether a potential lead for online education would convert to a paid customer. Random Forest and Decision tree were used to determine results.

Conclusions: Time spent on website and first interaction being website appeared as 2 of the most important features in both the random forest and decision tree. An actionable step that could be taken is to make the website more user friendly and engaging. Try to get more potential leads to interact with website maybe with more advertisement.

Younger leads below the age of 25 are also less likely to convert from a lead to a customer. Student discounts is a great option to attract more from the younger crowd.

Leads with high profile completion also were more likely to convert. Send more email notifications for customers to complete profile.

The predicting variables were 
ID: ID of the lead age: Age of the lead 
current_occupation: Current occupation of the lead. Values include 'Professional', 'Unemployed', and 'Student' 
first_interaction: How did the lead first interact with ExtraaLearn? Values include 'Website' and 'Mobile App'
profile_completed: What percentage of the profile has been filled by the lead on the website/mobile app? Values include Low - (0-50%), Medium - (50-75%), High (75-100%) 
website_visits: The number of times a lead has visited the website time_spent_on_website: Total time (seconds) spent on the website. 
page_views_per_visit: Average number of pages on the website viewed during the visits last_activity: Last interaction between the lead and ExtraaLearn
Email Activity: Seeking details about the program through email, Representative shared information with a lead like a brochure of the program, etc.
Phone Activity: Had a phone conversation with a representative, had a conversation over SMS with a representative, etc. 
Website Activity: Interacted on live chat with a representative, updated profile on the website, etc.
print_media_type1: Flag indicating whether the lead had seen the ad of ExtraaLearn in the Newspaper
print_media_type2: Flag indicating whether the lead had seen the ad of ExtraaLearn in the Magazine
