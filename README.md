# NLP Gender Detection - Instagram And Twitter Users

Social Gender Detection is a project aimed at predicting the gender of Twitter and Instagram users based on their profiles and activity. Social media networks offer vast opportunities for analysis, from entertainment to behavioral pattern recognition. By leveraging user-generated content, we can identify behavioral trends and potentially uncover insights relevant to various domains, including business intelligence.

## Dataset Description

We use a dataset comprising 10,000 samples for both training and validation purposes.
We utilize a dataset provided by [Dataak](https://dataak.com/) comprising information from Twitter and Instagram users. The dataset includes the following columns:

- **gender**: Target column indicating the gender of the user.
- **age**: Age range of the user.
- **fullname**: User's name as displayed on their social media profile.
- **username**: User's account username.
- **biography**: User's biography or description on their social media profile.
- **follower_count**: Number of followers of the user.
- **following_count**: Number of accounts the user is following.
- **is_business**: Indicator for whether the user account is associated with a business.
- **is_verified**: Indicator for whether the user account is verified.
- **is_private**: Indicator for whether the user account is private.

The age column represents discrete age categories rather than continuous variables.

| Actual Age Range of Users | Encoded Numeric Representation |
|----------------------------|--------------------------------|
| Less than 18 years         | 1                              |
| 19-29 years                | 2                              |
| 30-40 years                | 3                              |
| Above 40 years             | 4                              |

## Gender Detection Methodology

In this project, we employ various features to predict the gender of users. These features include:

- Analysis of user's name and username.
- Examination of the user's biography.
- Counting the number of emojis in the biography.
- Counting the lenght of biography.
- Utilizing follower and following counts.
- Considering account verification status, business association, and privacy settings.
- Age

## How to Contribute

Contributions to this project are welcome! If you have ideas for enhancements or wish to contribute to the codebase, please send me your idea with E-Mail.

Thank you for your interest in Social Gender Detection!
