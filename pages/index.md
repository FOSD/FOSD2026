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

<a href="https://www.carlsbergfondet.dk/en"><img src="assets/img/cf-logo.jpg" alt="Carlsberg-Logo" style="width: 60%;"></a>

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
    <td>March 12, 2026 </td>
  </tr>
  <tr>
    <td>FOSD Meeting 2026</td>
    <td>March 23 - 27, 2026</td>
  </tr>
</table>

# Keynotes

<b>Variability in Formal Methods: the cases of Lean and CSLib</b><br>
<i>Fabrizio Montesi (University of Southern Denmark)</i>

__Abstract:__ AI systems for coding are making impressive progress, but they are also infamous for making mistakes. At the same time, AI has become effective at finding vulnerabilities – an easier problem compared to producing bug-free code. In response to this pressure, another wave has been rising like never before: the development of formal methods and proof assistants for the mechanical verification of code and models. 

CSLib is a global initiative to formalise the world's knowledge on computer science and put it to use for real-world software development, using Lean as the engine for proof development and verification. The aim is to offer a platform powerful enough to help in the machine-checked development of new results and programs, developed by AI or humans. The success of CSLib requires finding reusable abstractions and providing shared infrastructure, which is challenging when formalising computer science. A lot of theories and systems are extensions or variants of others, which can lead to lots of copy-pasting and fragmentation. Variability, therefore, plays a crucial role. 

In this talk, I will give an introduction to CSLib and present some of the variability challenges in maintaining such a broad codebase of computer science. I will then engage in an open, hands-on conversation about how the formal methods and variability communities can mutually benefit from each other and join forces in contributing to a future where software and computer science results at large – even those produced by AI – come with machine-checkable specifications and proofs of what they do.

__CV:__ Fabrizio Montesi is Professor of Computer Science at the University of Southern Denmark (SDU) and Chair at the Danish Institute for Advanced Study (DIAS). He is Director of FORM – the Centre for Formal Methods and Future Computing – and Head of the Section of Artificial Intelligence, Cybersecurity, and Programming Languages at SDU.
His work focuses on programming languages and systems, formal methods and reasoning, distributed systems, and trustworthy computing, with particular contributions to choreographic programming, microservices, and the verification of computer systems. 

---

<b>Variability Never Rests: From ECU Development Through Production to Aftersales in Automotive OEM Systems</b><br>
<i>Oliver Kopp (University of Hamburg)</i>

__Abstract:__ Automotive original equipment manufacturers (OEMs) operate among the most demanding software product line environments on the planet. A single vehicle model may involve 40–200 Electronic Control Units (ECUs), over 100 million lines of code, and millions of theoretically valid variant configurations — yet every car rolling off the line is exactly one of them.

This keynote argues that variability in automotive systems is not a modelling problem confined to development time. It is a lifecycle-spanning operational challenge: a variant decision made during ECU development or by the customer at order time determines what is tested on the assembly line, which item selection rules fire in production, and which spare parts a workshop can actually install a decade later.

Drawing on three lines of industrial research — distributed ECU integration for automotive OEMs, executable variant-aware test workflows in software-defined car manufacturing, and graphical tooling for item selection rules in feature combination rule contexts — this talk traces variability through four lifecycle phases: ECU development, ECU testing, production, and aftersales. At each phase, we identify concrete industrial challenges that invite closer collaboration between variability research and automotive practice.

__CV:__ Dr. Oliver Kopp is Acting Professor at the University of Hamburg, leading the Software Engineering and Construction Methods (SWK) group. His current research focuses on software architecture and making architectural decisions sustainable and usable in practice — most notably through the widely adopted Markdown Architectural Decision Records (MADR) format and its successor YADR, both developed in the open-source adr community. His broader work spans software engineering, business process management, and cyber-physical systems — including earlier industrial research on variability in automotive OEM systems that forms the basis of this keynote.

---

<b>Managing language variants in software engineering for variant-rich production systems</b><br>
<i>Bianca Wiesmayr (Johannes Kepler University Linz)</i>

__Abstract:__ Industrial manufacturing systems need to be flexible and adaptable to allow for continuous evolvution along their life cycle, which can span
several decades. 
In these systems, hardware and software components
interact tightly to realize a production process (so-called cyber-physical production systems, CPPS). Engineers from different domains collaborate to design and implement CPPSs, including mechanical,
electrical, and software engineering. Different domain-specific notations and tools are used in each subdomain. Some of them promise harmony as they are defined in standards, but reality proves otherwise.

This talk will show the challenges and strategies for dealing with
real-life variability of the syntax and semantics of
programming/modeling languages in various environments.

__CV:__ Bianca Wiesmayr is a postdoctoral researcher at the Institute of Business Informatics - Software Engineering in Linz, where she leads a research project on model-driven control software engineering. She has completed her doctoral degree in technical sciences in 2023 (subject computer science) at the Johannes Kepler University in Linz, Austria. She researches model-driven methods for developing automation software and the usability of modeling tools. Her dissertation investigated the use of behavior models for the implementation and maintenance of control software in the domain-specific modeling language defined in IEC 61499. In addition to her research, she is an active software developer for the open-source development environment Eclipse 4diac, which provides an infrastructure for engineering Industry 4.0 and IIoT systems and is used in industry and academia.

# Program

## Rooms

<b>Getting to the university:</b> Coming from the city, the easiest way on all days is to take the Letbane and exit at <b>SDU University</b> (not SDU Campus). This is the second stop with SDU in the name.

<b>Tuesday reception</b> from 17:00 at <b>IMADA Forskertorv</b>: <a href="https://clients.mapsindoors.com/sdu/573f26e4bc1f571b08094312/details/563cb9ac423b7d0540c9a914" target="_blank">view on map</a>

<b>Tuesday &amp; Wednesday - Room U48:</b> <a href="https://clients.mapsindoors.com/sdu/573f26e4bc1f571b08094312/details/563cba14423b7d0540c9ac7d" target="_blank">view on map</a><br>
From the stop, turn directly left towards entrance <b>Gydehutten S</b>. From there, take the stairs up to the second floor. U48 will be right in front of you.

<b>Thursday &amp; Friday - IMADA Conference Room:</b> <a href="https://clients.mapsindoors.com/sdu/573f26e4bc1f571b08094312/details/563cb9be423b7d0540c9a9aa" target="_blank">view on map</a><br>
We will show the room at the reception.


## Schedule

The list of speakers for each session will be announced on the preceding day.

<table>
  <tr>
    <th>Time</th>
    <th>Monday (23th March)</th>
  </tr>
  <tr>
    <td>during the day</td>
    <td>Arrival</td>
  </tr>
  <tr>
    <td>19:00 – open end</td>
    <td><a href="https://stormspakhus.dk/"> Storms Pakhus</a></td>
  </tr>

  <tr>
    <td style="border-left: none; border-right: none;"></td>
    <td style="border-left: none; border-right: none;"></td>
  </tr>
  <tr>
    <th>Time</th>
    <th>Tuesday (24th March), <a href="https://clients.mapsindoors.com/sdu/573f26e4bc1f571b08094312/details/563cba14423b7d0540c9ac7d">U48</a></th> 
  </tr>
  <tr>
    <td>08:45</td>
    <td>Registration</td>
  </tr>
  <tr>
    <td>09:00</td>
    <td>Opening</td>
  </tr>
  <tr>
    <td>09:15</td>
    <td>
      <b>Keynote:</b> Fabrizio Montesi (University of Southern Denmark)<br>
      <i>Variability in Formal Methods: the cases of Lean and CSLib</i>
    </td>
  </tr>
  <tr>
    <td>10:15</td>
    <td>Coffee Break</td>
  </tr>
  <tr>
    <td>10:45</td>
    <td>
      <b>Session 1</b>
       <ul>
        <li>Malte Lochau (University of Siegen)<br><i>Sampling-based Testing for Partial Quantum State Tomography</i></li>
        <li>Tim Bächle (Karlsruhe Institute of Technology)<br><i>Towards Family-Based Vulnerability Discovery for Highly-Configurable Software Systems</i></li>
        <li>Rahel Sundermann (TU Braunschweig)<br><i>Fixing Feature Mappings</i></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>12:15</td>
    <td>Lunch</td>
  </tr>
  <tr>
    <td>13:15</td>
    <td>
      <b>Session 2</b>
      <ul>
        <li>Mathis Weiß (University of Siegen)<br><i>Modeling Approaches and Testing Strategies for Independent Features in Configurable Software</i></li>
        <li>Norbert Siegmund (Leipzig University)<br><i>The Promise of Tailor-Made Software: From Tale to Reality</i></li>
        <li>Tobias Dick (Saarland University)<br><i>Exceptional Configuration Subspaces with Subgroup Discovery: What Works Best?</i></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>14:30</td>
    <td>Coffee Break</td>
  </tr>
  <tr>
    <td>15:00</td>
    <td>
      <b>Session 3</b>
        <ul>
          <li>Sebastian Böhm (Saarland University)<br><i>Exploring the Effects of Feature Granularity and Data-Flow Complexity on Program Comprehension</i></li>
          <li>Sebastian Krieter (TU Braunschweig)<br><i>Tackling Expressive FM Constructs with Pseudo-Boolean d-DNNF Compilation</i></li>
          <li>Sebastian Simon (Leipzig University)<br><i>A Socio-Technical Perspective on Configuration Spaces: Insights into Technology Ecosystems, Contributor Dynamics, and Evolution in Open-Source Software Projects</i></li>
        </ul>
    </td>
  </tr>
  <tr>
    <td>from 17:00</td>
    <td>Reception at <a href="https://clients.mapsindoors.com/sdu/573f26e4bc1f571b08094312/details/563cb9ac423b7d0540c9a914">IMADA Forskertorv</a> 
    </td>
  </tr>

  <tr>
    <td style="border-left: none; border-right: none;"></td>
    <td style="border-left: none; border-right: none;"></td>
  </tr>
  <tr>
    <th>Time</th>
    <th>Wednesday (25th March), <a href="https://clients.mapsindoors.com/sdu/573f26e4bc1f571b08094312/details/563cba14423b7d0540c9ac7d">U48</a></th>
  </tr>
  <tr>
    <td>09:15</td>
    <td>
      <b>Keynote:</b> Bianca Wiesmayr (Johannes Kepler University Linz) <br>
      <i>Managing language variants in software engineering for variant-rich production systems</i>
    </td>
  </tr>
  <tr>
    <td>10:15</td>
    <td>Coffee Break</td>
  </tr>
  <tr>
    <td>10:45</td>
    <td>
      <b>Session 4</b>
      <ul>
        <li>Christopher Rau (TU Braunschweig)<br><i>Mining Bugs in Linux to Assess the Effectiveness of Automated Variability Testing</i></li>
        <li>Malte Grave (Johannes Kepler Universität Linz)<br><i>Explaining Why: Towards Explainable SMT-Based Consistency Checking in Variability-Intensive Cyber-Physical Production Systems</i></li>
        <li>Dirk Neumann (KIT)<br><i>The Variability-Aware Virtual Single Underlying Model: Operationalizing Variability and Developing Consistent Product Lines</i></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>12:00</td>
    <td>Lunch</td>
  </tr>
  <tr>
    <td>13:00</td>
    <td>
      <b>Session 5</b>
      <ul>
        <li>Simon Bothe (KIT)<br><i>Enabling Cross-Domain Consistency Preservation for Delta-Oriented Product Line Development</i></li>
        <li>Francisco Mayo (University of Seville)<br><i>Toward an Innovation-Oriented SPL Methodology for On-Premise Intelligent Systems</i></li>
        <li>Roman Bögli (University of Bern)<br><i>Exploring Community-Driven Variability: The Bitcoin Case</i></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>14:15</td>
    <td>Coffee Break</td>
  </tr>
  <tr>
    <td>14:45</td>
    <td>
      <b>Session 6</b>
      <ul>
        <li>Bjarke Hamerbak Pawulewski (University of Southern Denmark)<br><i>Feature Model Synthesis</i></li>
        <li>Evelyn Rühl (University of Siegen)<br><i>Feature Localization based on Large Language Models</i></li>
        <li>Simon Butt (University of Siegen)<br><i>Reconstruction of Cardinality-Based Feature Models</i></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>from 18:30</td>
    <td>Dinner at <a href="https://cafevivaldi.dk/cafe/odense-vestergade/">Cafe Vivaldi</a>
    </td>
  </tr>

  <tr>
    <td style="border-left: none; border-right: none;"></td>
    <td style="border-left: none; border-right: none;"></td>
  </tr>
  <tr>
    <th>Time</th>
    <th>Thursday (26th March), <a href="https://clients.mapsindoors.com/sdu/573f26e4bc1f571b08094312/details/563cb9be423b7d0540c9a9aa">IMADA Conference room</a></th>
  </tr>
  <tr>
    <td>09:15</td>
    <td>
      <b>Keynote:</b> Oliver Kopp (University of Hamburg)<br>
      <i>Variability Never Rests: From ECU Development Through Production to Aftersales in Automotive OEM Systems</i>
    </td>
  </tr>
  <tr>
    <td>10:15</td>
    <td>Coffee Break</td>
  </tr>
  <tr>
    <td>10:45</td>
    <td>
      <b>Session 7</b>
      <ul>
        <li>Tim Schmidt (Ulm University)<br><i>A Revised Classification of Product Sampling for Software Product Lines</i></li>
        <li>Morten Harter (KIT)<br><i>Modularity, Variability and Evolution for Threat Analysis and Risk Assessment</i></li>
        <li>Sandra Kaae Johansen & Sofie Løfberg (University of Southern Denmark)<br><i> Why your grandma was a computer scientist? - A special configuration use case</i></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>12:00</td>
    <td>Lunch</td>
  </tr>
  <tr>
    <td>13:00</td>
    <td>
      <b>Session 8</b>
      <ul>
        <li>Francisco Diaz (University of Seville)<br><i>Integration of Feature Models into the Model Context Protocol (MCP) for Dynamic Configuration of Data Analysis Interfaces</i></li>
        <li>Stefan Sobernig (WU Wien)<br><i>Staged adaptation of a general-purpose large-language model for building a localised UVL code recommender</i></li>
        <li>Raphael Dunkel (TU Braunschweig)<br><i>Engineering and Selecting Machine Learning Features for Feature Models</i></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>14:25</td>
    <td>Coffee Break</td>
  </tr>
  <tr>
    <td>16:30</td>
    <td>
    <a href="https://brandts.dk/"> Brandts Museum</a>
    </td>
  </tr>
  <tr>
    <td>from 18:30</td>
    <td>Dinner at <a href="https://marcantonio.dk/en/">Marcantonio</a>
    </td>
  </tr>
  <tr>
    <td>afterwards</td> 
    <td>Papas Papbar</td>
  </tr>

  <tr>
    <td style="border-left: none; border-right: none;"></td>
    <td style="border-left: none; border-right: none;"></td>
  </tr>
  <tr>
    <th>Time</th>
    <th>Friday (27th March), <a href="https://clients.mapsindoors.com/sdu/573f26e4bc1f571b08094312/details/563cb9be423b7d0540c9a9aa">IMADA Conference room</a></th>
  </tr>
  <tr>
    <td>09:00</td>
    <td>
      <b>Session 9</b>
      <ul>
        <li>Thomas Thüm (TU Braunschweig)<br><i>WIFI - What is a Feature Interaction?</i></li>
        <li>Lukas Abelt (Saarland University)<br><i>Pitfalls, challenges and learnings when adopting new approaches for performance benchmarking of configurable software systems</i></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>09:50</td>
    <td>Coffee Break</td>
  </tr>
  <tr>
    <td>10:00</td>
    <td>
      <b>Session 10</b>
      <ul>
        <li>Kallistos Weis (Saarland University)<br><i>Time-Aware Performance-Influence Modeling in the Spectral Domain</i></li>
        <li>Ruben Dunkel (TU Braunschweig)<br><i>Towards the Extraction of Implicit Variability From R Research Scripts</i></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>10:50</td>
    <td>Closing</td>
  </tr>
  <tr>
    <td>11:00</td>
    <td>(Takeaway) Lunch</td>
  </tr>
</table>

# Venue & Travel Information
The FOSD Meeting 2026 will take place at University of Southern Denmark in Odense.
<div style="display: flex; gap: 15px; margin: 10px 0;">
  <img src="assets/img/paaskestræde-small.jpg" alt="Odense street view" style="width: 49%;">
  <img src="assets/img/nelles.jpg" alt="Odense main entrance" style="width: 49%;">
</div>
Odense is the third-largest city in Denmark, located on the island of Funen. Known as the birthplace of famous fairy tale writer Hans Christian Andersen, the city blends rich history with modern innovation. With its charming old town, vibrant cultural scene, and strong focus on education and technology, Odense offers a unique mix of tradition and progress.

At the heart of this vibrant environment, the University of Southern Denmark (SDU) has been dedicated to fostering talent and advancing research since its establishment in 1966. From its main campus in Odense to its regional campuses in Slagelse, Kolding, Esbjerg, and Sønderborg, SDU serves more than 27,000 students, nearly 20% of whom come from abroad, and employs over 3,800 staff members. As one of the top fifty young universities globally, SDU conducts world-class research that has a profound impact on both society and industry. Central to this ambition is the Department of Mathematics and Computer Science, where highly specialized researchers from around the world work on advanced projects that address both theoretical and practical challenges. The department’s interdisciplinary approach spans academia, business, and society, offering expertise in areas that are crucial for tackling complex issues in today’s world. Hosting several respected research centers, the department plays a key role in driving SDU’s innovation agenda, contributing significantly to both academic excellence and practical solutions that benefit a wide range of sectors inthe Danish society.

## Traveling to Odense

### Arrival by Train
Getting to Odense is most convenient by train, which stops at Odense’s main station (Odense St.). Trains are operated by [DSB](https://www.dsb.dk/en/) and tickets can be bought on their website.
  
Coming from Germany, the easiest connection is the EC Hamburg-Copenhagen which takes approximately **3.5 hours** and runs every 2 hours. Tickets can be bought from [Deutsche Bahn](https://int.bahn.de/en?dbkanal_007=sprachauswahl-en).

### Arrival by Plane

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
- [Sandra Greiner](https://sandragreiner.github.io/)
- [Tobias Dick](https://www.se.cs.uni-saarland.de/people/dick.php)

### Local Organization

- [Ursula Lundgreen Svane](https://portal.findresearcher.sdu.dk/da/persons/ursula-lundgreen-svane/)

## Steering Committee
- [Sven Apel](https://www.se.cs.uni-saarland.de/apel/)
- [Thomas Thüm](https://www.uni-paderborn.de/person/102807)
