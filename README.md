# Who's News

## Final report

The final report for the Who's News prototype can be found on the [about page](https://deco3500.github.io/newsbias/about.html) of our prototype.  Our Github Page has been behaving inconsistently so the prototype and about page content are best viewed by downloading this Github repository and opening the files locally.

### Promotional video

Our [video can be viewed on You Tube](https://youtu.be/fGVuigW2Tww) or on our [about page](https://deco3500.github.io/newsbias/about.html).


<a href="http://www.youtube.com/watch?feature=player_embedded&v=fGVuigW2Tww
" target="_blank"><img src="http://img.youtube.com/vi/fGVuigW2Tww/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

## How to use the prototype

### Search

Search for an Australian newspaper (online or in print) using the search box on the [home page](https://deco3500.github.io/newsbias/index.html).  You can search for a name (e.g. Brisbane Times) or copy and paste a url of an article.

### Fact Check
Who's News Fact Check allows you to submit an article to be checked and assessed by our team of community leaders. Articles will be given a rating based on four weighted criteria which are independantly assessed by three members of the fact-checking team. 


### Chrome Extension

<ol>
<li>Download this Github repository and unzip it.</li>
<li>In Chrome, go the the Google Chrome Settings.</li>
<li>On the side menu, click the extension tab.</li>
<li>Tick the 'Developer mode' box.</li>
<li>Click the 'Load unpacked extension' button and choose the folder 'newsbias'.</li>
</ol>

![Chrome Settings](https://raw.githubusercontent.com/deco3500/newsbias/master/IMG/Screen%20Shot%202016-10-30%20at%209.55.25%20am.png "Chrome Settings")

You can now use the extension when viewing a news article on the web (like this one: https://theconversation.com/is-it-back-to-the-future-for-human-origins-science-or-just-a-case-of-science-media-misleading-us-again-63043), and click on the extension button.

![Using the extension](https://raw.githubusercontent.com/deco3500/newsbias/master/IMG/Screen%20Shot%202016-10-30%20at%2010.10.50%20am.png "Using the extension")







# Team News Bias Project Proposal

## 1. Introduction

In March 2016, the Government tabled changes to media ownership rules set out in the Broadcasting Services Act 1992 (Cth). The changes proposed to repeal the “2/3 cross media ownership” and “75% reach” rules respectively, citing a need for “traditional” platforms (Commercial Television/Radio, most Newspapers), to have greater flexibility to respond to increased pressure from “new” forms of media (i.e. online) (Foreman & Jordan, 2016).

Although these changes do not specifically apply to online publications, they reinforce the ever-evolving landscape of media ownership in Australia. Data published by the Australian Communications and Media Authority (ACMA) show that 9 individuals hold the majority of media outlets in Australia (ACMA, 2016). The selection of senior editorial staff is often closely managed (McKnight, 2012), and accusations of bias are not uncommon given the numerous private interests the owners hold (Hobbs, 2016), (AIM Editorial, 2014).

While the data provided by the ACMA is useful, it lacks granularity and is only available from a “top-down” perspective. There is no functionality for a user who wants to interrogate a specific publication or website (i.e. search from the “bottom-up”). The fragmented nature of digital publications serves to broaden the gap between the data on media ownership and the articles themselves. 

Our app will connect the available information directly with the article being read; a consumer can draw their own informed conclusion as to the presence of bias. Presenting the information at the point of delivery will bridge the disconnect between an article and the ownership / editorial structure underpinning it's authorship.

## 2. Concept

News Bias is a web app that will highlight ownership, key stakeholders, reach, and a crowdsourced trust rating for news web sites that users search for. The app pairs with a Chrome extension that detects and notifies a user when they browse a site within the app's database.  

There are two main components to the web app: **Search/Ownership Profile** and **Fact Check**.

### 2.1 Search / Ownership Profile
Users simply enter a URL (base URL or a direct link to an article) and are presented with a profile of ownership, key stakeholders and reach for that news site.

A crowdsourced trust rating is also shown and users have the option to contribute to the trust rating. The rating is clearly presented as a __reflection of public opinion__. 

If a site has no data, users can submit for it to be added to our database. All results can be shared via social media such as Facebook, Twitter, etc.

### 2.2 Fact Check
User can submit a quote and a link to an article to be fact checked by a team of community leaders i.e. "Fact Checkers". Users can apply to become fact-checkers via a form on the website.

Articles will be given a "rating", computed by a series of weighted parameters which 3 members of the fact-checking team must answer independently.  Results of a fact check can be easily shared by a user to social media chanels and email.

**Possible guidelines/parameters for fact check**
* Is the content factually correct? (All aspects / most aspects / few aspects / no aspects)
* Have aspects been presented in an even and balanced manner? (Both sides evenly considered / Some degree of bias / Large degree of bias)
* Is the headline reflective of the article’s content (i.e. is it clickbait?)
* How sensational is the tone? (Heavily sensationalised and exaggerated / Somewhat sensationalised and exaggerated / Generally not sensationalised)

Results from the 3 are averaged and computed into a rating (e.g. A - F) which is then displayed publically. Once enough data is collected, the rating will be displayed as an additional component of the ownership profile in 2.1, reflective of the outlet's overall trustworthiness.

The site's community (including the submitter) can offer their own commentary in this section. As with the ownership profile, results for individual articles can be shared on social media. 

### 2.3 Stretch goals
* A further breakdown of the trust rating by non-identifiable demographics, e.g. 34% conservatives vs 65% liberals find a source trustworthy.
* Chrome extension for users to check sites as they encounter them without having to navigate to a seperate site
* Ability for text-based searching terms other than a URL - such as a journalist, organisation, owner, etc.

### 2.4 Audience
Our solution is aimed at heavy consumers of news, particularly those who take more than a passing interest in the origin of content they consume. 
Those who are interested in who owns their news and how that might affect the bias of the news they read regularly will be the "primary" audience for the app. These users will visit the site, or install the extension directly.
The ability to share results via social media will serve to engage those who lack the motivation/interest to seek the information directly. This casual audience can be considered the "secondary" audience for the app, and will visit the site via links shared on social media. 

### 2.5 Points of Differentiation
The interactive map on the ACMA website is the closest thing we found to an app with loosely-similar functionality to our concept. Our approach is different in many ways, most notably that it directly connects a piece of content with an ownership profile. A user is unable to directly profile an article or website using the ACMA map; making the link would require additional prior knowledge of which publications are connected to which outlets.

## 3. Team

### 3.1 Individual Roles & Responsibilities

**All team members will contribute to all aspects of the assessment.**  Team roles are to facilitate the different aspects of our project and follow up with other team members on their areas of responsibility. 


Name | Details | Roles | Responsibilities
--- | --- | --- | --- 
Lilly Borchardt | <ul><li>Lilly.borchardt@gmail.com</li><li>40652218</li><li>Github: lollyborch</li><li>DECO7350</li></ul> | Team Co-ordinator | <ul><li>Keep team on track for meeting project goals</li><li>Front and back end support</li><ul>
Chris Pala | <ul><li>highwaytoacdc@gmail.com</li><li>42976561</li><li>Github: chrispala</li><li>DECO7350</li></ul> | Content and Communication | <ul><li>Writing web content for product</li><li>Coordination of team documentation (e.g. project proposal)</li><ul>
Xu Liu (Leo) | <ul><li>liuxu1992422@gmail.com</li><li>43677191</li><li>Github: leoliuxu</li><li>DECO3500</li></ul> | Design | <ul><li>Wireframing, interface design</li><li>Front end support</li><ul>
Foo Cheok Kok (Kirill) | <ul><li>kfc1346@gmail.com </li><li>43845570</li><li>Github: kirillmomo</li><li>DECO3500</li></ul> | Development | <ul><li>Front and back end</li>

Logistics including equipment, meetings, transport will be shared by all team members.  Each team member is responsible for thier own transport to workshops and meetings, and development environment. 
All of the logistic responsibilities will be equally shared to all of the team member.

### 3.2 Decision Making

Decisions will be made collaboratively.  If no consensus is reached, decisions will be voted on.  In the event of an even split, the person responsible for each section will have final say.

### 3.3 Conflict resolution

In the event of group conflict, we will:
* Admit there is a conflict that needs to be resolved
* Approach team members involved to understand problem from all perspectives
* Mediate an agreeable resolution after understanding the problem and move on if conflict is solved.
* If problem is still present, we will inform tutors to seek advice.

#### 3.3.1 Underperformance
The whole group will discuss and evaluate the underperforming person’s role, and responsibilities to possibly be reallocated. In the circumstance that members still do not participate equally after multiple discussions the course coordinator will be informed.  All team members acknowledge that this may result in individual grade being reduced.


## 4. Communications 

Our GitHub repository for storing and collaborating on code https://github.com/deco3500/newsbias

### 4.1 Meeting times and communication
We will be meeting during the workshop session (Wednesday 4pm).  In addition to the course requirement to attend, it is a group expectation that all group members will attend these every week.  Additional meetings will be scheduled as needed.

#### 4.1.1 Facebook 
A private group community has been set-up on Facebook for group communication.  This was chosen as all group members are regularly active on Facebook which allows for quick responses.  As not to rely on Facebook's 'Seen by ...' function, group members have agreed to 'Like' posts to indicate they have read and understood it.  

#### 4.1.2 Google Drive
A shared Google Drive folder has been set-up to work collaboratively on documents.  All group members already have active Google Accounts.  Using Google Drive allows multiple group members to work on documents (e.g. proposal, task list) simultaneously.

### 4.2 File naming conventions

Files will be named using descriptive terms in camel case, e.g. trustRatingController.js.  This makes files easy to asses at first glance and easy to read.


## 5. Plan

### 5.1 Project Phases

#### 5.1.1 Research and Requirements
* research problem space including academic and non-academic sources
* review similar approaches (including [Crickey bias-o-meter](https://www.crikey.com.au/2007/06/26/crikey-bias-o-meter-the-newspapers/), [The Conversation author information](https://theconversation.com/students-are-not-hard-wired-to-learn-in-different-ways-we-need-to-stop-using-unproven-harmful-methods-63715), [ABC Fact Check](http://www.abc.net.au/news/factcheck/))
* source news ownership information available to use in the prototype
* confirm technical requirements and development environment

#### 5.1.2 Design
* produce wireframes and user interface designs
* test designs with users

#### 5.1.3 Construction
* build the prototype
* front end and back end development

#### 5.1.4 Prototypes
* final decisions about high/low fidelity of different aspects of prototype

##### 5.1.4.1 High Fidelity: Search
The 'Search' feature will be a high fidelity prototype that users can search news sites/articles and see results.  A database of news sites will be developed,initially with a small amount of data with a view to make this as robust as possible for final prototype. The crowd-sourced trust rating will also be functional.  We plan to use AngularJS to complete this aspect.  There will also be a form to submit sites not yet listed

##### 5.1.4.2 Low Fidelity: Fact Check
Users will be able to see how to submit article, how to become a volunteer and view sample results page. No actual volunteer fact checkers will be developed for this prototype.  

##### 5.1.4.3 Approach
We plan to use a mobile-first approach in designing and developing this web app using responsive technologies like the [W3 CSS grid layout](http://www.w3schools.com/w3css/).  Code will be managed using GitHub and tasks/workflow will be managed using the Zenhub approach. A web app was chosen so the product is device neutral.



### 5.2 Deliverable breakdown

Week | Due | Key Deliverable
--- | --- | ---
*Week 7* | Mon 5 Sept, Blackboard 11.59pm | Project Proposal Report (this document)
*Week 8* | Wed 14 Sept, Workshop 4-6pm | Project Prototype Interim Stand-up <ul><li>presentation of research phase<ul><li>technical framework details</li><li>data gathered/available</li></ul></li><li>design update<ul><li>wireframes</li><li>UI designs</li></ul></li></ul>
*Week 9* |--- | <ul><li>continue working on design phase</li><li>start front end development </li></ul>
*Week 10* | Wed 5 Oct, Workshop 4-6pm | Project Prototype Interim Stand-up <ul><li>presentation of prototype to be tested with users</li><li>detail of use case scenario</li></ul>
*Week 11* | --- | <ul><li>usability testing with users</li><li>iteration of feedback into app</li><li>continuation of front end development</li></ul>
*Week 12* | Wed 19 Oct, Workshop 4-6pm | Project Prototype Interim Stand-up <ul><li>presentation of prototype</li><li>technical update on front/back end development</li><li>continue development this week</li></ul>
*Week 13* | Wed 26 Oct, Workshop 4-6pm | Final Project Prototype Presentation

### 5.3 Resources

* Team member time & skills
* Web hosting for app
* Development environment
 

## 6. Tags

### 6.1 Social and Mobile
* #crowdsource
* #socialmedia
* #webapp

### 6.2 Journalism and News

* #bias
* #factcheck

## 7. Bibliography


* ACMA. (2016). 'Media Interests' snapshot | ACMA. *Acma.gov.au*. Retrieved 4 September 2016, from *http://acma.gov.au/theACMA/media-interests-snapshot*

* AIM Editorial. (2014). Democracy and diversity: media ownership in Australia. The AIM Network. Retrieved from *http://theaimn.com/democracy-diversity-media-ownership-australia/*

* Foreman, A. & Jordan, K. (2016). Government announces media ownership law changes. *Claytonutz.com*. Retrieved from *https://www.claytonutz.com/knowledge/2016/march/government-announces-media-ownership-law-changes*

* Hobbs, M. (2016). Kick this mob out: The Murdoch media and the Australian Labor Government (2007 to 2013). Global Media Journal Australian Edition, 10(1). Retrieved from *http://www.hca.westernsydney.edu.au/gmjau/?p=1075*

* McKnight, D. (2012). Gina Rinehart and Rupert Murdoch: a study of power in the media. Theconversation.com. Retrieved 5 September 2016, from *http://theconversation.com/gina-rinehart-and-rupert-murdoch-a-study-of-power-in-the-media-5394*

https://fullfact.org/blog/2016/oct/how-find-fact/

