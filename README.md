Minor League Splits will no longer exist in its original form.

Instead, I have elected to make a considerable amount of data available, for free, to the public.

This README outlines the files included in the repo.

# Players, teams, leagues, franchises

In all of the files, players, teams, leagues, and franchises are referred to by IDs.

There are individual files that link IDs to names and characteristics. For instance, "minorLeagueSplitsPlayers.csv" links playerIDs to names, as well as handedness and date of birth.

# Splits files

There are two files for each year, 2005-10: one for batters, one for pitchers. Most of the split names are self-explanatory. They are all identified in the table "minorLeagueSplitsSplits.csv"

# Play-by-play files

Each file contains full play-by-play logs of every game for a particular league-season.

These closely follow the conventions of the Retrosheet event log. To understand these conventions, [start here](https://www.retrosheet.org/eventfile.htm).

One difference between the Retrosheet event log and these files is that occasionally, these files are missing some piece of data. For instance, a play may be coded as "E?" instead of, say, "E1."

Another difference is the presence of detailed hit location data. It is not in these files for all years and leagues. When it is present, the entry for a play is extended by two fields, and the final two fields are the x and y coordinates of the hit location, as recorded by the MiLB scorer. These are somewhat unreliable and not intuitive to work with.

# Errata

There are many errors in these files. Their causes are manifold. Most error-ridden are the 2006 files, since that was the first year of the database.

Many of the errors arose from oddball plays. Some come from mistakes made by the MiLB scorers; they may have later been corrected, but these files were not updated. Some are systematic due to a mistake of mine at some point in the process.

These various mistakes mean that these files cannot and should not be treated as "official." Season totals are often incorrect. However, for the vast majority of players and research purposes, the errors are minor.

# A reminder

If you use the data, please take the time to read and understand the terms of the Creative Commons license linked below. This only applies to the contents and characteristics of the database that are not already in the public domain.

It is possible that I will expand, improve, and/or correct this dataset in the future, but it is unlikely I will respond to bug reports or requests for help in a timely manner.

# License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Dataset" property="dct:title" rel="dct:type">Tennis databases, files, and algorithms</span> by <a xmlns:cc="http://creativecommons.org/ns# " href="http://www.tennisabstract.com/" property="cc:attributionName" rel="cc:attributionURL">Jeff Sackmann / Minor League Splits</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/JeffSackmann" rel="dct:source">https://github.com/JeffSackmann</a>.

In other words: Attribution is required. Non-commercial use only. 
