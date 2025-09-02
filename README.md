Netflix Data Analysis Project

📌 Overview

This project analyzes the Netflix dataset to extract meaningful insights about movies and TV shows available on the platform. The dataset includes details such as directors, cast, country, ratings, genres, release year, and duration.

The goal is to perform exploratory data analysis (EDA), visualize patterns, and provide business recommendations that could help Netflix optimize its content strategy.

📊 Dataset

Rows: 8,807

Columns: 12

Key Features:

show_id – Unique ID

type – Movie / TV Show

title – Name of the content

director – Director(s)

cast – Actors

country – Country of production

date_added – Date when added to Netflix

release_year – Year of release

rating – Audience rating (TV-MA, PG-13, etc.)

duration – Duration of movies / number of seasons

genre – Categories/Genres

description – Short description

🔎 Exploratory Data Analysis (EDA)

Key analyses performed:

Movies vs TV Shows – ~2/3 are movies, ~1/3 are TV shows.

Top Directors & Actors – Rajiv Chilaka (Director) and Anupam Kher (Actor) appear most frequently.

Country-wise Contribution – U.S., India, U.K., Canada, and France contribute ~72% of Netflix content.

Genre Popularity – International Movies, Dramas, and Comedies dominate.

Content Growth Trend – Sharp growth between 2014–2018, decline after 2019.

Ratings Analysis – Majority of titles are TV-MA and TV-14.

Duration Analysis – Most movies are 87–114 mins; 67% of TV shows have only 1 season.

Month-wise Additions – July, December, and September see maximum additions.

💡 Business Insights

Movies dominate Netflix’s library (72%).

Indian actors (Anupam Kher, Shah Rukh Khan, Naseeruddin Shah) are highly featured.

U.S. leads in content production, followed by India and the U.K.

Content growth peaked in 2018, declined afterwards.

TV-MA is the most frequent rating, suggesting preference for mature content.

✅ Recommendations

Target Countries: Focus on content from U.S., India, U.K., Canada, and France.

Preferred Genres: International Movies, Dramas, Comedies (Movies) and International TV Shows, Dramas, Comedies (TV).

Content Duration:

Movies: Keep within 87–114 mins.

TV Shows: Prefer ≤3 seasons.

Best Months to Add Content: July, December, and September.

Preferred Directors & Actors:

Directors: Rajiv Chilaka, Jan Suter, Raúl Campos, Suhas Kadav, Marcus Raboy.

Actors: Anupam Kher, Shah Rukh Khan, Naseeruddin Shah (Movies).

Release Timing: Most effective on the 1st of each month.

Rating Strategy: Focus on TV-MA and TV-14 content.

🛠️ Tools & Libraries Used

Python

NumPy, Pandas – Data manipulation

Matplotlib, Seaborn – Data visualization

Jupyter Notebook – Analysis
