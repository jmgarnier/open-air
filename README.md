# Context 

This is my modest contribution to the ideas competition organized by the ["obsAIRve"](http://www.obsairve.eu/), EU project in order to raise public awareness for air quality issues in cities.

# Abstract

This project is called **OPEN-AIR**. Its purpose is to build a free open source web site with open data about air pollution.

Objectives:

- save millions of € by providing a hosted SaaS (Software As a Service) platform to EU regions
- crystal clear infographics about air pollution data 
- provide a good API to empower (geeky) citizens
- get some significant budget from crowdfunding to stay independant

## Long story

[I am a software engineer](http://about.me/jeanmichel_garnier), involved in the Ruby on Rails (web application technology) open source community and deeply concerned by environmental issues.

My idea is an open source and open data SaaS (Software As A Service) web platform to inform citizens about air pollution. 

It would include all the features as in http://www.atmo-franche-comte.org/ for example.

This is nothing new. Every EU region has built such a platform, with more or less success. For instance, 2 very rich regions where I have lived - [Catalunya (Spain)](http://www.gencat.net:8000/oicqa/owa/b01.consulta?estacio=00&contaminant=99&dades=1) and [Rhônes-Alpes (France)](http://www.atmo-rhonealpes.org/) - have miserably failed. Their web sites suffer from poor usability, very slow responses despite null or little traffic and a lack of crystal clear data and infographics. When I wrote or called their support, I was dissapointed by the quality of their replies and their lack of commitment.

A small team - 5 - 10 people - can develop the platform, publish its code on a open source platform such as github and provide it for a very modest fee to the EU regions as a hosted and highly responsive traditionnal Software As a Service web site and API.

# Objectives

## Objective 1: save millions of public €

The first objective is to **save money** for the 271 EU Regions who must provide such a platform to their citizens. As far as I am concerned, each region has separately reinvented the wheel - developing a custom and proprietary solution - instead of collaborating.

## Objective 2: crystal clear information about air pollution

The second objective - equally important - is to provide a high **quality** service with cool and user friendly infographics & widgets. I haven't had the time to look at all the EU regions web sites but I feel that there is a lot of margin for improvement.

## Objective 3: provide a good API to empower (geeky) citizens

Finally, it aims at creating an eco-system of active contributers who will fix bugs and  contribute some features on one hand. It is very important to provide a well designed and simple API to access all data, with as much as transparency as possible (open data).
Once again, none of the EU regions where I have lived provide such an API: they simply lack the awareness and skills.

Contributers can be IT students, professionals, NGOs, some public administrations, etc ... Imagine an EU competition with a small prize aiming at creating mobile phones Apps using the API.

It is a proven fact that the public is more and more concerned about air pollution. For example, there are several crowdsourcing projects which have been successfully funded:

- 140 000 $ were raised to build the [Air quality Egg](http://www.kickstarter.com/projects/edborden/air-quality-egg), a sensor system designed to collect readings of NO2 and CO concentrations. I'll get mine soon. Their web site - http://airqualityegg.com - is open source and using the Ruby technology.
- 100 000 $ for a [Geiger counter](http://www.kickstarter.com/projects/seanbonner/safecast-x-kickstarter-geiger-counter)

It worths also mentioning a french initiative with no funding yet: [Citoyens Capteurs](http://www.citoyenscapteurs.net/2012/12/10/planete-plus-intelligente-vivagora-owni-revue-de-presse-des-citoyenscapteurs/) 

I am thinking to launch a kickstarter campaign about this project in order to verify the public interest.

# Innovation

## Content

The web site will contain a little bit of text explaining the health hazards of air pollution.

To start with, data will be extracted from existing platform such as http://www.airqualitynow.org or local web sites. Then it's easier to imagine that EU regions will collaborate and provide data using a PUSH API.

## Design

- animation a la http://www.storyofstuff.org/
- dashboards a la  http://dashingdemo.herokuapp.com/sample
- infographics a la http://usdebt.kleptocracy.us/ or 

Designer Slick and fancy UI such as https://squareup.com/careers
https://www.simple.com/

## Communication channels

Look at what facebook and twitter have achieved with their APIs.

It's easy to imagine custom solutions which would use open-air API to alert sensible citizens with SMS, e-mails or publish to facebook profiles and twitter accounts.

# Implementation

## Budget

I estimate the 271 [EU Regions](http://epp.eurostat.ec.europa.eu/statistics_explained/index.php/Regions_of_Europe) have probably spent btw 25-50K€ for the initial cost + 5-20 K€ / year for maintenance, hence approximately 1O-15M€ + 5000K€ / year.

The "dream" team must include a very good designer for at least 1 year. Design budget: 50K€.
 
As a Ruby developer, I'd love to work on such a meaningfull project. Might add another ruby developer + 1-2 campaigners from Avaaz for PR and diffusion. 4 people paid 35K€ / year.

Yearly budget: **~200-400K€** 

To start with, translations can easily be delegated to google translate and volunteers.

## Political issues

Diesel car manufacturers will probably lobby very hard against any project which want to raise public awareness. Potential allies are NGOs and exhaust fumes filter manufacturers. 

EU public bodies seem to be more concerned by the cost of air pollution than local and national bodies. 

# Impact

As a proof of concept, I will start with a city where there is a local airquality egg active community such as London or Bristol.

The ultimate target is hundreds of millions of EU citizens living in cities polluted.

# Inspiration & credits

The [Government Digital Service project]( http://digital.cabinetoffice.gov.uk/about/ ) from the UK governement aims at providing information portals for its citizens, transforming government digital services. They work with Agile and Lean practices to manage their project. It is built with the modern technology Ruby on Rails which powers basecamp, twitter, group.on and millions of other web sites, some with very high traffic.

The whole project will cost millions of pounds to the UK governement but they are altruistic enough to share the source code with other governements: nearly everything will be open source!

And of course the Airquality egg utopia and dream which is becoming reality: http://airqualityegg.com/
