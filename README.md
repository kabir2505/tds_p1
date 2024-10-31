## Data Collection Overview

- To grab the data, I checked out the GitHub API docs to get the lowdown on the endpoints and parameters I needed for my queries. I used the `requests` library to shoot out GET requests and pull in repository and user data. Then, I parsed the JSON responses into Pandas DataFrames for some deeper analysis.

- TypeScript is emerging as a major growth opportunity in Zurich’s market, boasting a 20% increase in demand compared to JavaScript. With just 15% of developers currently using it (lower competition), there’s a unique gap for developers to enhance their skills and marketability, positioning themselves ahead of the competition in this evolving landscape.

- Developers should strategically combine Python and TypeScript skills to enhance their job market appeal. Python offers 3,301 repositories and 86 hireable developers, while TypeScript is gaining traction in frontend development. By focusing on data-driven projects, developers can leverage Python’s versatility alongside TypeScript’s growth potential, creating a competitive edge in a rapidly evolving tech landscape.

**Note:** The dataset does not contain the entirety of 2024's days, as the year 2024 is not yet complete.
## Charts for the insights
### Language popularity over time 
![Data Chart](./imgs/language_popularity.png)

### Typescript trend 
![Data Chart](./imgs/typescript_trend.png)



## Files

- **users.csv**: Contains information about 475 GitHub users in Delhi with over 100 followers.
- **repositories.csv**: Contains information about 22,697 public repositories from these users.
- **gitscrap.py**: Python script used to collect this data.

## Data Collection

- Data collected using GitHub API.
- Date of collection: 2024-10-29.
- Only included users with 100+ followers.
- Up to 500 most recently pushed repositories per user.