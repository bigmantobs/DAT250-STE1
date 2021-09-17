# DAT250 Database Experimentation
## Introduction
The purpose of this report is to document the learning and implementation of Java Persistence API. The first difficulty I had with this experiment was one I brought upon myself, I had started the experiment too late (I have been somewhat ill this weekend, and this has limited my workrate), but then I encountered a number of technical difficulties which made the experiment more challenging than need be. Unfortunately, at this point in time I am still unable to generate any database reports with my model, meeting a number of errors in my IDE terminal. I shall go to a lab session this week and see if I may be guided to a functional experiment.
## Code for experiment one and two
[Experiment 1](https://github.com/bigmantobs/de.vogella.jpa.eclipselink)
[Experiment 2](https://github.com/bigmantobs/jpa-basic-cc)

## Screenshots
![First derby runs](https://i.imgur.com/sG97d22.png)
![Test results](https://user-images.githubusercontent.com/60216048/133073530-0067a647-8dce-42dd-82da-da9da8763598.png)
![No persistence provider](https://i.imgur.com/saigku3.png)
![Struggles](https://i.imgur.com/7m1ifdv.png)

## Struggles
This was a really challenging task for me. I must have made about 8 different intelliJ project directories before I finally got it right. I had a number of different errors, which meant very little to me, so troubleshooting these errors was a nightmare. Troubleshooting online also led me astray, as I was using code from stackoverflow which was incompatible with our maven configuration. I also spent hours troubleshooting an error which was as simple as a typo in the class declaration in persistence.xml. The error description for this was something along the lines of: entity creditcard targets a non-entity pincode for a relationship.

## Inspection of Data Tables
Inspection of generated database tables was carried out via derby's ij tool. The following screenshot is of the database tables.
![Database Results](https://i.imgur.com/XJGHOBR.png)

## Unsolved Issues
- None.
