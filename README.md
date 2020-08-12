# A data based approach to hire diverse refugee talent  
Author: Daniel Macdonald @talentrics http://www.talentrics.com/

A recent Deloitte whitepaper presents research into how companies are 'Creating Value and Impact Through the Alternative Workforce', pointing to market shifts such as rapidly developing technology, market globalization and the need for agile workforce strategies as a unique opportunity for businesses to leverage global market changes (Dikau & Hatfield 2020).  In parallel, the growing field of 'People Analytics' suggests that corporations can apply data science to their talent strategy, using data science to improve on people processes.

This proposal looks at how organizations can drive 'Diversity and Inclusion' programs by using a data driven approach to match refugee talent with current opportunities for employement.  Such an approach has the potential to address business needs to hire highly skilled, dedicated professionals while also having a range of social benefits that support UN development initiatives. (Cousins & Laurie 2019)

![](images/Project_overview.png)

# How would it work?

The recommended approach is to use machine learning and skills ontologies to match refugee talent to job listings.

The data sources - on the talent supply side, data may come from specially curated databases such as the 'Talent Beyond Boundaries' talent catalog, or via available social media feeds.  Talent demand would be referenced via the Thinknum NYSE Jobs Database, and the matching engine would use a NLP approach such as the 'OpenSkills Project' from Data at work. (links to sources in citations below)

![](images/Method_scope.png)
Statistics on refugee populations from https://www.unhcr.org


# Initial Data Exploration:

Initial data exploration is presented in the 'Notebooks' folder of this repository: 
https://github.com/talentrics/Project_proposal_2020/tree/master/Notebooks

For the proposal, I used the Thinknum data via [The Data Incubator program](https://blog.thedataincubator.com/tag/data-sources/) to find open job roles.  The data is uploaded to Python via csv (25GB) and then loaded to a SQL lite database due to the size.  An initial query resulted in 128 job roles with 'Cardiovascular Tech' in the job title.  The process is outlined in [this Python Notebook](https://github.com/talentrics/Project_proposal_2020/blob/master/Notebooks/datalab_jobs.ipynb).  

I then look at the API for [The OpenSkills Project](http://dataatwork.org/data/) to determine relevant skills for each specific job role. Below is the example keyword search that resulted in the top 10 skills recommended for for 'Cardiovascular Technician'.  The process is outlined in [this Python Notebook](https://github.com/talentrics/Project_proposal_2020/blob/master/Notebooks/Open_Skills_Jobs_API.ipynb)

![](images/proposed_approach.png)


# Citations: 

Dikau, D., & Hatfield, S. Deloitte Publishing (2020); "Creating Value and Impact through the Alternative Workforce"
https://www2.deloitte.com/us/en/pages/human-capital/articles/alternative-workforce.html

Cousins,S., Lawrie, R. & Nyce, S. Talent Without Boundaries (2019); "The Promise of Labour Mobility"
https://static1.squarespace.com/static/5dc0262432cd095744bf1bf2/t/5ed20b4cdef8546a019d216b/1590823775767/TBBGRFReport2019.pdf

UNHCR, “Figures at a Glance”, https://www.unhcr.org/en-au/figures-at-a-glance.html

Talent Beyond Boundaries Talent Catalog
https://www.talentbeyondboundaries.org/the-talent-catalog

OpenSkills Project
http://dataatwork.org/data/
