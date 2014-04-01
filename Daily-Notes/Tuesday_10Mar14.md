[**Real World Data: Lessons from Texas Prisons**](http://schedule.sxsw.com/2014/events/event_IAP26142)

\#rwdata

**Travis Swicegood**  
Formerly of The Texas Tribune  
@tswicegood

[Slides](http://tswicegood.github.io/real-world-data)

[Texas Prison Inmates](http://www.texastribune.org/library/data/texas-prisons/) Data Application

- Prison data updated once a month
- [Errors in Data](http://www.texastribune.org/2013/07/30/prisoner-database-back-online/) from TDCJ
- About 3% of codes are inaccurate

Real World Data is not "Big Data":

- Dataset
- Not unbounded
- Almost always "dirty"

[Texas Tribune Bill Tracker](http://www.texastribune.org/session/83R/bills/):

- Texas Legislature Online data is scraped
- "No concept of semantic markup"
- Legislator's ID exposed on [reports page](http://www.legis.state.tx.us/reports/report.aspx?ID=author&LegSess=83R&Code=A2100), but not bill page
- Between 81R and 82R, TLO changed from [Patrick, Dan](http://www.legis.state.tx.us/reports/report.aspx?LegSess=81R&ID=author&Code=A1430) to [Patrick](http://www.legis.state.tx.us/reports/report.aspx?LegSess=82R&ID=author&Code=A1430)
- TLO doesn't have a "dashboard" for the data

Script everything: Reproducible, Reliable

Keep copies of requested data (in various stages of cleaning)

S3 is [cheap](http://aws.amazon.com/s3/pricing/effective-april-2014/)

Be flexible: "A float changes to a string, then changes back"

The [documentation](http://csvkit.readthedocs.org/) for running CSVKit has a great explanation of the command line.

Tools: Git, CSVkit, Tabula, Python, NumPy, pandas, R, jQuery -> pyQuery, OpenRefine

Great data stores: Postgres/PostGIS

---------

[**Representative Democracy in a Social Media Era**](http://schedule.sxsw.com/2014/events/event_IAP24468)

\#socialgov

**Matthew Desjardins**  
SM Mgr; Press Officer - Exec Office of the Mayor  
Government of the District of Columbia  
@dayshardan

**Zach Boisi**  
Client Svcs Dir - newBrandAnalytics  
@zachb22

[Slides](https://db.tt/xBYkkg82)

[Grade.DC.gov](http://grade.dc.gov)  
Public/Private partnership between D.C. & newBrandAnalytics

Rolled out with several agencies per phase.

Data collected from: Google+, Wordpress, Yahoo!, Facebook, Twitter, Web Forms, Paper Cards

Interesting case: *D.C. Office of Aging* was one of the surprise successes

Website connects to newBrandAnalytics technology:  
Natural Language Processing, Algorithms, Credibility & Theme Extraction, etc.

Grades are communicated to frontline employees.

More detailed data is kept internal.

Q: What does an "A" mean?  
A: The processing to determine the grade is proprietary.  However, they are trying to better describe what the grades mean.

---------

[**The Future Farm Is Now: Can Robots Feed the World?**](http://schedule.sxsw.com/2014/events/event_IAP20078)

\#futurefarm

**Dev Shrestha**  
Assoc Professor - University of Idaho

**Jeff Caldwell**  
Multimedia/News Editor  - Successful Farming & Agriculture.com  
@jeffacaldwell

**Maribeth Gandy**  
Dir - Interactive Media Technology Center at Georgia Institute of Technology  
@maribethgandy

**Nathan Wright**  
Digital Mktg & Innovation - Hy-Vee  
@nathantwright

Farmers are hacking GoPros to collect IR data from their fields

Robert Blair, Blair Farm - Kendrick Idaho  
[The Unmanned Farmer](http://theunmannedfarmer.blogspot.com)

Wearable computing and sensing.

[CopyCat](http://www.cats.gatech.edu/research) - "CopyCat is designed both as a platform to collect gesture data for our ASL recognition system and as a practical application which helps deaf children develop working memory and language skills while they play the game."