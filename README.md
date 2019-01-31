# Learning in Collective Self-adaptive Systems
**Collective self-adaptive systems (CSAS)** are distributed and interconnected systems composed of multiple agents that can perform complex tasks. By providing individual agents with learning capabilities, CSAS can cope with challenges related to distributed sensing and decision-making, and operate in uncertain environments. Although learning has been explored in many CSAS applications, selecting suitable learning techniques and models remains a significant challenge.

# Goal
The goal of our systematic literature review is to understand the state of practice on how learning is employed in CSAS. To this end, we investigate related research that involve the development of CSAS employing learning techniques. We are particularly interested in the studies employing learning in CSAS to enable agents to adapt their behavior when encountering scenarios unanticipated at design time.

# Research Questions

- **RQ1**: What are the characteristics of the described CSAS?
  - Application Domain (**RQ1**): classify the domain of the
developed CSAS application;
  - Agents (**RQ1**): identify agents within the collective with
learning abilities;
  - Autonomy (**RQ1**): determine whether agents act autonomously
or are supervised by external entities;
  - Knowledge Access (**RQ1**): assess the amount of information
provided to an agent by its peers;
  - Behaviour (**RQ1**): evaluate how an agent behaves with
respect to other agents’ behaviour;

- **RQ2**: What is the purpose of learning?
  - Learning Tasks (**RQ2**): establish the objectives of learning
by an agent and the collective;
  - Emergent Behaviour (**RQ2**): determine which characteristics
emerge from agents’ interactions and are observed as outcomes of agents’ behaviour;

- **RQ3**: Which are the selected learning techniques?
  - Learning Technique (**RQ3**): classify the techniques used
by agents to enable learning;

- **RQ4**: What are the triggers for updating learning models?
  - Learning Trigger (**RQ4**): identify the triggers driving
knowledge processing and refinement of learning models.

# Research Method
Our investigation is made by means of a systematic literature review (SLR) of 52 related research papers out of 215 preliminary candidates.

# Documents
**Replication package**: The following [link](https://drive.google.com/open?id=1tkX0cTYFzkTWq-KWRimPkrowaW_ZvoRs) points to the replication document.

**Collected Data**: The following [link](https://docs.google.com/spreadsheets/d/1tD9yaWa7JfokEHNGdw5sMem09e-y5FuAhfuI7Av2VYw/edit#gid=1392946669) points to the analysed literature and corresponding data collected in a Google sheet.

# Results
Based on the analysis of the selected studies, we report here our findings.

## Application Domain
The most dominant applications are cyber-physical systems (CPS) such as robotics, sensor systems and smart energy applications.
This is inline with the increasing interest in CPS, especially in the area of self-adaptive systems. Network-based applications
are the second most explored domain. Other applications include traffic scenarios, cooperative games, and market applications. Finally, four studies describe the solution to learning in CSAS using abstract multi-agent organisational models but do not report any concrete applications.

<p align="center">
  <img height="200" src='images/Fig2.ApplicationDomain.png'/>
</p>

## Autonomy, Knowledge Access, and Behaviour

* We define CSAS **autonomy** to be the level of self-authorisation provided to agents within the collective. An agent is autonomous when there is no external or internal (i.e., by other agents) control over its behaviour.

* Our analysis reveals that some agent-based models explicitly exchange learning information with each other. We call this concept **knowledge access**.

* The **behaviour** of agents within a CSAS indicates whether an agent has the objective to maximise its own utility, i.e., it is selfish, to maximise the CSAS utility, i.e., it is altruistic, or adopts an intermediate role.

The results for these 3 dimensions are reported in the following table.

<p align="center">
  <img height="300" src='images/Tab3.AutonomyKnowledgeBehaviour.png'/>
</p>





### From Domain to papers
![Vis](images/domaintopaper.png)

**NOTE:** Papers are identified by unique numbers in our [literature review](https://docs.google.com/spreadsheets/d/1tD9yaWa7JfokEHNGdw5sMem09e-y5FuAhfuI7Av2VYw/edit#gid=1392946669)

