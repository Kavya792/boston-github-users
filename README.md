GitHub Users in Boston with Over 100 Followers
Project Summary
Data Scraping Process: We used the GitHub API to retrieve detailed information on GitHub users in Boston with over 100 followers, along with up to 500 of their most recent repositories.
Interesting Finding: A significant proportion of Boston-based GitHub users with high follower counts contribute to open-source projects in Python and JavaScript.
Recommendation for Developers: Engaging more in collaborative projects and focusing on popular languages like Python and JavaScript could improve visibility and follower growth.
Overview
This project uses the GitHub API to gather information about users in Boston with over 100 followers. It provides insights into their activity, repositories, and popular technologies. The data collected is structured in CSV files for easy analysis.

Files in This Repository
users.csv: Contains detailed user information, including GitHub username, name, company, location, email, bio, number of public repositories, followers, and when they joined.
repositories.csv: Contains information on the repositories associated with each user, including repository name, creation date, star count, language, and license type.
README.md: Provides an overview of the project, findings, and recommendations.
Data Collection Methodology
Identifying Users: Using the GitHub Search API, we located users in Boston with over 100 followers. The location:Boston and followers:>100 filters allowed us to refine the search efficiently.
User Data Extraction: For each user, we retrieved details such as their name, bio, company, and follower counts. Company names were cleaned to ensure consistency (e.g., stripping extra spaces and converting to uppercase).
Repository Data Extraction: For each user, we fetched up to 500 of their most recent repositories. Data fields like stargazers_count, language, and license provide insights into the repository’s popularity and technology.
Key Findings
After analyzing the data, several insights were uncovered:

Technology Stack: Boston developers with high followers often favor Python, JavaScript, and TypeScript, suggesting these languages are both popular and highly collaborative.
Repository Engagement: Repositories with detailed documentation and an active wiki tend to have higher engagement, indicated by stars and watchers.
Recommendations
For developers seeking to grow their followers, we recommend:

Active Participation: Contribute to high-visibility projects and leverage popular languages like Python and JavaScript.
Repository Documentation: Improve repository documentation, enabling other developers to engage and collaborate more easily.
