---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
<style>
* {
  box-sizing: border-box;
}

.row_wvs {
  display: flex;
}

/* Create three equal columns that sits next to each other */
.column_wvs {
  flex: 50%;
  padding: 5px;
}
</style>

<h1 style="text-align:center">Play Hard</h1>
<h1 style="text-align:center">Be Present</h1>
<h1 style="text-align:center">Forgive</h1>
<h1 style="text-align:center">Remember</h1>
<br>

---

The chart below was created in Python using plotly express for static hosting. The data comes from iPhone Healthkit and Google Fit sources. I'm curious how these companies define and evaluate fitness data and ultimately the narrative of our daily lives. How accurate are they? So far it appears they are similar in terms of steps and distance.
<br>
We can understand what a step is, but what about going up/down stairs and how does it compare to walking, jogging, running or biking? And what about move minutes and heart minutes?
<div>{% include FamilyDistance.html %}</div>
<br>
A simple Swift app scrapes the Healthit info and sends it (using amplify) to an AWS S3 bucket. If the Django site is provisioned on AWS, lambda functions will insert the data into an RDS MySql db; otherwise, I'll grab from the bucket, manage the db locally and create the plotly derived html files. In general, the iPhone monitoring is always on.
<div>{% include FamilySteps.html %}</div>
<br>
My Swiss army knife, an android app "GetOut" that I've been slowly developing, will only monitor my gps and fitness when I want. I can select any Journal entry and follow the same process to make this data available on the cloud or locally.
<div class="row_wvs">
<div class="column_wvs"><img src="/assets/images/GetOut_Journal_list1_300x617.png" alt="Journal list"></div>
<div class="column_wvs"><img src="/assets/images/GetOut_Journal_rte1_300x617.png" alt="Journal route"></div>
</div>

---

*to do list*
* add resume
* add footer
* add ultimate team pages
  * 1977-1985 	Summit No Sweat
  * 1983-1985 	10 St Dealers
  * 1986 	Spot
  * 1987-1993 	NY NY
  * 1994-1995 	Cojones
  * 1996 	Randall's Island
  * 1997-1999 	WUDI / WSL All-Stars*
  * 2000-2001 	Bomb Squad / New York**
  * 2002 	Jam
  * 2003 	Family Style
  * 2004-2005 	KAVU
  * 2007-2010 	Troubled Past
  * 2017 	SF Relics 

