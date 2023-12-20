# Airbnb AI scraping using ChatGPT
This code was written by Maxim Oweyssi using the help of ChatGPT.
## Description  
 - First script reads council names and adds search terms to them, then does a google search and scrapes the first link.
 - The second script takes the <body> elements of the link and feeds them to GPT4 with a specific prompt asking for a table, then joins the results.
 - Third script then does formatting so that this can be used by Solstice.

## How to install and use. 
Nothing to install yet, but good to fill this in with more detail

## Improvements TODO
 - Third part of the code should be completely changed, we should think about what data we want to scrape, which columns and then make Solstice adjust
 - Scottish councils should be added
 - Apart from reviewing all fields, "disabled facilities grants" should definitely be added as grant category as it confuses the AI, since it contains boiler repairs
 - Installation measures should be reviewed, perhaps to discuss with William or James. Solstice doesn't have EWI/IWI, just Solid wall insulation. This is not methodology that the ocuncils use so it confuses the AI. if solstice insists, then we should still press on and make EWI/IWI measure categories and merge them after scraping so that the AI does it the comprehensive way.
 - In general, anything confusing to a human will be confusing to an AI

### Key contacts at EST
Maxim Oweyssi - maxim.oweyssi@est.org.uk