# DAT250 Software Experiment Assignment 3: MongoDB
The purpose of this report is to document the installation and testing of MongoDB on my personal computer. Furthermore the report will seek to record an aggragation section. More on that will follow.

## Installation 
During installation there were no actual problems. Only issue I had to report on, lies in the verification of the installation. In the tutorial we were instructed to download the sha256 hash file for version 5.0.2 of MongoDB, and so when I compared the two hash' I was met with False. (I used powershell, didn't know if we were supposed to use anything else.)

[Screenshot of the False comparison](https://i.imgur.com/8Ksthhv.png)

The fix for this was as easy as changing the 5.0.2 to a 5.0.3 in the URL for the download.

[Screenshot of the correct verification](https://i.imgur.com/q4DTIRR.png)

## Introductory CRUD operations
The first instruction was to use insertOne and insertMany.

[Screenshot evidence of insertion](https://i.imgur.com/2A3tBhf.png)

Next, we were instructed to use queries.

[Screenshot evidence of queries](https://i.imgur.com/Oy7D0mJ.png)

Thirdly, we use update.

[Screenshot evidence of update](https://i.imgur.com/crxEI48.png)

Fourth, removal

[Screenshot evidence of removal](https://i.imgur.com/Ab3Ojkt.png)

Finally, we were instructed to attempt a bulkWrite.

[Screenshot evidence of bulkWrite](https://i.imgur.com/6wNAAjv.png)

Further screenshot evidence can be found [here](https://imgur.com/a/Cbk5VHm) (*Includes the resulting screenshots from the delete operation*)

## Experiment 2: Aggregation

[MapReduce Example](https://i.imgur.com/Tx9Xkfl.png)

[Reduce and finalize functions for self-implemented mapReduce operation](https://i.imgur.com/7fSRe7V.png)

[Result of custom mapReduce](https://i.imgur.com/tfChWug.png)

My mapReduce function will allow users to access a customer's average money spent per order, which can be helpful to find which customers should be afforded certain promotional offers and deals, based on how much money they are spending each time they order. (Customers who spend less should be given larger percentage discounts, as the amount discounted will be less than if they give these promotional offers to the big spenders.)

## Pending issues
N/A
