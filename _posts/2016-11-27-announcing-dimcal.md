---
title: "Announcing DimCal!"
published: true
date: "2016-11-27 23:28"
modified: "2016-12-08 00:08"
tags: [dimcal, SQL]
---
<h2>aka being wrong on the internet.</h2>


<p>
I'm putting <a href="https://github.com/gregn610/dimcal/tree/master/src/dimcal/sql">out</a>
<a href="https://github.com/gregn610/dimcal/blob/master/src/dimcal/sql/hol_ca_fed.sql">there</a> a
<a href="https://github.com/gregn610/dimcal/blob/master/src/dimcal/sql/hol_gb_eng_wls.sql">collection</a> of public holiday data in SQL format,
to use in a data warehouse.
</p>


<p>
Data has mostly come from wikipedia, I've completed a small number of countries and the mistakes are all mine.
It covers a handful of countries, and foucses dates Jan 1970 - Jan 2038.
I'll keep expanding the list of countries and I'm hoping for some help from the internet to get it more complete.
</p>

<p>
The main output of this project is the SQL to update a dim_calendar table, which is why I've broken it down into those columns.
I've also knocked up a little  <a href="http://dimcalendar.gregnicol.xyz/dim_calendar/index.html">django generated website</a> to view the results.
It ain't pretty but ...
</p>


<p>
p.s.
Does HTML time element work? Lets see <time>2016-11-12</time>.
</p>

</body>
</html>
