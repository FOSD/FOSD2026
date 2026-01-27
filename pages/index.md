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

The meeting series started 17 years ago to bring several research groups with common interests closer together. It has successfully been repeated 16 times with 20 to 50 participants each, and has established countless collaborations since. For example, see the recent past FOSD meetings: [FOSD 2025 in Köthen](https://fosd.github.io/FOSD2025/), [FOSD 2024 in Eindhoven](https://set.win.tue.nl/event/fosd-meeting-2024/), and [FOSD 2023 in Ulm](https://fosd23.uni-ulm.de/).

The main objective is that researchers at different career stages (including undergraduate and early-career graduate students) come together to present their research, to get feedback from peers, to discuss new directions, and to initiate collaborations.

The format of an FOSD meeting consists of short presentations from each participant with plenty of time for discussion. Young researchers (graduate and undergraduate students), as well as more senior community members, present their research, provide and get feedback from others, engage into discussions and establish new collaborations. FOSD is a place for discussion, not a publication venue. Participants can present previously published work as well as unpublished work, including early ideas and work in progress. The key is to encourage discussions, to receive feedback and to grow the network of collaborating researchers.

## Supporters



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
    <td>FOSD Meeting 2026</td>
    <td>March 23 - 27, 2026</td>
  </tr>
</table>

# Participants
<table>
  <tr>
    <th>Name</th>
    <th>Title</th>
    <th>University</th>
  </tr>
  {% for item in site.data.participants | sort: "name" %}
    <tr>
      <td width="20%">{{ item.name }}</td>
      <td width="55%">{{ item.title }} {% if item.link != null %}<a href="{{ item.link }}" target="_blank">[slides]</a>{% endif %}</td>
      <td width="25%">{{ item.university }}</td>
    </tr>
  {% endfor %}

</table>

# Venue & Travel Information
The FOSD Meeting 2026 will take place at University of Southern Denmark in Odense.

Odense is the third-largest city in Denmark, located on the island of Funen. Known as the birthplace of famous fairy tale writer Hans Christian Andersen, the city blends rich history with modern innovation. With its charming old town, vibrant cultural scene, and strong focus on education and technology, Odense offers a unique mix of tradition and progress.

At the heart of this vibrant environment, the University of Southern Denmark (SDU) has been dedicated to fostering talent and advancing research since its establishment in 1966. From its main campus in Odense to its regional campuses in Slagelse, Kolding, Esbjerg, and Sønderborg, SDU serves more than 27,000 students, nearly 20% of whom come from abroad, and employs over 3,800 staff members. As one of the top fifty young universities globally, SDU conducts world-class research that has a profound impact on both society and industry. Central to this ambition is the Department of Mathematics and Computer Science, where highly specialized researchers from around the world work on advanced projects that address both theoretical and practical challenges. The department’s interdisciplinary approach spans academia, business, and society, offering expertise in areas that are crucial for tackling complex issues in today’s world. Hosting several respected research centers, the department plays a key role in driving SDU’s innovation agenda, contributing significantly to both academic excellence and practical solutions that benefit a wide range of sectors inthe Danish society.

## Traveling to Odense

### By train:
  Getting to Odense is most confeniently taking a train, which stops at Odense’s main station (Odense St.). Trains are operated by [DSB](https://www.dsb.dk/en/) and tickets can be bought on their website.
  Coming from Germany, the easiest connection is the EC Hamburg-Copenhagen which takes approx **3.5 hours** and runs every 2 hours. Tickets can be bought from [Deutsche Bahn](https://int.bahn.de/en?dbkanal_007=sprachauswahl-en).

### By plain:

* _Copenhagen Airport_ (CPH): There is a direct train line to Odense from the airport. The ticketing office and the exit to the platforms is in the lobby of Terminal 3 at the airport. 
Travel time: approximately **1.5 hours**.

* _Billund Airport_ (BLL): The trip from Billund Airport is a combined bus+train ride. There is a direct bus line from Billund Airport to **Vejle** main train station. From there, you can take a direct train to Odense. Travel time: approximately **2 hours**.

* _Aarhus Airport_ (AAR): The trip from Aarhus Airport is also a combined bus+train ride. There is a direct bus line to Aarhus Train Station (Aarhus H). From there, you can take a direct train to Odense. Travel time: approximately **2.5 hours**.

## Getting around in Odense

Starting from the train station, it is easiest to take the light rail train (Letbane) to reach SDU. Tickets can be bought directly from [Odense Letbane](https://letbanebillet.dk/) or by scanning the QR-Code on the stations. You can recognize the stations based on the large O. 

From other places, you can take the bus (operated by [FynBus](https://en.fynbus.dk/)). You can plan your trips using  [Rejseplanen](https://www.rejseplanen.dk) (Journey Planner) and follow its instructions. Tickets can be purchased through [Rejsebillet](https://www.rejsekort.dk/da/rejsebillet?sc_lang=en).

Apart from that, many sight in the inner city can easily be reached by foot.

# Contact
For questions and abstract submissions, please send an email to <fosd26@lists.se.cs.uni-saarland.de>.

## Organizers
- [Sandra Greiner](https://portal.findresearcher.sdu.dk/en/persons/greiner)
- [Tobias Dick](https://www.se.cs.uni-saarland.de/people/dick.php)

## Steering Committee
- [Sven Apel](https://www.se.cs.uni-saarland.de/apel/)
- [Thomas Thüm](https://www.uni-paderborn.de/person/102807)
