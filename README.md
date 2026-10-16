# Netflix-Movie-Data-Analytics-

# Project Overview
This project analyzes Netflix's library of movies and TV shows to understand what content Netflix offers, who their target audience is, and which countries produce the most titles.

# Industry Type (Entertainment & Media)
Dataset Size: 8,797 Total Titles

# Story of Data
In its early streaming days, Netflix was mainly a place to watch licensed movies and older TV shows from Hollywood studios. Growth was slow and steady, and the catalog was mostly movies.

Around 2015–2016, traditional studios began pulling their content to launch their own streaming apps. Netflix pivoted by aggressively producing its own Netflix Originals. This led to massive growth between 2016 and 2020. Netflix added thousands of movies and heavily expanded its TV show library to keep viewers coming back. To keep growing, Netflix also shifted to global production, making international content and focusing primarily on mature audiences (Teens and Adults).

# Stakeholder Interests (Why This Analysis Matters)
Content Licensing Team: Identifies which genres and formats (Movies vs. TV Shows) to buy next to fill content gaps.

Studio Executives: Evaluates ideal movie runtimes (90–110 minutes) and show performance to guide new productions.

Global Expansion Team: Tracks country trends (e.g., Indian Movies vs. South Korean Dramas) to expand in international markets.

Marketing Team: Uses content rating splits (TV-MA, TV-14) to target advertising campaigns to the right age groups.

Executive Leadership: Monitors overall platform growth, catalog health, and high-level metrics (8,797+ titles).

# Potential Analysis & Analytical Insights
1. How fast did Netflix grow over the years?
Insight: Growth was slow before 2015, but skyrocketed between 2016 and 2020 when Netflix expanded into producing its own original shows and movies.

2. What percentage of Netflix content is Movies vs. TV Shows?
Insight: Movies make up the majority of the library at 69.69% (6,131 titles), while TV Shows make up 30.31% (2,666 titles). However, TV shows drive higher long-term viewing hours.

3. Which top countries produce the most content?
Insight: The United States leads by a huge margin, followed by India and the UK. India produces mostly Movies, whereas South Korea and Japan focus heavily on TV Shows.

4. Target Audience (Who is content made for)?
Insight: Most content is rated TV-MA (Adults) or TV-14 (Teens). Netflix focuses primarily on young adults and mature audiences rather than young children.

5. What are the most common content genres?
Insight: Dramas, Comedies, and International Movies/Shows make up more than half of all options available on Netflix.

6. Movie Length (Runtime): How long are most movies?
Insight: Most feature movies on Netflix run between 90 and 110 minutes.

# Project Variables
Independent Variables (Inputs / Category Filters)

Release Year: The original year the title came out.

Date Added / Year Added: The date or year Netflix added the title to its app.

Type: Content category (Movie vs. TV Show).

Country: Country where the content was made.

Rating: Maturity classification (e.g., TV-MA, PG-13).

Listed In: Assigned genres or categories.

# Dependent Variables (Metrics / Calculated Outputs)
Count of Show ID: Total number of titles in a category.

Duration Value: Length of movies (minutes) or length of TV shows (seasons).

Type Distribution (%): Percentage split of Movies versus TV Shows.

# Tools Used
Power Query Editor: Cleaned data, removed duplicates, and handled missing values.

Power BI Desktop: Built dashboard visuals and layout.

DAX: Calculated total summary counts and percentage splits.

# Key Numbers & Statistics
Total Titles: 8,797

Movies: 6,131 (69.69%)

TV Shows: 2,666 (30.31%)

# Target Audience Breakdown
Adults: 4,092 titles

Teens: 2,647 titles

Kids & Children: 2,054 titles

# Top 5 Country Origins
United States: 2,812 titles

India: 972 titles

Unknown / Missing Data: 830 titles

United Kingdom: 418 titles

Japan: 244 titles

# General Observations & Findings

Content Split: The overall catalog consists of 8,797 titles, heavily weighted toward 6,131 movies (69.69%) compared to 2,666 TV shows (30.31%).

Growth Trends: Content growth stayed low and flat prior to 2000, then accelerated exponentially after 2010 to reach a sharp peak between 2018 and 2020 before tapering off.

Expansion Rates: Movie additions surged at a much higher rate than TV show additions during the post-2010 peak expansion period.

Top Producers: The United States leads global production by a large margin with 2,812 titles, followed by India (972 titles), the United Kingdom (418 titles), and Japan (244 titles).

Data Quality: A total of 830 titles are missing country metadata and register as "Unknown".

Demographics: Content rated for Adults represents the largest demographic segment at 4,092 titles, followed by Teen content at 2,647 titles and Kids & Children content at 2,054 titles.

# General Recommendations
Rebalance Content Format: Invest more in multi-season TV shows to keep subscribers engaged long-term.

Fix Missing Data: Clean up the 830 "Unknown" country titles to improve reporting accuracy.

Expand Regional Markets: Build on strong momentum in India and Japan by expanding production in Latin America, East Asia, and Africa.
Optimize Content Licensing: Focus original budgets on Adult and Teen shows, while using cheaper licensing deals for Children's content.
