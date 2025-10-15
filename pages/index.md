<style>
  table {
    width: 100%;
    border-collapse: collapse;
    margin-bottom: 40px; /* Adds space between tables */
  }
  th, td {
    border: 1px solid #ddd;
    padding: 12px;
    text-align: left;
  }
  th {
    background-color: #f4f4f4;
    font-size: 1.2em;
  }
  td {
    font-size: 1em;
  }
  table colgroup col:first-child {
    width: 20% !important;
  }
  table colgroup col:last-child {
    width: 80% !important;
  }
  ul li {
    margin-bottom: 15px;
  }
</style>

# About
The Meeting on Feature-Oriented Software Development (FOSD Meeting) is a yearly informal meeting to bring together the community of researchers working on feature-oriented software development, including, but not limited to:

- Product lines
- Software variability
- Configuration management
- Software architecture

The meeting series started 17 years ago to bring several research groups with common interests closer together. It has successfully been repeated 16 times with 20 to 50 participants each, and has established countless collaborations since. For example, see the recent past FOSD meetings: [FOSD 2025 in Köthen](https://fosd.github.io/FOSD2025/) [FOSD 2024 in Eindhoven](https://set.win.tue.nl/event/fosd-meeting-2024/), and [FOSD 2023 in Ulm](https://fosd23.uni-ulm.de/).

The main objective is that researchers at different career stages (including undergraduate and early-career graduate students) come together to present their research, to get feedback from peers, to discuss new directions, and to initiate collaborations.

The format of an FOSD meeting consists of short presentations from each participant with plenty of time for discussion. Young researchers (graduate and undergraduate students), as well as more senior community members, present their research, provide and get feedback from others, engage into discussions and establish new collaborations. FOSD is a place for discussion, not a publication venue. Participants can present previously published work as well as unpublished work, including early ideas and work in progress. The key is to encourage discussions, to receive feedback and to grow the network of collaborating researchers.

## Important Dates
<table>
  <tr>
    <td>Abstract Submission Deadline</td>
    <td>December 5, 2025 </td>
  </tr>
  <tr>
    <td>Notification of Acceptance</td>
    <td>December 16, 2025 </td>
  </tr>
  <tr>
    <td>Registration Deadline</td>
    <td>TBD (estimated: February 2026) </td>
  </tr>
  <tr>
    <td>FOSD Meeting 2025</td>
    <td>March 24 - 27, 2025</td>
  </tr>
</table>

{% for conf_day in site.data.schedule %}
### Schedule {{ conf_day.day | date: "%A, %b %e" }}

{% for session in conf_day.sessions %}
Session: {{ session.from | date: "%R" }} - {{ session.to | date: "%R" }}, Chair: {{ session.chair }} 
{% for talk in session.talks %}
* **{{ talk.speaking }}**: {{ talk.title }}
{% endfor %}
{% endfor %}
{% endfor %}

# Venue & Travel Information
The FOSD Meeting 2026 will take place at University of Southern Denmark in Odense.

Odense is the third-largest city in Denmark, located on the island of Funen. Known as the birthplace of famous fairy tale writer Hans Christian Andersen, the city blends rich history with modern innovation. With its charming old town, vibrant cultural scene, and strong focus on education and technology, Odense offers a unique mix of tradition and progress.

At the heart of this vibrant environment, the University of Southern Denmark (SDU) has been dedicated to fostering talent and advancing research since its establishment in 1966. From its main campus in Odense to its regional campuses in Slagelse, Kolding, Esbjerg, and Sønderborg, SDU serves more than 27,000 students, nearly 20% of whom come from abroad, and employs over 3,800 staff members. As one of the top fifty young universities globally, SDU conducts world-class research that has a profound impact on both society and industry. Central to this ambition is the Department of Mathematics and Computer Science, where highly specialized researchers from around the world work on advanced projects that address both theoretical and practical challenges. The department’s interdisciplinary approach spans academia, business, and society, offering expertise in areas that are crucial for tackling complex issues in today’s world. Hosting several respected research centers, the department plays a key role in driving SDU’s innovation agenda, contributing significantly to both academic excellence and practical solutions that benefit a wide range of sectors inthe Danish society.

# Contact
For questions and abstract submissions, please send an email to <fosd26@lists.se.cs.uni-saarland.de>.

## Organizers
- [Sandra Greiner](https://portal.findresearcher.sdu.dk/en/persons/greiner)
- [Tobias Dick](https://www.se.cs.uni-saarland.de/people/dick.php)

## Steering Committee
- [Sven Apel](https://www.se.cs.uni-saarland.de/apel/)
- [Thomas Thüm](https://www.uni-paderborn.de/person/102807)
