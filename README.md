# Doctor Who Through the Ages"
An analysis of three metrics of the show for S01-S13


## What can data tell us about quality of Doctor Who (2005)?
As a long time fan of Doctor Who (2005), I hit a wall watching the show around 2020. I really wanted to like the new (Thirteenth) Doctor, but somehow the show just wasn't as magical anymore as it used to be in the old days. After I suffered through *Orphan 55*, I glanced over the `IMDb Ratings` of the show, and realized that I did not seem to be alone. The ratings had gone down significantly, and I wondered why this might be. 

So I created a spreadsheet and plotted the data of the ratings. I considered more advanced methods of analysis, but the problem with this data is that all of it is highly correlated, as we will soon see.

To illustrate these correlations, let me first introduce the 3 types of data in this dataset: `IMDb ratings`, the `UK viewerships` numbers, and the Audience Appreciation Index (`AI`). All of these are highly correlated. 

- The IMDb Ratings were exported from IMDb in April 2020 (S01-S12) and January 2023 (S13). 
- The values for UK viewership data and AI are taken from this site: https://www.doctorwhotv.co.uk/doctor-who-series-13-2021-22-uk-ratings-accumulator-95514.htm
- As also explained there, the British Audience Appreciation Index (AI) is a score out of 100 which is used as an indicator of the public’s appreciation for a show. Over 90 is considered exceptional, 85 or over is excellent, 60 or less is poor, and less than 55 is very poor. 

The analyis was written in R using RMarkdown (doctorwho.Rmd). To view the analysis, see doctorwho.html
