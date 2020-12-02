# Data science and music?
Have you ever wondered how the artists of two different music genres might be connected? If so, you've come to the right place. This webpage provides an exploration of the Wikipedia pages of artists from the two genres "West Coast Hip Hop" and "Dance Pop", using links between the pages to create a network connecting all artists. This network contains several communities, which are further explored. The Wikipedia pages provide a large amount of text, allowing for text and sentiment analysis of artists as well as communites. By including lyrics from some of the songs associated with the artists, it is also possible to explore sentiments of lyrics and investigate how these sentiments change over time.

# Selecting genres and retrieving data
- network overview?
<img src="images/BasicGraph.png" alt="hi" class="inline"/>

# Delving into the network and calculating some basic statistics

- Insert degree distributions

- Insert network plot
<center>
{% include graph_output.html %}
</center>

# Defining genres with words

- Insert wordclouds for the two genres.

<img src="images/DancePop.png" alt="hi" class="inline"/>

<img src="images/WestCoast.png" alt="hi" class="inline"/>

# Finding communities within network

- Show the network, colored by communities.

- List the artists in the communities

**Community 1:**

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

- Madonna (Dance Pop)
- Britney Spears (Dance Pop)
- Rihanna (Dance Pop)
- Michael Jackson (Dance Pop)
- Janet Jackson (Dance Pop)
- Lady Gaga (Dance Pop)
- Nicki Minaj (Dance Pop)
- Mariah Carey (Dance Pop)
- Katy Perry (Dance Pop)
- Justin Timberlake (Dance Pop)

**Community 2:**
- Kendrick Lamar (West Coast)
- Chris Brown (Dance Pop)
- Wiz Khalifa (West Coast)
- Dom Kennedy (West Coast)
- Tyga (West Coast)
- Problem (West Coast)
- Alchemist (West Coast)
- Ty Dolla $ign (West Coast)
- YG (West Coast)
- Schoolboy Q (West Coast)

Community 3:

Paris (West Coast)
Subnoize Souljaz (West Coast)
Kottonmouth Kings (West Coast)
Havoc (West Coast)
Young Murder Squad (West Coast)
Kingspade (West Coast)
Potluck (West Coast)
Delinquent Habits (West Coast)
Hed PE (West Coast)
Sen Dog (West Coast)


Community 4:

Planet Asia (West Coast)
Dilated Peoples (West Coast)
Murs (West Coast)
Gorillaz (Dance Pop)
Evidence (West Coast)
Del the Funky Homosapien (West Coast)
People Under The Stairs (West Coast)
Pigeon John (West Coast)
The Grouch (West Coast)
Domino (West Coast)

Community 5:

Exposé (Dance Pop)
Xuxa (Dance Pop)
Company B (Dance Pop)
Will to Power (Dance Pop)
Mars (West Coast)
The Cover Girls (Dance Pop)
t.A.T.u. (Dance Pop)
Lisa Lisa and Cult Jam (Dance Pop)

Community 6:

Snoop Dogg (West Coast)
Dr. Dre (West Coast)
Ice Cube (West Coast)
The Game (West Coast)
Tha Dogg Pound (West Coast)
Kurupt (West Coast)
Eazy-E (West Coast)
N.W.A (West Coast)
DJ Quik (West Coast)
Kam (West Coast)

<img src="images/CommunityGraph.png" alt="hi" class="inline"/>

- Show a distribution plot of the number of nodes in each community

- Wordcloud + sentiment analysis

# Songs and sentiment over time

- Sentimentanalysis over time

- Wordclouds based on songs for some the five biggest nodes in the artist network

