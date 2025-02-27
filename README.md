<p align="center">
  <h1 align="center">Welcome to <strong>diverr</strong>!</h1>

  <p align="left">
    Goodbye paper dive logs, hello <strong>diverr</strong>!
    <br /><br />
    Paper dive logs are difficult to keep track of. Which dives have all my shark photos? Where are all my Australia dives? What equipment did I wear when the water was 48º?
    <br /><br />
    That's where diverr comes in, a multi-functional storage and library application with a social component. At the core, it provides an intuitive form to submit logs into an electronic, searchable, & filterable dive log book that is an extension of traditional paper records.
    <br /><br />
    Upload your photos to your dive log and instantly share them with a worldwide community of divers who understand the thrill of swimming with manta rays, setting a new personal depth record, and passing the 24-hours-underwater mark.
    <br /><br />
  Built by a six-person dev team with <em>Next.js</em>, <em>React</em>, <em>Material-UI</em>, <em>NextAuth</em>, <em>Formik</em>, and <em>Postgres</em>, diverr boasts a simple and intuitive UI while providing a highly performant back end constructed with complex queries that abstract away the front end workload.
    <br /><br />
  
 ![](https://media.giphy.com/media/8oqWA5KasbsIqWLCwU/giphy.gif )
  
    <h3 align="center">
      <strong>Contributors »</strong>
      <br />
      <hr />
      <a href="https://github.com/cmcrow2" target="_blank">Cameron Crow</a>
      •
      <a href="https://github.com/acdavitt" target="_blank">Amanda Davitt</a>
      •
      <a href="https://github.com/itsme-sunil" target="_blank">Sunil Gadgil</a>
      •
      <a href="https://github.com/jeff-try-code" target="_blank">Jeff Jiang</a>
      •
      <a href="https://github.com/eserpin" target="_blank">Eren Serpin</a>
      •
      <a href="https://github.com/kennyctran" target="_blank">Kenny Tran</a>
      <hr />
    </h3>
  </p>
</p>
<br />
<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#stack">Built With</a></li>
    <li><a href="#welcome-page">Welcome Page</a></li>
    <li><a href="#feed">Feed</a></li>
    <li><a href="#view-logs-dashboard">Dashboard</a></li>
    <li><a href="#add-a-dive-log">Add a Dive Log</a></li>
    <li><a href="#back-end">Back End</a></li>
    <li>
     <a href="#workflow">Workflow</a>
     <ul>
      <li><a href="#trello">Trello</a></li>
      <li><a href="#version-control">Version Control</a></li>
     </ul>
    </li>
    <li>
     <a href="#development-and-deployment">Development and Deployment</a>
     <ul>
      <li><a href="#repo">Repo</a></li>
      <li><a href="#install">Install</a></li>
      <li><a href="#start-scripts">Start Scripts</a></li>
      <li><a href="#google-oauth-token">Google OAuth Token</a></li>
      <li><a href="#cicd">CI/CD</a></li>
     </ul>
    </li>
    <li><a href="#challenges-and-learning">Challenges and Learning</a></li>
  </ol>
</details>

<hr />
<br />

# Stack

<table>
  <tbody>
    <tr>
      <td>Front End Languages</td>
      <td>
        <img alt="JavaScript" src="https://img.shields.io/badge/javascript%20-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" />
        <img alt="HTML" src="https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white" />
        <img alt="CSS" src="https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white" />
      </td>
    </tr>
    <tr>
      <td>Frameworks & Libraries</td>
      <td>
        <img alt="Next.js" src="https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=next-dot-js&logoColor=white"/>
        <img alt="React" src="https://img.shields.io/badge/react%20-%2320232a.svg?&style=for-the-badge&logo=react&logoColor=%2361DAFB" />
        <img alt="Material-UI" src="https://img.shields.io/badge/-Material--UI-%230081CB?&style=for-the-badge&logo=material-ui&logoColor=white" />
      </td>
    </tr>
      <td>Database & Back End</td>
      <td>
        <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
        <img alt="MySQL" src="https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white"/>
        <img alt="NodeJS" src="https://img.shields.io/badge/node.js-%2343853D.svg?style=for-the-badge&logo=node-dot-js&logoColor=white"/>
      </td>
    </tr>
      <td>Design</td>
      <td>
        <img alt="Figma" src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
      </td>
    </tr>
    <tr>
      <td>Utilities</td>
      <td>
        <img alt="Webpack" src="https://img.shields.io/badge/webpack%20-%2320232a.svg?&style=for-the-badge&logo=webpack&logoColor=%2361DAFB" />
        <img alt="Babel" src="https://img.shields.io/badge/Babel-F9DC3e?style=for-the-badge&logo=babel&logoColor=black" />
        <img alt="Postman" src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=red" />
        <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
        <img alt="yarn" src="https://img.shields.io/badge/Yarn-2C8EBB?style=for-the-badge&logo=yarn&logoColor=white"/>
      </td>
    </tr>
         <tr>
      <td>Testing</td>
      <td>
        <img alt="Jest" src="https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white"/>      </td>
    </tr>
     <tr>
      <td>Workflow</td>
      <td>
        <img alt="Github" src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/>
        <img alt="Trello" src="https://img.shields.io/badge/Trello-%23026AA7.svg?&style=for-the-badge&logo=Trello&logoColor=white"/>
        <img alt="Slack" src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white"/>
        <img alt="Discord" src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white"/>
        <img alt="Zoom" src="https://img.shields.io/badge/Zoom-2D8CFF?style=for-the-badge&logo=zoom&logoColor=white"/>
      </td>
    </tr>
    <tr>
      <td>Deployment</td>
      <td>
        <img alt="GitHub Actions" src="https://img.shields.io/badge/githubactions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white"/>
        <img alt="AWS" src="https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" />
        <img alt="Vercel" src="https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white"/>
      </td>
    </tr>
  </tbody>
</table>

<!-- # About

**diverr** is an electronic log book for storing scuba dive records, as well as a means to share photos from dives. Traditionally, scuba divers record information from each dive in a paper log book. This can become cumbersome to search for a particular log as the number of dives increases. Enter **diverr**!  With **diverr** you can fill out a form for each dive with dive metrics, photos, and tags. The logs are compiled in a dashboard for ease of viewing. Additionally, a feed of photos displays images from all users with searchable tags. -->

<!-- ![](https://media.giphy.com/media/8oqWA5KasbsIqWLCwU/giphy.gif ) -->
<hr />

# Front End

## Welcome Page
  The site theme was inspired by a photo of a manta ray where sunlight hit the top of the water, and loses permeation of that sunlight as you descend deeper underwater. So, our palette consisted of a range of blues, from an almost white, light blue, to pure black with a touch of blue.

**Features:**

  * Animated electric page to wow new visitors
  * Sticky info box with a *Join Today* button to allow sign up no matter where users are in the feed
  * Dynamic Header based on session auth status
  * *Authentication*: OAuth sign in with Google built using NextAuth
  * *Login*: A custom login page with video background
  * *Redirects*: Authentication checks to dynamically render secured pages
  * *Never Lost*: Descriptive and Assertive page routing to lead users to accessible areas

![](https://media.giphy.com/media/l0mfQEQLQGyEBZWzGn/giphy.gif )

## Feed
**Features:**

  * *Display Public Dive Log Photos*: renders feed of photos from public dive logs uploaded by users across the planet
  * *Filter By Search Bar*: Can enter search terms in a search bar to filter posts visible in the feed
  * *Filter By Image Tag*: Can click on a tag on an image to filter posts visible in the feed

![](https://media.giphy.com/media/gkihsToPQCgBc6El4X/giphy.gif)

## View Logs Dashboard
**Features:**

  * *Log List*: Displays a list of logs, and allows the user to click a log to be displayed in the section to the right.
  * *Tag List*: Displays a list of all tags associated with a user's logs, and allows the user to click and select a tag to filter the log list by the currently selected tags.
  * *Log Display*: Displays the currently selected log data(defaults to the most recent.) The data is split into categories, and all media attached to the log is displayed in an image slider at the bottom.
  * *User Information*: Displays a greeting to the user, the amount of dives a user has logged, and the total cumulative time that a user has spent under water.
  * *No Logs Feature*: If a user has not created any logs, the view logs dashboard will consist solely of the user information box, and a button that allows the user to start logging.

 ![](https://media.giphy.com/media/m6f12JhYnV7OkQf0r0/giphy.gif)

## Add a Dive Log
**Features:**

  * *Data Collection Fields*: combination of 31 different text fields, radio buttons, and checkboxes
  * *Add Tags*: ability to include tags to make logs and photos searchable
  * *Add Media*: ability to add photos with each dive log and share on the feed

  ![](https://media.giphy.com/media/Rie2JbmhgDfqBidFZq/giphy.gif)

<hr />

# Back End - API & Database

**Back End Features:**
  * *Database*: Designed schema in Postgres to store log users and log information, including dive photos and user-created tags, along with relevant meta data
  * *Integrity*: Used relational tables, foreign keys, and unique constraints to maintain data integrity
  * *API*: Created a serverless NextJS API to interact with database
  * *Docs*: Supplied the front-end team with documents explaining the data they can expect to receive and what url to request from for that data

<hr />

# Workflow
Our team used Agile workflow for this sprint.

## Trello
A Trello board was used to create and track tickets.  We held daily scrum meetings to discuss accomplishments, challenges, and upcoming tickets.  To effectively collaborate remotely while allowing for quick communication if needed, we utilized Discord, Slack, and Zoom.

## Version Control
We implemented Git Feature Branch Workflow.  All pull requests in Github were reviewed by another team member before being merged into the main branch.

<hr />

# Development and Deployment

## CI/CD

Continuous Integration / Continuous Deployment

**CI**: Husky (Linting), GitHub Actions (Build and Testing)

**CD**: Vercel (Connected GitHub Branch)

This project was built with the above CI/CD pipeline.
The pipeline and deployment were implemented prior to any building.

  * To standardize styling we used a Husky pre-commit hook that ran Prettier and ESLint (AirBnB) through the project.
  * GitHub Actions provided another layer of protection on Pull Requests to the Master Branch by running builds on Node 12.x and 14.x, as well as running all available **Jest** tests.
  * Vercel was connected to the Master Branch and deployed all code pushed to it

<hr />

# Challenges and Learning

* The team decided to learn a new technology, NextJS, in order to implement server-side rendering and dynamic API routing.
* Due to the amount of data necessary to maintain an accurate dive log book, the back end team was faced with creating complex database queries while balancing ease of accessing data against maintaining a high degree of data integrity.
* After encountering issues with proper access to data, our back end team switched SQL databases midway through the project and still was able to deliver reliable, high-quality APIs to the front end team.
* The team used Figma to aid in designing a website that implements a pseudo-social media aspect without overshadowing the core functionality of storing dive log information per our client's request.
* In order to present a dive log input form that includes all the numerous fields without sacrificing readability, Formik was implemented to capture the necessary data.
