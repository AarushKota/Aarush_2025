---
title: Jupyter Notebook
permalink: /jupyternotebook
---

```python
from emoji import emojize 
print(emojize(":thumbs_up: Piggy Yak That Has Ostrich Nose :grinning_face:"))
```

    👍 Piggy Yak That Has Ostrich Nose 😀



```python
!pip install newspaper3k
```

    Requirement already satisfied: newspaper3k in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (0.2.8)
    Requirement already satisfied: beautifulsoup4>=4.4.1 in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from newspaper3k) (4.12.3)
    Requirement already satisfied: Pillow>=3.3.0 in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from newspaper3k) (10.4.0)
    Requirement already satisfied: PyYAML>=3.11 in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from newspaper3k) (6.0.2)
    Requirement already satisfied: cssselect>=0.9.2 in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from newspaper3k) (1.2.0)
    Requirement already satisfied: lxml>=3.6.0 in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from newspaper3k) (5.3.0)
    Requirement already satisfied: nltk>=3.2.1 in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from newspaper3k) (3.9.1)
    Requirement already satisfied: requests>=2.10.0 in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from newspaper3k) (2.32.3)
    Requirement already satisfied: feedparser>=5.2.1 in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from newspaper3k) (6.0.11)
    Requirement already satisfied: tldextract>=2.0.1 in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from newspaper3k) (5.1.2)
    Requirement already satisfied: feedfinder2>=0.0.4 in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from newspaper3k) (0.0.4)
    Requirement already satisfied: jieba3k>=0.35.1 in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from newspaper3k) (0.35.1)
    Requirement already satisfied: python-dateutil>=2.5.3 in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from newspaper3k) (2.9.0.post0)
    Requirement already satisfied: tinysegmenter==0.3 in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from newspaper3k) (0.3)
    Requirement already satisfied: soupsieve>1.2 in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from beautifulsoup4>=4.4.1->newspaper3k) (2.6)
    Requirement already satisfied: six in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from feedfinder2>=0.0.4->newspaper3k) (1.16.0)
    Requirement already satisfied: sgmllib3k in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from feedparser>=5.2.1->newspaper3k) (1.0.0)
    Requirement already satisfied: click in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from nltk>=3.2.1->newspaper3k) (8.1.7)
    Requirement already satisfied: joblib in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from nltk>=3.2.1->newspaper3k) (1.4.2)
    Requirement already satisfied: regex>=2021.8.3 in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from nltk>=3.2.1->newspaper3k) (2024.7.24)
    Requirement already satisfied: tqdm in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from nltk>=3.2.1->newspaper3k) (4.66.5)
    Requirement already satisfied: charset-normalizer<4,>=2 in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from requests>=2.10.0->newspaper3k) (3.3.2)
    Requirement already satisfied: idna<4,>=2.5 in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from requests>=2.10.0->newspaper3k) (3.8)
    Requirement already satisfied: urllib3<3,>=1.21.1 in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from requests>=2.10.0->newspaper3k) (2.2.2)
    Requirement already satisfied: certifi>=2017.4.17 in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from requests>=2.10.0->newspaper3k) (2024.8.30)
    Requirement already satisfied: requests-file>=1.4 in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from tldextract>=2.0.1->newspaper3k) (2.1.0)
    Requirement already satisfied: filelock>=3.0.8 in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from tldextract>=2.0.1->newspaper3k) (3.16.0)



```python
!pip install wikipedia
```

    Requirement already satisfied: wikipedia in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (1.4.0)
    Requirement already satisfied: beautifulsoup4 in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from wikipedia) (4.12.3)
    Requirement already satisfied: requests<3.0.0,>=2.0.0 in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from wikipedia) (2.32.3)
    Requirement already satisfied: charset-normalizer<4,>=2 in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from requests<3.0.0,>=2.0.0->wikipedia) (3.3.2)
    Requirement already satisfied: idna<4,>=2.5 in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from requests<3.0.0,>=2.0.0->wikipedia) (3.8)
    Requirement already satisfied: urllib3<3,>=1.21.1 in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from requests<3.0.0,>=2.0.0->wikipedia) (2.2.2)
    Requirement already satisfied: certifi>=2017.4.17 in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from requests<3.0.0,>=2.0.0->wikipedia) (2024.8.30)
    Requirement already satisfied: soupsieve>1.2 in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from beautifulsoup4->wikipedia) (2.6)



```python
import wikipedia 
from IPython.display import display, Markdown  # For Jupyter Notebook

# Ask the user to type in a search term
search_term = input("Enter a term to search on Wikipedia: ")

# Search for a page related to the term
result = wikipedia.search(search_term)

# If we get a result, get the summary and display it
if result:
    summary = wikipedia.summary(result[0])  # Get the first result's summary
    print(search_term)  # Display the search term
    display(Markdown(summary))  # Display the summary in Jupyter Notebook
else:
    print("No results found.")

```

    emojis



Emo  is a music genre characterized by emotional, often confessional lyrics. It emerged as a style of hardcore punk and post-hardcore from the mid-1980s Washington, D.C. hardcore scene, where it was known as emotional hardcore or emocore. The bands Rites of Spring and Embrace, among others, pioneered the genre. In the early-to-mid 1990s, emo was adopted and reinvented by alternative rock, indie rock, punk rock, and pop-punk bands, including Sunny Day Real Estate, Jawbreaker, Cap'n Jazz, and Jimmy Eat World. By the mid-1990s, Braid, the Promise Ring, and the Get Up Kids emerged from Midwest emo, and several independent record labels began to specialize in the genre. Meanwhile, screamo, a more aggressive style of emo using screamed vocals, also emerged, pioneered by the San Diego bands Heroin and Antioch Arrow. Screamo achieved mainstream success in the 2000s with bands like Hawthorne Heights, Silverstein, Story of the Year, Thursday, the Used, and Underoath.
Often seen as a subculture, emo also signifies a specific relationship between fans and artists and certain aspects of fashion, culture, and behavior. Emo fashion includes skinny jeans, black eyeliner, tight t-shirts with band names, studded belts, and flat, straight, jet-black hair with long bangs. Since the early-to-mid 2000s, fans of emo music who dress like this are referred to as "emo kids" or "emos". The emo subculture was stereotypically associated with social alienation, sensitivity, misanthropy, introversion, and angst. Purported links to depression, self-harm, and suicide, combined with its rise in popularity in the early 2000s, inspired a backlash against emo, with some bands, including My Chemical Romance and Panic! at the Disco, rejecting the emo label because of the social stigma and controversy surrounding it.
Emo and its subgenre emo pop entered mainstream culture in the early 2000s with the success of Jimmy Eat World and Dashboard Confessional, and many artists signed contracts with major record labels. Bands such as My Chemical Romance, AFI, Fall Out Boy, and The Red Jumpsuit Apparatus continued the genre's popularity during the rest of the decade. By the early 2010s, emo's popularity had declined, with some emo bands changing their sound and others disbanding. Meanwhile, however, a mainly underground emo revival emerged, with bands such as the World Is a Beautiful Place & I Am No Longer Afraid to Die and Modern Baseball, some drawing on the sound and aesthetic of 1990s emo. During the late 2010s, a fusion genre called emo rap became mainstream; its most famous artists included Lil Peep, XXXTentacion, and Juice Wrld.



```python
pip install lxml_html_clean

```

    Collecting lxml_html_clean
      Downloading lxml_html_clean-0.2.2-py3-none-any.whl.metadata (1.8 kB)
    Requirement already satisfied: lxml in /Users/thomasb/nighthawk/thomasCSP_2025/venv/lib/python3.12/site-packages (from lxml_html_clean) (5.3.0)
    Downloading lxml_html_clean-0.2.2-py3-none-any.whl (13 kB)
    Installing collected packages: lxml_html_clean
    Successfully installed lxml_html_clean-0.2.2
    Note: you may need to restart the kernel to use updated packages.



```python
from newspaper import Article
from emoji import emojize
from IPython.display import display, Markdown

# URLs to import
urls = [
    "https://www.cnn.com/2019/12/08/entertainment/juice-wrld-jarad-higgins-obit/index.html",
    "https://www.cnn.com/2024/08/07/entertainment/metro-boomin-single-mother-grant-program/index.html"
]

for url in urls:
    article = Article(url)  # Specify the article
    article.download()     # Download the article
    article.parse()        # Parse the article
    
    # Adding emojis to the title
    article_title = emojize(":crying_face:") + article.title + emojize(":crying_face:")  # Format title with emojis
    
    # Display title and content
    display(Markdown(f"### {article_title}"))  # Displays title
    display(Markdown(article.text))  # Displays text

```


### 😢Rapper and singer Juice WRLD is dead at 21😢



CNN —

Rapper and singer Juice WRLD has died in Chicago, the Cook County Medical Examiner’s Office said Sunday.

Juice, who was born Jarad Anthony Higgins, turned 21 on December 2.

The rapper suffered a medical emergency shortly after arriving at Chicago’s Midway International Airport, according to people who were traveling with him, Chicago police spokesman Anthony Guglielmi said in an email to CNN. The rapper died shortly after at a nearby hospital, according to police.

“There were no signs of foul play and all individuals aboard the aircraft are cooperating with CPD and have given all of their information,” Guglielmi said.

Police are waiting for the medical examiner to determine cause and manner of death, he said.

An autopsy hasn’t been performed and no cause of death has been determined, Cook County Medical Examiner’s Office spokeswoman Natalia Derevyanny said.

“Juice made a profound impact on the world in such a short period of time,” the artist’s label, Interscope Records, said in a statement. “He was a gentle soul, whose creativity knew no bounds, an exceptional human being and artist who loved and cared for his fans above everything else.”

Juice made a profound impact on the world in such a short period of time. He was a gentle soul, whose creativity knew no bounds, an exceptional human being and artist who loved and cared for his fans above everything else. pic.twitter.com/DsVNGNaMZK — interscope (@Interscope) December 8, 2019

Juice was signed to Interscope Records in March 2018 after scoring hits on SoundCloud with “Lucid Dreams” and “All Girls Are the Same,” according to Billboard magazine, which profiled the artist in March.

SoundCloud says Juice was the most streamed, liked, and reposted artist on its platform in 2018 and “Lucid Dreams” notched the most plays of any song last year.

Juice WRLD was named Top New Artist at the Billboard Music Awards in May.

Billboard said his songs reached its Hot 100 chart 25 times in less than two years. Juice was included on three songs on the Hot 100 ranking as of Saturday, Billboard said, including two as lead artist.

Music world stunned by the sudden death

Several of Juice’s fellow artists reacted to the news of his death on social media, including Drake.

“I would like to see all the younger talent live longer,” he wrote on Instagram, “and I hate waking up hearing another story filled with blessings was cut short.”

Instagram post not found. Post has been removed or is no longer public.

Fellow artist Lil Yachty, who featured Juice on his song “Yacht Club,” expressed his shock on Twitter. “Wow, I can not believe this. Rip my brother juice world,” he wrote.

Wow, I can not believe this. Rip my brother juice world 😭😭😭 — CONCRETE BOY BOAT^ (@lilyachty) December 8, 2019

Singer Ellie Goulding collaborated with Juice on the song “Hate Me” earlier this year. She shared photos of them together and said he was a “sweet soul.”

“You had so much further to go, you were just getting started. You’ll be missed Juice,” she wrote.

I can’t believe it... you were such a sweet soul. I’ll always remember meeting you and your family on the video set and thinking how close you were. You had so much further to go, you were just getting started. You’ll be missed Juice 💔 — Ellie Goulding (@elliegoulding) December 8, 2019

Chart topper Lil Nas X paid tribute on Twitter, saying it’s “so sad how often this is happening” to up-and-coming artists.



### 😢After tragedy, rap producer Metro Boomin launches grant program on tour😢



CNN —

Two years ago, Metro Boomin suddenly lost his mother.

The Grammy-nominated rap producer – who has collaborated with Travis Scott, 21 Savage, Drake, The Weeknd and is currently on tour with Future – was raised by a single mother and knew he had to give back in her memory.

“Being raised by a single mother myself growing up, I know firsthand how hard things can get,” Metro Boomin told CNN in a recent interview. “My mother dedicated her entire life to being the best mother she possibly could, and I watched her do it all on her own.”

Metro Boomin – born Leland Tyler Wayne – had been dedicated to celebrating single mothers and their children prior to losing his mother, whom he commemorated as his “best friend in the universe” on his Instagram back in the summer of 2022. Five years before her passing, he launched his “Single Moms Are Superheroes” initiative. But after he experienced tragedy, the cause became even more personal.

Metro Boomin, center, Kansas City, July 30, 2024. Jimmy Smith

He launched a continuation of his program to celebrate single mothers, named after his own mom Leslie Joanne Wayne, in December 2023. Now, “Leslie Joanne Single Moms Are Superheroes” has kicked off a national grant program, in conjunction with Metro Boomin and Future’s North American “We Trust You” tour that will hit 21 cities.

The multi-city grant-giving initiative will provide $20,000 grants and show tickets to non-profit organizations supporting single mothers in each city on the tour.

“As soon as I got the routing for the tour, I knew that I had to give back and share blessings with the cities and communities who are coming out and sharing blessings with me,” the producer said.

“There are thousands and thousands of people in each one of these cities spending their hard-earned money on a ticket to come to the show. I’m more than grateful and don’t take that for granted,” he added. “In return, it means a lot to me knowing that I can support a great cause in each city and leave a positive impact there in a way other than entertainment.”

The charity program’s first three stops were at Metro Boomin and Future’s concerts in Kansas City, St. Paul and Detroit last week, where grants were given to the Kansas City non-profit Essential Families, which provides development services for single mothers and families in need; the St. Paul organization Jeremiah Program, which provides assistance to single mothers and children facing poverty; and the Detroit non-profit Alternatives for Girls, which helps young girls and women experiencing homelessness. Both non-profits brought single mothers and their children to enjoy the show.

The grant-giving program will continue through the month of August and into September at each stop on the tour, which includes Atlanta, Chicago, Los Angeles, New York, Toronto and more.

Metro Boomin, second from right, St. Paul, July 31, 2024. Jimmy Smith

“It’s an amazing feeling to meet these families and the heads of these organizations, hear their stories and notice the similarities with my own,” Metro Boomin said. “It’s reassuring to know you’re doing the right thing and that the funds are safe in the right hands.”

Metro Boomin also said that he recognizes his platform and recognizes his responsibility – and privilege to help others – as a public figure. One of the most in-demand and influential producers working with top artists in the hip-hop space, he also has a massive fanbase with a large reach on social media with roughly 20 million followers across Instagram, X and TikTok.

“Giving back is important to me and essential because I know God shines his light on me in a major way,” he says. “And that leaves me responsible to let that light shine through me and onto others.”



```python
import statistics as stats

# List of some numbers (like test scores)
data = [99, 345, 11, 44, 88, 66, 77, 112]

# Find the average (mean) of the numbers
mean = stats.mean(data)

# Find the middle value (median) of the numbers
median = stats.median(data)

# Find how spread out the numbers are (standard deviation)
stdev = stats.stdev(data)

# Show the results
print(f"Average (Mean): {mean}")
print(f"Middle value (Median): {median}")
print(f"How spread out (Standard Deviation): {stdev}")
```

    Average (Mean): 105.25
    Middle value (Median): 82.5
    How spread out (Standard Deviation): 102.00525196562886