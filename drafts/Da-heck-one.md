---
output:
  rmarkdown::html_document:
    theme: cerulean
  collapsed: no
  css: /css/style.css
subtitle: A data scientist answers for the non-Technorati
title: "| \\vspace{10cm} \\LARGE{} “What do you do, but really?” \n| \\vspace{10cm}
  \\LARGE{}\n"
---
<style type="text/css">
.main-container {
  max-width: 624px;  <!-- standard width of 8.5 in page with 1 in margin all around-->
  margin-left: auto;
  margin-right: auto;
}
</style>

<center>Brandon Dey</center> 
<center>7.29.18</center>

<!-- left indent like a bullet point-less bullet point -->
<style>
.nobullet li {
  list-style-type: none;
}
</style>
<br />
<br />
  It's rare if I'm completely certain of something, but I *know* I do an insufficient job of describing what I do for a living becuase the same members of family and friend groups ask me the same question almost every time we meet:
<br />
<div class="nobullet"> * *"So tell me what you do again. You work with computers or something? In IT?"*</div>
<div class="nobullet"> * *"Computers, yea ... I work in data science, which you're right: is IT."*</div>
Then I try to fabricate a sense of suspense, and pause. 
<br />
<br />
<br />
<br />
<br />
<br />
<br />
This has never fabricated suspense. 
<br />
<br />
<br />
<br />
<br />
<br />
<br />
Instead their eyes just get this glaze, meaning:
<div class="nobullet"> * Data science? Means nothing to me, you derpy derp^[**Derpy derp**: *n*. *An affectionate and/or humorous label for one who's missing the point/gist/ship, typically of an explanation or description of factual information. Origin: Although Mr. Dey suspected this term originated in the Dey household (because he had a coworker in college who used its nominalized and adjectival form, i.e.,  "What a derpy derp kind of day.", or "What the derp!" upon being confused by something), he later discovered [this YouTube video](https://www.youtube.com/watch?v=4PDJcw9oJt0), which is the more plausible* original *origin.*]. </div>
<div class="nobullet"> * *"But what do you do? Actually."* </div>
I know I can't be coy:
<div class="nobullet"> * *"I do *data science* of course!"*</div>
They'd probably go smug, retreat to the safe topic of chit chat, the weather. But say I decide to, just this once.
<div class="nobullet"> * *"Data science? So…what, you do science? on data?"* </div>
Hear that implied, *"But you're not saying anything!"*?

<br />

#### The disconnect is threefold:  

##### 1. "Data science" sounds super boring;

##### 2. "Data science" sounds made up;

##### 3. "Data Scientist" doesn't tell you much about what's actually done on the job like other job titles, which give away what they're about right there in the title, e.g., Bakers bake, Air Traffic Controllers control air traffic, and Software Engineers engineer software.  
<br />

#### Disclaimer: 

What follows is the start of multi-post hand-waving to justify these three points and demonstrate an application of data science, in the wild. If you don't want to wait, the gist of what I do, in an italicized nutshell, is:

> *My job is to make sense of — and use — lots and lots of data so the business makes money, operates more efficiently, and/or makes better decisions about an unknowable future.*

This might be pretty abstract -- toeing line coy -- to the uninitiated. But stick with me. The reason is that data science and its applications are easier seen and *used* than explained. Some guy you've never heard of said this well a long time ago: 

> *"In data analysis we have no difficulty in complicating problems in useful ways."* </br>
<center> John W. Tukey, "The Future of Data Analysis", 1961 </center>

Try to keep the 'useful' part of this stranger's thought in mind if the next few posts (of hand-waving demonstration) feel like drudgery.

---


### 1. "Data science" sounds really boring
<br />

Sure does. College or high school Science torpedoed your spirit for it? And data? Well, data. Therefore: *"'Data science?’ Doubly boring."* 

I don’t think it’s actually boring though. In fact our former U.S. Chief Data Scientist [D.J. Patil](https://en.wikipedia.org/wiki/DJ_Patil) and analytics academic, entrepreneur, and author [Tom Davenport](http://www.tomdavenport.com/about/)^[He also has an analytics and data science consulting company that’s definitely not biasing his opinion of analytics and data science.] wrote about Data Scientist being the ["Sexiest job of the 21st Century"](https://hbr.org/2012/10/data-scientist-the-sexiest-job-of-the-21st-century) in the Harvard Business Review in 2012. 

White lab coat, micropipette, large clinical rats? *Not* sexy. That was pretty close to my first reaction when a friend suggested I get a masters in data science, which was the first time I actually heard the words "data" and "science" joined together in verbal matrimony.

*Right-O there, captain square^pants^* went my first thought. *No way am I doing that.* 

I was trained in economics and econometrics^[Unfortunately this is a real word too. Means to use statistics to prove economic theories.] -- not the data and computer sciences -- and so was still pretty smitten by the idea of getting my masters in applied economics, or maybe statistics, but definitely not *data* science. His suggestion sounded like death by boredom of the debt-generating^[Which I’m realizing now is good cause to re-use economics’ label of the “Dismal Science” for *Data Science*. But Malthus was born before me so he can keep his doomy nickname. His books are read more than this site anyway.] variety. 

Until I thought more about how the technology developed by data science touches my thumbs every time I pull out my iPhone and autocorrect keeps a misthumbed *Haha* as *Gaga* because Apple data scientists presume -- reasonably -- that people talk about the pop star more than they text in baby babble. And yet they -- unreasonably -- don’t correct *Gaga* back to *Haha*, even though *Haha* is considerably^[A conjecture based on the number of people who laugh vs who have plausibly heard of Lady Gaga.] more popular than the Fame Monster herself.^[Read about the Fame Monster [here](https://en.wikipedia.org/wiki/The_Fame).]

Plus Google’s *Did you mean [your misspelled search]?* is pretty handy. I regularly rely on it to spell words I don’t know how to, which occurs often since Apple's autocorrect^[Farhad Manjoo of Slate has [an excellent article](http://www.slate.com/articles/technology/technology/2010/07/yes_ill_matty_you.html) titled, “Yes, I’ll Matty You”, describing how autocorrect works.
] has been dimineshing^[~~Opps~~ Oops.] my spelling chops since I first got an iPhone.

Also, the fruit from science a\` la data aids what I spend (way too) much of my time doing: watching Netflix and buying stuff from Amazon. Both companies use a variety of recommendation engines that work in different ways^[[Here's](https://www.quora.com/How-does-Amazons-collaborative-filtering-recommendation-engine-work-How-much-sales-lift-is-attributed-to-Amazons-recommendation-engine) a quick (somewhat-techy) rundown on Amazon’s collaborative filtering algorithm and a layman description of [Netflix’s recommendation engine](http://www.wired.co.uk/article/how-do-netflixs-algorithms-work-machine-learning-helps-to-predict-what-viewers-will-like). ] to help customers like us either find something:
    
* we know we like or  
* something we didn’t know we'd like but end up liking because it’s pretty similar to what we know we do and/or people who like similar things.  

Netflix, Amazon? — they’re convenient, sure, but capital-B Boring^[At least curbside. It’s more interesting when you pop the hood.] in terms of what data science can do for social good. I.e., they don’t hold a candle to the usefulness of identifying forest fires from satellite images^[[MIT Technology Review](https://www.technologyreview.com/the-download/610445/to-spot-fire-damage-from-space-point-this-ai-at-satellite-imagery/)] or the ingenuity of estimating quarterly earnings of brick and mortar retailers like Walmart using satellite imagery^[[Gigaom](https://gigaom.com/2010/08/18/parking-lots-help-predict-earnings/), a “technology research and analysis firm”], which shows how many cars are parked in their parking lots. 

For its lack of real or genuine social do-goodery in our lives, the Netflix algorithm(s) are hardly just rank-and-file.^[[This](https://medium.com/netflix-techblog/netflix-recommendations-beyond-the-5-stars-part-1-55838468f429) and [this](https://www.quora.com/How-does-the-Netflix-movie-recommendation-algorithm-work) is what I read to understand it. But if you’re an insomniac, give the [papers](https://netflixprize.com/community/topic_1537.html) on the nuts and bolts of the system a ~~read~~ look.] The company hosted a competition —  somewhat famously depending on one’s social circle —  to improve their existing recommendation system called Cinematch by a measly^[It took a team of AT&T Research engineers over 2,000 hours of work in year 1 to get an 8.43% improvement, bringing them mostly to the finish line. The remaining 1.57% wasn’t knocked out for another two years, plus collaboration with two additional teams, bringing the headcount of super smart, super persistent winners to seven: two statistics guys, two machine learning researchers, one electrical engineer, one software engineer, and a senior research scientist at Yahoo! Research Israel. [Source]((https://www.digitaltrends.com/home-theater/croudsourcing-key-to-netflix-contest-winners/)).] 10%. 

The prize? $1 million large.

The [outcome?](https://netflixprize.com/) A company that knows what we want to watch better than we do^[Although I dispute this weekly when I can’t find something to watch.
], admits we lie to ourselves when we do/wo/ca/n’t^[[Source](http://www.businessinsider.com/google-data-scientist-explains-netflix-algorithm-2017-5)], and, in 2018, is [investing](https://www.nytimes.com/2017/10/16/business/media/netflix-earnings.html) more money into cooking up more of this highly personalized, highly bingeable eye candy than the nominal GDP of 24%^[Or 45 of 191 countries with data, per the 2018 nominal GDP figures from the IMF. [Source](https://en.wikipedia.org/wiki/List_of_countries_by_GDP_(nominal)).]] of the world’s countries: $8 **billion-with-a-b** big ones. 

> *“That's kind of creepy — and creepier when you realize that Netflix is hardly the only business making bank on people's lack of self-knowledge.”*^[ [Source](http://www.businessinsider.com/google-data-scientist-explains-netflix-algorithm-2017-5).]

---

#### Exhibit Target
The retailer Target is somewhat infamous for having the statistical precision to predict with uncanny^[The title of this Forbes article says it all: [“How Target Figured Out A Teen Girl Was Pregnant Before Her Father Did”](https://www.forbes.com/sites/kashmirhill/2012/02/16/how-target-figured-out-a-teen-girl-was-pregnant-before-her-father-did/#2fa9ab4c6668)] accuracy if you’re a pregnant woman based on information like the following, which I pulled from the New York Times article^[New York Times coverage is [here](https://www.nytimes.com/2012/02/19/magazine/shopping-habits.html?pagewanted=1&_r=1&hp), the reporting of which was cut short after Target made its statistician — Andrew Pole, who has a [patent](http://patft.uspto.gov/netacgi/nph-Parser?Sect1=PTO1&Sect2=HITOFF&d=PALL&p=1&u=%2Fnetahtml%2FPTO%2Fsrchnum.htm&r=1&f=G&l=50&s1=8650085.PN.&OS=PN/8650085&RS=PN/8650085) on tech that can guess if you bought what you did in the store because you saw it online —  halt communication with the NYT’s reporter.
] detailing coverage:

> *“...sometime in the first 20 weeks, pregnant women loaded up on supplements like calcium, magnesium and zinc. Many shoppers purchase soap and cotton balls, but when someone suddenly starts buying lots of scent-free soap and extra-big bags of cotton balls, in addition to hand sanitizers and washcloths, it signals they could be getting close to their delivery date.” *

Predictive modeling is supposed to deliver insights, that’s the point. But the stakes of the conversation amp up considerably — and maybe only — when we the peonic people are the algorithm food and all these insights about ourselves — and not some commodity — are spit out. 

But that’s the thing: we the peonic people become products. Mariana Mazzucato at the MIT Technology Review^[[Source](https://www.technologyreview.com/s/611489/lets-make-private-data-into-a-public-good/)] lands this in a duck pond nicely:
  
> *“But Google doesn’t give us anything for free. It’s really the other way around—we’re handing over to Google exactly what it needs. When you use Google’s services it might feel as if you’re getting something for nothing, but you’re not even the customer—you’re the product. The bulk of Google’s profits come from selling advertising space and users’ data to firms. Facebook’s and Google’s business models are built on the commodification of personal data, transforming our friendships, interests, beliefs, and preferences into sellable propositions.” *

#### The Point(s): 
(i) Google is smart. 
(ii) So is Apple.  
(iii) Target too. 
(iv) Can’t forget about Netflix. 
(v) Sometimes smarter than us, the datafied peons. 
(vi) **Therefore: *Data Science* definitely *sounds* boring but actually isn’t.**^[s (urv) i ii iii iv v vi(ng)]  

In the next post, I’ll work out the second reason why eyes go aglaze when I mention I do *data science*: because Data Science sounds completely made up. There, I'll do some kerplunking beyond the small walls of Community Dork to see how data science is impacting even obscure corners of our economy.

