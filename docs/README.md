# BOTJAKTEN FAQ

## Why?
In the beginning of 2018 many Twitter users experienced a radical increase in interaction from what could be assumed to be some kind of automated accounts sharing nothing but links and images with sexual content. The number of such accounts have been never-ending, why there has been a need to do some experimental analyses to understand the rationale behind these porn bots.

## How?
In order to collect enough data points to perform a somewhat systematic analysis a form was setup to allow crowd sourcing of user names or Twitter ID for identified bots. A link to the form has been shared widely over the Swedish part of Twitter, and a large number of Twitter users have been active in adding accounts to the database. 
The database is only collecting information on porn bots. All user names connected to legitimate Twitter users have been deleted, in order to only focus on the active bots. From the data it is possible to make different analytical tests, such as mapping the bots online behaviour, trying to understand their origin and also highlight the width of the issue.

## What?
So far, only initial tests have been performed. What can be found so far is for instance:
* Most of the porn bots have a specific syntax related to links they provide. Even though many links are unique, they all point to only two (2) web sites with sexual content.
* Many of the porn bots seem to have been registered as Twitter users several years ago, with a specific cluster registered around 2011. It is still too early to make anything out of this, but a theory is that some of the porn bots are legitimate Twitter accounts that have been hacked while some are registered for the sole purpose of being part of different botnets.
* Most of the porn bots have profile pictures (and also shared images) relating to a small number of actresses in porn. Most likely the people portrayed have nothing to do with the bot activity.

<div style="text-align:center;width:80%">

<figure>
<img align="left" alt="Many accounts were created several years ago" src="https://raw.githubusercontent.com/Segerberg/botjakten/master/visualisations/no_of_accounts_by_created_year.png" width="100%" height="100%"/>
  <figcaption style="font-size:smaller;font-style:italic">Spam accounts by year they were created. Older accounts may have been taken over by spammers as they typically have valid older content.</figcaption>
</figure>


<figure style="text-align:center;width:100%">
<img alt="Many accounts were created several years ago" src="https://raw.githubusercontent.com/Segerberg/botjakten/master/visualisations/indegree.png" width="100%" height="100%"/>
  <figcaption style="font-size:smaller;font-style:italic">Analysis of the most recent 100 spam bot tweets. In-degree network based on @-tweets. Larger nodes mean more incoming @-tweets, which may be interpreted as bot targets.</figcaption>
</figure>


<figure style="text-align:center;width:100%">
<a href="https://github.com/Segerberg/botjakten/blob/master/visualisations/botjakten_sankey_37K_se_sv.png"><img alt="Spam site targets via redirects" src="https://raw.githubusercontent.com/Segerberg/botjakten/master/visualisations/botjakten_sankey_37K_se_sv.png" width="100%" height="100%"/></a>
  <figcaption style="font-size:smaller;font-style:italic">Spam bot profile links and their destinations. Via obscure link shorteners users are directed to questionnaire websites that in turn lead users to one of two sex dating websites.</figcaption>
</figure>

</div>

## Is there more?
It is yet too early to say anything about the origin and rationale behind the activities of these porn bots. It is tempting to assume that it is an orchestrated move to establish a botnet on parts of Twitter, for instance to make a coordinated move related to spam links or to influence a wider population in political events. At this point it is however to be considered just as likely that the porn bots are just that – porn bots.

## Who?
#Botjakten is a project managed by a number of individuals. Some are academic researchers, some archivists, some data journalists. If you want to reach out to us, please send a tweet to @asegerberg, @intensifier, @peterkz_swe, @WilliamForsth or @dekaminski on Twitter. Most of the communication will however be presented here.
