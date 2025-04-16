![track](https://github.com/user-attachments/assets/d84189e6-1014-4e06-ba56-055bcacd798d)

<p align="center">
    <a href="https://github.com/iNineBD/Track-5Sem2025Front">Frontend</a> |
    <a href="https://github.com/iNineBD/Track-5Sem2025Server">Backend</a> |
    <a href="https://github.com/iNineBD/Track-5Sem2025ETL">ETL</a> |
    <a href="#context">Context</a> |
    <a href="#contributors">Contributors</a> |
    <a href="#requirements" >Requirements</a> |
    <a href="#backlog">Product Backlog</a> |
    <a href="#sprints">Sprints</a> |
    <a href="#other-docs">Other Documentation</a> |
    <a href="#technologies">Technologies</a>
</p>

<span id="context">

## ◻️ Context
The project aims to develop a performance management and project tracking platform, focused on providing visibility and insights into metrics and indicators in a dynamic and intuitive way. The platform will be used by different user profiles, each with specific needs, but with the common goal of improving efficiency and data-driven decision-making.

<span id="contributors">

## ◻️ Contributors

<div align="left">
  
  | **FUNCTION** | **NAME** | **SOCIAL MEDIA** |
  | :---: | :--- | :---: |
  | Product Owner | Ana Raquel | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/ana-sasaki-19a2031b8/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Anaraquely) |
  | Scrum Master | Lucas Henrique | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/lucas-henrique-9a557620b) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/LucasHCOliveira7) |
  | Developer | Ali Mohamed | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/alimohamedkhodr/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/alimkhodr) |
  | Developer | Alita Amancio | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/alitaamancio/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/AlitaAmancio) |
  | Developer | André Bernardes | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/andre-oliveira2004) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Andre-Bernardes200) |
  | Developer | Eduardo Farias | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/eduardofariasp/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/eduardofpaula) |
  | Developer | Willian Antoniazzi | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/williamantoniazzi/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/williamantoniazzi) |

</div>

<span id="requirements">
    
## ◻️ Functional and Non-Functional Requirements

<table>
    <tr>
        <th>ID</th>
        <th>Functional Requirement</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>RF01</td>
        <td>Cards by tag</td>
        <td>Display the number of cards per tag</td>
    </tr>
    <tr>
        <td>RF02</td>
        <td>Cards per employee</td>
        <td>Display the number of cards per collaborator</td>
    </tr>
    <tr>
        <td>RF03</td>
        <td>Cards by status (Kanban columns)</td>
        <td>Display the number of cards by status based on the Kanban board columns (In Progress, In Review, Done, etc.)</td>
    </tr>
    <tr>
        <td>RF04</td>
        <td>Cards created by period</td>
        <td>Display the number of cards created for a given period.</td>
    </tr>
    <tr>
        <td>RF05</td>
        <td>Cards completed by period</td>
        <td>Display the number of completed cards for a given period.</td>
    </tr>
    <tr>
        <td>RF06</td>
        <td>Average card execution time</td>
        <td>Display the average time it takes for a card to complete</td>
    </tr>
    <tr>
        <td>RF07</td>
        <td>Reworks</td>
        <td>View the amount of rework in the system (cards that have returned from the Completed column to In Progress)</td>
    </tr>
    <tr>
        <td>RF08</td>
        <td>Access control by levels</td>
        <td>Managing the display of indicators from different access levels (admin, manager and operator)</td>
    </tr>
    <tr>
        <td>RF09</td>
        <td>Integration with other systems</td>
        <td>Create an API for integration with other systems such as Trello and Jira</td>
    </tr>
</table>

<table>
    <tr>
        <th>ID</th>
        <th>Non-Functional Requirements</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>RNF01</td>
        <td>API Documentation</td>
        <td>The API must have clear and detailed documentation.</td>
    </tr>
    <tr>
        <td>RNF02</td>
        <td>Responsiveness</td>
        <td>The system must be responsive and accessible on different devices (Desktop and Mobile)</td>
    </tr>
    <tr>
        <td>RNF03</td>
        <td>User Manual</td>
        <td>A manual must be provided to guide users in using the system.</td>
    </tr>
    <tr>
        <td>RNF04</td>
        <td>Database Modeling</td>
        <td>Create an efficient database model (DW) to store all project information</td>
    </tr>
</table>

<span id="backlog">

## ◻️ Product Backlog

<table>
    <tr>
        <th>Rank</th>
        <th>ID Requirement</th>
        <th>User Stories</th>
        <th>Priority</th>
        <th>Sprint</th>
        <th>Status</th>
    </tr>
    <tr>
        <td>1</td>
        <td>RF08, RNF01, RNF02, RNF04</td>
        <td>As an administrator, I want to view all projects on the Taiga management platform and their relevant indicators and measurements, to monitor the performance of each one.</td>
        <td>1</td>
        <td>1</td>
        <td>✅ Done</td>
    </tr>
    <tr>
        <td>2</td>
        <td>RF01, RF02, RF03, RNF01, RNF02, RNF03</td>
        <td>As a user, I want to view dashboards with card metrics (by tag, collaborator and status) to monitor results in a dynamic and intuitive way.</td>
        <td>2</td>
        <td>1</td>
        <td>✅ Done</td>
    </tr>
    <tr>
        <td>3</td>
        <td>RF08, RNF02</td>
        <td>As an administrator, I want to log in securely with my credentials to access all team and project indicators.</td>
        <td>4</td>
        <td>2</td>
        <td>🚧 In Progress</td>
    </tr>
    <tr>
        <td>4</td>
        <td>RF08, RNF02</td>
        <td>As an operator, I want to log in securely with my credentials to access only my own performance indicators.</td>
        <td>2</td>
        <td>2</td>
        <td>🚧 In Progress</td>
    </tr>
    <tr>
        <td>5</td>
        <td>RF08, RNF02</td>
        <td>As a manager, I want to log in securely with my credentials to access only my and my team's performance indicators.</td>
        <td>3</td>
        <td>2</td>
        <td>🚧 In Progress</td>
    </tr>
    <tr>
        <td>6</td>
        <td>RF04, RF05, RF06, RF07, RNF01, RNF02, RNF03</td>
        <td>As a user, I want to view dashboards with metrics on cards created by period (last 7 days), cards completed by period (last 7 days), as well as the average card execution time and rework, to monitor the efficiency of processes through dashboards.</td>
        <td>1</td>
        <td>2</td>
        <td>🚧 In Progress</td>
    </tr>
    <tr>
        <td>7</td>
        <td>RF01, RF02, RF03, RF04, RF05, RF06, RF07, RNF02, RNF03</td>
        <td>As a user, I want to filter the metrics and indicators in the dashboards to get only the information that is relevant for my analysis.</td>
        <td>1</td>
        <td>3</td>
        <td>-</td>
    </tr>
    <tr>
        <td>8</td>
        <td>RF09, RNF01, RNF04</td>
        <td>As a user, I want the system to allow integration with Trello and Jira platforms, so that I can pull project metrics. This will help me consolidate information in one place, making analysis and decision-making easier.</td>
        <td>1</td>
        <td>3</td>
        <td>-</td>
    </tr>

</table>

<span id="sprints">

## ◻️ Sprints

| SPRINTS | PERIODS | KEYWORD | DESCRIPTION |
|:-------:|:-----:|:---------:|:---------:|
| Kick-off | 27/02/2025 | - | Initial team alignment, presentation of the project theme (Track), and definition of roles and responsibilities. |
| [Sprint 1](https://github.com/iNineBD/Track-5Sem2025Main/wiki/Sprint-1) | 10/03/2025 to 30/03/2025 | initials dashboards and project screen  | Deliver the basic functionalities for project visualization and dashboards, establishing the foundation for the development of more advanced features in the upcoming sprints. |
| [Sprint 2](https://github.com/iNineBD/Track-5Sem2025Main/wiki/Sprint-2) | 07/04/2025 to 27/04/2025 | access management and dashboards | Deliver a secure authentication system and expand the functionalities of the dashboards. |
| [Sprint 3](https://github.com/iNineBD/Track-5Sem2025Main/wiki/Sprint-3) | 05/05/2025 to 25/05/2025 | advanced filters  | Deliver filtering functionalities that allow users to customize the visualization of metrics and indicators on the dashboards. |
| Feira de Soluções | 29/05/2025 | final presentation | Present the final version of the Track system, demonstrating its key functionalities and how it meets the project’s objectives and user needs. |

<span id="other-docs">

## Other documentation

- <a href="https://www.figma.com/design/Cwg09HW9o8iOQ8hKjYlLXK/Untitled?node-id=0-1&p=f&t=fwIKVwqYRZ1fFAUT-0">Wireframes</a>
- <a href="https://github.com/iNineBD/Track-5Sem2025Main/blob/main/documentation/patterns.md">Project Patterns</a>
- <a href="">User Manual</a>
- <a href="">Database</a>
- <a href="">Project Documentation</a>

<span id="technologies">

## ◻️ Technologies

![track-technologies](https://github.com/user-attachments/assets/a103e5df-77a6-476f-a2e7-761cb0c90c75)
