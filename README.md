# Skys The Limit Final Report
Authors: Daniel Allen, Minnie Cao, Aaron Donohoe, Kristen Lowe

Link to Report: <a href="https://dat4500group5.github.io/Skys-The-Limit-Final-Report/" target="_blank">https://dat4500group5.github.io/Skys-The-Limit-Final-Report/</a>

## Abstract
This study investigates the role of aircraft age and usage in contributing to flight disruptions, particularly carrier delays and carrier cancellations, among domestic U.S. flights.  While weather and air traffic are external causes, mechanical issues, often linked to aging, are internal and potentially predictable. We hypothesize that aging aircraft, through accumulated wear and maintenance demands, are more prone to causing disruptions, and this relationship can be quantified through historical flight data.

To evaluate this, we used "The Sky's the Limit" dataset covering all U.S. domestic flights since 1995 and joined it with FAA aircraft registration data. We computed cumulative totals for each aircraft's number of flights (FLIGHTS), distance traveled (DISTANCE), and total airtime (AIR_TIME) to create usage-based age proxies, along with manufacture-year-based AGE. These four variables were then analyzed through correlation and regression tests to predict three key outcomes: the proportion of flights with any carrier delay, the proportion of delays over 30 minutes, and the proportion of flight cancellations.

The analysis revealed that delays over 30 minutes followed an S-shaped relationship with AGE: as planes aged, delays increased sharply, plateaued, and rose again after about 15 years. In contrast, cancellations exhibited an inverted-U pattern: they increased with age and declined beyond a certain point. Noted that this was partially influenced by fewer aircraft in older age bins, which reduced reliability in the trend's tail.

These patterns suggest that maintenance is a major contributor to flight disruptions or lack thereof. Industry literature supports this, noting increased maintenance demands beginning at year 7 and mandatory FAA Aging Aircraft Inspections beginning at year 14. Planes operating reliably at very old ages tend to be corporate, multi-engine aircraft with superior maintenance regimes and set flight routes, reinforcing the role of targeted upkeep in mitigating disruptions.
