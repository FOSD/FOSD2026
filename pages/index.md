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
TBD

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
Coming soon.

# Contact
Coming soon.

## Organizers
- [Sandra Greiner](https://portal.findresearcher.sdu.dk/en/persons/greiner)
- [Tobias Dick](https://www.se.cs.uni-saarland.de/people/dick.php)

## Steering Committee
- [Sven Apel](https://www.se.cs.uni-saarland.de/apel/)
- [Thomas Thüm](https://www.uni-paderborn.de/person/102807)
