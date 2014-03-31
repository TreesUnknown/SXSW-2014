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
