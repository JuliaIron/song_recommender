# Song Recommender Project with Web Scraping and Spotify API

Team: Andres, Julia, Diana

### 💼 Business Case <a class="anchor" id="first-bullet-point"></a>

"Gnod" is a site that provides recommendations for music, art, literature and products based on collaborative filtering algorithms. Their flagship product is the music recommender, which you can try at www.gnoosic.com. The site asks users to input 3 bands they like, and computes similarity scores with the rest of the users. Then, they recommend to the user bands that users with similar tastes have picked.

"Gnod" is a small company, and its only revenue stream so far are adds in the site. In the future, they would like to explore partnership options with music apps (such as Deezer, Soundcloud or even Apple Music and Spotify). However, for that to be possible, they need to expand and improve their recommendations.

That's precisely where you come. They have hired you as a Data Analyst, and they expect you to bring a **mix of technical expertise and business mindset** to the table.

### 📝 Tasks <a class="anchor" id="second-bullet-point"></a>

* One of the new features we'd like to research is to recommend songs (not only bands). We're also aware of the limitations of our collaborative filtering algorithms, and would like to give users two new possibilities when searching for recommendations:

    * Songs that are actually similar to the ones they picked from an acoustic point of view.
    * Songs that are popular around the world right now, independently from their tastes.

* We want you to explore new data sources for songs. Feel free to use APIs or directly scrape the web to collect as much information as possible from popular songs. 

* Once the data is collected, we create clusters of songs that are similar to each other.                                                                               The idea is that if a user inputs a song from one group, we'll prioritize giving them recommendations of songs from that same group.

* Be open minded about this process: we are agile, and that means that we define our products and features on-the-go, while exploring the tools and the data that's available to us. We'd love you to provide your own vision of the product and the next steps to be taken.

### 🎵 Music Recommender Workflow <a class="anchor" id="third-bullet-point"></a>

![image](https://github.com/JuliaIron/song_recommender/blob/main/music_recommender_workflow.PNG)

### 🛠️ Build with <a class="anchor" id="fourth-bullet-point"></a>

* Spotify Web API
* Spotipy - Python wrapper for Spotify Web API

### 💻 Unsupervised Machine Learning <a class="anchor" id="fifth-bullet-point"></a>

* K-Means
* Beautiful Soup
* Scikit-learn with StandardScaler
* Pickle Python

