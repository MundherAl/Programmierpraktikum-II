 This section contains a summary and takeaways for the scenario described in [Woche 1 – Programmierpraktikum 2 (propra.de)](http://propra.de/ws2223/cfc6e2ea4fc7eb4/#_beispiel_wasserfall_vs_agile)

---
## Waterfall Timeline:
<dl>
<dt>Week 1</dt>
<dd> - Gathering of 80 specifications for project.</dd>
<dd> - Decision to use Onion-Architecture because they are most familiar with it and it appears to be useful for the project.</dd>
<dd> - Decision to use MySQL and Docker.</dd>
<dd> - Planning and preparations take one day and implementation begins.</dd>

<dt>Week 2 - Week 3</dt>
<dd> - Data Modeling begins. Finishes in 1.5 weeks. <dd>
<dd> - Implementation of repositories and Java classes begins as well as testing Finishes in 2 days.<dd>
<dd> - Developers notice, that they have too many aggregates but continue development. <dd>

<dt> Week 4 - Week 11 <dt>
<dd> - A concept is developed to decide which components should be used and what their responsibilities and intersections with other components are. Finishes in 1 week. <dd>
<dd> - Six components are planned. Each component finishes in one week.<dd>

<dt> Week 12 - Week 15 <dt>
<dd> - Front-end development begins. Small modifications are made. <dd>
<dd> - Implementation and testing is concluded after 2.5 weeks.<dd>
<dd> - Deployment scripting begins. Finishes in 2 days. <dd>
</dl>
- The project is now presented to the client and following requirements are made:
	1. Admin wants a Postgres DB instead of a MySQL DB. This costs 2 days of time.
	2. Front-end feature for data entry is not optimal. Request is made to allow excel files for data entry. This costs 1 day.
	3. Creating repositories is unstable (GitHubs fault). Request is made for a shell script that receives data as a .CSV file. This costs 1 day.
	4. Project has taken too long and the client decides to use a suboptimal alternative.
---
## Agile Timeline:
<dl>
<dt>Week 1 - Week 2</dt>
<dd> - Discussion to assign tasks and prioritization. <dd>
<dd> - The registration feature earns highest priority. <dd>
<dd> - Developers implement code, push it, build it and test it in the production server. <dd>
<dd> - Developers write scripts for MySQL as a DB, system admin protests and developers switch to Postgres.<dd>
<dd> - All of the above costs 3 days. <dd>
<dd> - Developers work on the registration feature. Costs 1.5 weeks. <dd>
<dd> - Developers now have a demo! <dd>

<dt>Week 3 </dt>
<dd> - System admin requests an additional feature to registration <dd>
<dd> - Developers add requested feature and finish a basic UI. Costs 1 week. </dd>

<dt>Week 4 - week 6</dt>
<dd> - Developers work on "apply" feature. Costs 1.5 weeks</dd>
<dd> - System admin requests a neat UI design. Costs 1 week.</dd>

<dt>Week 7 - Week 8</dt>
<dd> - Next planned feature is developed. Costs 1 week.</dd>
<dd> - Repositories are implemented. Developers detect a problem with GitHub Java API and fix the issue. Costs 3-4 days</dd>
</dl> 

### Take-away:
- Feedback is important! Agile development saves a lot of time.