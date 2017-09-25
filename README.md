# participate.net

Participate.Net : An experiment in constituent driven policy

Premise:

In order to increase participation of constituents in the process of creating and promoting legislation, a platform is proposed. This platform will enable constituents to vote on pending legislation, create petitions to lobby their representatives, and promote their own legislative suggestions. Each constituent will have their own personal dashboard tracking suggested, introduced, and pending legislation. Constituent suggested legislation, once published, becomes available to all other district constituents for comment, voting, and general review. Additionally, there will be a social media aspect to promote constituent to constituent collaboration. Each constituent and official will have an inbox for pending notifications. These may be notices of new suggested legislation, petitions, and polls. A method of direct contact with the constituents’ elected officials will be provided. Virtual town halls will be possible via chat (first rev.) with the elected official. Officials will have their own dashboard tracking constituent opinion regarding new, introduced, pending, or suggested legislation. Additionally, the official will have an opportunity to comment on votes they cast on any given piece of pending legislation or opinion regarding suggested legislation.

Data on new, introduced, and pending legislation will be captured from publicly available data sources. This data will include bill details, current committee progress, and a list of co-sponsors. Data regarding officials will be gathered in the same way. Data on officials will include website, contact information, voting record, reason for casting any given vote, and financial contributors.

As data accumulates over time a rating of the elected official regarding votes cast correlating to the votes cast by constituents on a given piece of legislation will be gathered. This has tremendous value to both constituent and elected official. Constituents have the power to not only suggest new laws, but weigh in on any given bill. The elected official will then have a detailed understanding of the will of his constituents on any given bill. Also, if the votes cast by the official are in parity with the will of their constituents it becomes far more difficult for challengers to unseat the elected official. So long as the elected official is in this close relationship with their constituents punitive spending by political opponents is rendered ineffective. So, if the constituents wish to re-elect their elected official, no amount of money spent against them will succeed.


Technical Details:


By utilizing existing, and free, data gathering site APIs detailed data can be acquired and cached locally to the server for speedy retrieval. By using open-standard protocols we are able to tap into a wide variety of data sources. I have selected OS.js (node.js based) web framework as the first candidate for the server software. A new and custom application can be written to add features over time as they are needed. It has the ability to integrate with Dropbox, Google Drive, Microsoft OneDrive, and any WebDav server as needed. This server platform can access SQLite, MySQL, and Postgres databases. OS.js can be found here: https://www.os-js.org/ 
