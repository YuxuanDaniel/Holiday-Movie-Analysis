# data

Place data file(s) in this folder.

Then, include metadata about your dataset including information on provenance, codebook, etc.

The codebook for your data file(s) using the following format.

## name of data file

|variable         |description |
|:----------------|:-----------|
|tconst           | alphanumeric unique identifier of the title |
|title_type       | the type/format of the title (movie, video, or tvMovie) |
|primary_title    | the more popular title / the title used by the filmmakers on promotional materials at the point of release |
|original_title   | original title, in the original language |
|year             | the release year of a title |
|runtime_minutes  | primary runtime of the title, in minutes |
|genres           | includes up to three genres associated with the title (comma-delimited) |
|simple_title     | the title in lowercase, with punctuation removed, for easier filtering and grouping |
|average_rating   | weighted average of all the individual user ratings on IMDb |
|num_votes        | number of votes the title has received on IMDb (titles with fewer than 10 votes were not included in this dataset) |
|christmas        | whether the title includes "christmas", "xmas", "x mas", etc |
|hanukkah         | whether the title includes "hanukkah", "chanukah", etc |
|kwanzaa          | whether the title includes "kwanzaa" |
|holiday          | whether the title includes the word "holiday" |
