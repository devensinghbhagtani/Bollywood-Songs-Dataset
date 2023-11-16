# Bollywood Songs Dataset (2017-2023)
This dataset contains information about Bollywood songs including music names, singers, album names, release years, <b>lyrics and thumbnails</b> collected from various sources. This dataset aims to address the gap in existing Bollywood song datasets available online by providing up-to-date information with lyrics and thumbnail columns, which are often missing or outdated in other repositories.

## Dataset Overview
Existing datasets available on the internet often lack lyrics and thumbnail columns or contain outdated information. This dataset bridges this gap by offering the most recent and comprehensive collection of Bollywood songs with associated metadata and multimedia elements.

## Columns:
- music_name: Name of the Bollywood song.
- singer: Singer(s) of the song.
- album_name: Name of the album the song belongs to.
- release: Release year of the song.
- lyrics: Lyrics of the song.
- thumbnail: URLs of thumbnails fetched from YouTube for respective songs.

## Data Collection Process
The data was collected through Python using the Pandas library for data handling, Beautiful Soup for web scraping AZLyrics, and Google's YouTube API for fetching thumbnails.<br>
Note:
AZLyrics enforces limitations on frequent page visits and might enforce IP bans after a certain threshold. The web scraping process might be affected by these limitations.

## Usage
- Researchers, data enthusiasts, and Bollywood enthusiasts can utilize this dataset for various analytical, exploratory, or educational purposes.
- The availability of lyrics enables the creation of content-based recommendation systems or similarity matrices based on song content.

## Acknowledgments
    1) AZLyrics: For providing song-related information.
    2) YouTube API: For facilitating the collection of song thumbnails.
