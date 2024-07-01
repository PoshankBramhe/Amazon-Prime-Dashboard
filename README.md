# Amazon-Prime-Dashboard


<h2>Overview</h2>
<p>This Power BI dashboard provides insights into Amazon Prime Video's vast collection of shows and movies. It allows users to explore data related to the types, ratings, genres, and geographical distribution of content available on the platform.</p>

<h2>Data Source</h2>
<p>The dataset used for this dashboard comprises the following columns:</p>
<ul>
    <li><strong>show_id:</strong> Unique identifier for each show/movie.</li>
    <li><strong>type:</strong> Indicates whether the entry is a "Movie" or a "TV Show".</li>
    <li><strong>title:</strong> Title of the show/movie.</li>
    <li><strong>director:</strong> Director of the show/movie.</li>
    <li><strong>cast:</strong> List of cast members.</li>
    <li><strong>country:</strong> Country where the show/movie was produced.</li>
    <li><strong>date_added:</strong> Date when the show/movie was added to the platform.</li>
    <li><strong>release_year:</strong> Year the show/movie was released.</li>
    <li><strong>rating:</strong> Age rating of the show/movie.</li>
    <li><strong>duration:</strong> Duration of the show/movie (e.g., number of seasons for TV shows or runtime for movies).</li>
    <li><strong>listed_in:</strong> Genres associated with the show/movie.</li>
    <li><strong>description:</strong> Brief description of the show/movie.</li>
</ul>

<h2>ETL Process</h2>

<h3>Extraction</h3>
<p>The raw data was extracted from the provided dataset. The data was collected and compiled from various sources to ensure comprehensiveness.</p>

<h3>Transformation</h3>
<p>The transformation process included:</p>
<ul>
    <li><strong>Data Cleaning:</strong>
        <ul>
            <li>Removed duplicate entries.</li>
            <li>Filled in missing values where applicable.</li>
            <li>Standardized date formats and categorical entries.</li>
        </ul>
    </li>
    <li><strong>Data Enrichment:</strong>
        <ul>
            <li>Categorized data based on ratings, genres, and countries.</li>
            <li>Calculated the total count of shows/movies per category.</li>
        </ul>
    </li>
    <li><strong>Data Aggregation:</strong>
        <ul>
            <li>Grouped data by country, type, and genre to facilitate analysis.</li>
            <li>Created time-series data for trends over the years.</li>
        </ul>
    </li>
</ul>

<h3>Loading</h3>
<p>The cleaned and transformed data was loaded into Power BI for visualization.</p>

<h2>Insights & Visualizations</h2>
<p>The dashboard offers the following insights:</p>
<ul>
    <li><strong>Total Show Distribution</strong>
        <ul>
            <li><strong>Geographical Distribution:</strong> Displays the count of shows/movies by country, highlighting regions with the most extensive content.</li>
        </ul>
    </li>
    <li><strong>Show Count Over Time</strong>
        <ul>
            <li><strong>Trend Analysis:</strong> Shows the growth in the number of shows/movies added to the platform over time, indicating trends in content production.</li>
        </ul>
    </li>
    <li><strong>Ratings Distribution</strong>
        <ul>
            <li><strong>Content Rating:</strong> Displays the distribution of content based on age ratings, providing insights into the platform's family-friendly or adult-oriented content.</li>
        </ul>
    </li>
    <li><strong>Type Distribution</strong>
        <ul>
            <li><strong>Content Type:</strong> Pie chart showing the proportion of TV shows versus movies available on the platform.</li>
        </ul>
    </li>
    <li><strong>Genre Analysis</strong>
        <ul>
            <li><strong>Top Genres:</strong> Bar chart showing the top genres by the number of shows/movies, helping to identify popular content themes.</li>
        </ul>
    </li>
</ul>

<h2>Usage</h2>
<p>This dashboard can be used by:</p>
<ul>
    <li><strong>Content Analysts:</strong> To understand the distribution and trends in content available on Amazon Prime Video.</li>
    <li><strong>Marketing Teams:</strong> To identify popular genres and ratings for targeted campaigns.</li>
    <li><strong>Content Creators:</strong> To explore gaps in content and opportunities for new productions.</li>
</ul>

<h2>Future Enhancements</h2>
<p>Incorporating user ratings and reviews for more in-depth analysis.</p>
<p>Adding filters for more granular analysis of content by specific directors or cast members.</p>
<p>Enhancing the geographical analysis with additional demographic data.</p>

