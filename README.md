# A data based approach to hire diverse refugee talent  
Author: Daniel Macdonald @talentrics http://www.talentrics.com/

Current trends in strategic talent Management suggest that businesses who seek to build a diverse workforce need to actively embrace trends in globalization, technology, and a de-centralized workforce.  As a result, the growing practice of 'People Analytics' is developing tools that apply machine learning to search for highly skilled professionals in under-utilized pockets of talent. (Dikau & Hatfield 2020)

![](images/Project_overview.png)

# How would it work?

The recommended approach is to use machine learning to match refugee talent against current job listings.  On the talent supply side, data may come from specially curated databases such as the 'Talent Beyond Boundaries' talent catalog, or via available social media feeds.  Talent demand would be referenced via the Thinknum NYSE Jobs Database, and the matching engine would use a Natural Language Processing approach such as the 'OpenSkills Project' from Dataatwork. (links below)

![](images/Method_scope.png)
https://www.unhcr.org


# data sources and initial EDA

 - The Open Skills Project http://dataatwork.org/data/
 The Open Skills Project is a public-private partnership lead by the University of Chicago focused on providing a dynamic, up-to-date, locally-relevant, and normalized taxonomy of skills and jobs that builds on and expands on the Department of Labor’s ONet Data Resources.  Link to initial investigation of the data source can be found here: https://github.com/talentrics/Project_proposal_2020/blob/master/Open_Skills_Jobs_API.ipynb
 
 - Job Data https://blog.thedataincubator.com/tag/data-sources/
 As part of the 'Data Incubator' data sources, I downloaded an example file of the Job Postings data set for all NYSE and Nasdaq stocks.
 The file is one of seven that are available, and is 25GB, so manipulating this data will require big data management skills.  I have posted my initial investigation of the source here: 
 https://github.com/talentrics/Project_proposal_2020/blob/master/datalab_jobs.ipynb
 
 - refugees with skills
 - UNHR

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
