# NOTES

## So why are there so many pharmacies in Paris?

What made me think of this: 

I was at the viewpoint at the top of L'Arc de Triomphe in Paris last month, at night, and I noticed all the bright green crosses everywhere. This made me think: how are there so many pharmacies? 

Aside from that, I do **miss** French pharmacies, for the following reasons: 

- Convenience / easier to find 
- Smaller, no random items, just medical and cosmetic products 
- Everything is cheaper!! 

For this project I chose my new home, NYC, as a point of comparison. My **aim** was to see if there really are more pharmacies in Paris.  

## Findings 

In Paris, there are more pharmacies. There are also geographically more concentrated. 

But why? 

1. **no chains** you can't have pharmacy chains in France! Or it's so difficult that I have yet to come across an instance where there is one. You also have to be a pharmacist to own one. That's regulated by [these](https://www.ordre.pharmacien.fr/) people.

2. Where you can sell medical products is more regulated

    e.g. the **only** place you can buy aspirin is at a pharmacy 

3. Pharmaceutical products are reimbursed under the public healthcare insurance -> more people buying things from pharmacies

4. This is not a reason, but products are cheaper in general! and that is something I do miss. 


## Data I used 

- [List of all districts in Paris with the density of pharmacies](https://118-418.pharmaciedegarde.org/pharmacie/75-Paris.html)
- [CSV file with all the pharmacies in Paris](https://www.data.gouv.fr/fr/datasets/carte-des-pharmacies-de-paris/)
- [Number of registered pharmacies in NY state, by county](https://www.op.nysed.gov/professions/pharmacist/license-statistics#stores)
- [NY population by county](https://www.newyork-demographics.com/counties_by_population)
- Various websites to compare prices of products: [CVS](https://www.cvs.com/?icid=cvsheader:cvslogo), [CityPharma](https://pharmacie-citypharma.fr/fr/), [Nuxe](https://us.nuxe.com/)

##  Analysis 

- Most of the analysis I did consisted of reading tables in python directly from the html (beautiful!) and putting it into pandas to get summary statistics and standardize the numbers (by population). 

## New skills and approaches 

- I think I grew the most in this project in learning how to generate an idea and find the data to support it. For most of the duration of the project, I had an idea of structure and  what I wanted to get  across, but no data. Lots of reading and going down internet rabbit holes about why pharmacies use  different symbols (green crosses, red crosses, snakes, etc.)

- I tried out a new mapbox functionality for the first time, and also tried some new kind of creative visualization using Canva (to create the image of the medical cabinet).

- I also used LogSeq to track the entire process of coming up with an idea and findings different references,  and  even to embed the Mapbox map to get a preview of what it would look like. This worked really well!

##  Things I wanted to do 

- I tried to get a dataset with all of the pharmacies in New York City so that I could run the same analysis at a district / zip code level rather than at the borough level. I scraped from the hidden API on the Office of the Professions site - but was unable to get through every single page. That's what the nyc_pharmacies notebook was for. As of Feb 5, the site I was trying to scrape from appears to be down. If this had worked I would have liked to map out all the individual pharmacies to get a sense of where they are. 

- I would have liked to make the density maps differently so that they would be at the same scale. The ones I currently have do not show the geographic / spatial concentration, i.e. you can't tell that not only there are more pharmacies in Paris, but there are more in a much smaller area. This would have been possible in QGIS but I did not have the time, or I would have had the time to make it that  way but not make it look nice. It's hard to match the embedded Datawrapper styling. 

- I would have liked to incorporate more **design**. Need to learn Adobe Creative Suite. 

