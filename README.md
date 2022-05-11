<h1 align="center">
  <a href="https://github.com/Standards-and-Practices/structured-rapid-development">
    <img src="./logo.png" alt="Structured Rapid Development" width="128" /><br/>
  </a>
</h1>

<div align="center">
  Design Patterns to Streamline Learning Design and Development.
  <br />
  <br />
  <a href="https://github.com/Standards-and-Practices/structured-rapid-development/issues/new?assignees=&labels=bug&template=01_BUG_REPORT.md&title=bug%3A+">Report a Bug</a>
  ·
  <a href="https://github.com/Standards-and-Practices/structured-rapid-development/issues/new?assignees=&labels=enhancement&template=02_FEATURE_REQUEST.md&title=feat%3A+">Request a Pattern</a>
  .
  <a href="https://github.com/Standards-and-Practices/structured-rapid-development/discussions">Ask a Question</a>
</div>

WGU's vision is to be the world's most innovative, student-centric university. 

Structured Rapid Development uses these design patterns to streamline the learning product design and development.


<details open="open">
<summary>Table of Contents</summary>

- [Pathways](#pathway-patterns) - The journey a learner will go on.
- [Learning Experiences](#learning-experience-patterns) - Learning experiences on the journey that encourage learning.
    - [Case Patterns](#case-patterns)
    - [Practice Patterns](#practice-patterns)
    - [Problem Patterns](#problem-patterns)
    - [Design Patterns](#design-patterns)
    - [Inquiry Patterns](#inquiry-patterns)
- [Activities](./activities/README.md)
- [Screen Layouts](#screen-layouts) - What the user will actually see on their screen.
- [xBlocks](./xBlocks)

</details>

# Pathway Patterns
Pathways are organized sets of achievements that usually lead to some sort of credential (e.g. a degree, a certificate). There are several typical patterns that pathways take. 
- [Explorer](./pathways/Explorer.md) - Expose learners to a variety of topics.
- [Deep Dive](./pathways/DeepDive.md) - Increase a learner's proficiency in a single domain.

# Learning Experience Patterns
Modules are the sub-xBlocks of pathways. They could be found at the certificate, course, competency, or sub-competency level. 
## Case Patterns


- [Decision Case](./experiences/cases/DecisionCase.md) <img src="https://img.shields.io/badge/-dev-orange" alt="In Development" />
- [Evaluation Case](./experiences/cases/EvaluationCase.md) <img src="https://img.shields.io/badge/-dev-orange" alt="In Development" />
- [Problem-Diagnosis Case](./experiences/cases/ProblemDiagnosisCase.md) <img src="https://img.shields.io/badge/-dev-orange" alt="In Development" />
- [ ] Outlier
- [ ] Role Play
- [ ] Longitudinal

## Practice Patterns
- [Deliberate Practice](./experiences/practice/DeliberatePractice.md) <img src="https://img.shields.io/badge/-dev-orange" alt="In Development" />
- [ ] Scaffolded Assistance
- [ ] Distributed
- [ ] Variable

## Problem Patterns
- [Well-Structured Problems](./experiences/problems/WellStructuredProblem.md) <img src="https://img.shields.io/badge/-dev-orange" alt="In Development" />
- [Ill-Structured Problems](./experiences/problems/IllStructuredProblem.md) <img src="https://img.shields.io/badge/-dev-orange" alt="In Development" />
## Design Patterns
- [Design Thinking](./experiences/design/DesignThinking.md) <img src="https://img.shields.io/badge/-dev-orange" alt="In Development" />
- [ ] Maker Spaces

## Inquiry Patterns
- [Scientific Method](./experiences/inquiry/ScientificMethod.md) <img src="https://img.shields.io/badge/-dev-orange" alt="In Development" />
- [ ] Socratic Questioning

## Other Patterns
- [Engage, Guide, and Apply](./experiences/other/EngageGuideApply.md)

# Activites
Check out the index of our learning activites [here](./activities/README.md).
# Screen Layouts
- [Article](./layouts/Article.md)
- [Blog](./layouts/Blog.md)
- [Content](./layouts/Content.md)
- [Gallery](./layouts/Gallery.md)
- [Intro](./layouts/Intro.md)
- [Media](./layouts/Media.md)
- [Other](./layouts/Other.md)


- ~~Intro / Outro Sandwich~~ 
- ~~Check For Understanding (CFU)~~ 

# [xBlock xBlocks](./xBlocks/README.md)

# OEX Structure

```mermaid 
graph TD
CC[Course Content]:::CC
SO01[Section Opener]:::SO
LO01[Lesson Opener]:::LO
LO02[Lesson Opener]:::LO
U01[Unit]:::U
U02[Unit]:::U
U03[Unit]:::U
U04[Unit]:::U
LS01[Lesson Summary]:::LS
LS02[Lesson Summary]:::LS
LA01[Lesson Assessment]:::LA
LA02[Lesson Assessment]:::LA
SS01[Section Summary]:::SS
SA01[Section Assessment]:::SA
CC --> SO01
SO01 --> LO01
SO01 --> LO02
LO01 --> U01
LO01 --> U02
LO02 --> U03
LO02 --> U04
U01 --> LS01
U02 --> LS01
U03 --> LS02
U04 --> LS02
LS01 --> LA01
LS02 --> LA02
LA01 --> SS01
LA02 --> SS01
SS01 --> SA01


SO02[Section Opener]:::SO
LO03[Lesson Opener]:::LO
LO04[Lesson Opener]:::LO
U05[Unit]:::U
U06[Unit]:::U
U07[Unit]:::U
U08[Unit]:::U
LS03[Lesson Summary]:::LS
LS04[Lesson Summary]:::LS
LA03[Lesson Assessment]:::LA
LA04[Lesson Assessment]:::LA
SS02[Section Summary]:::SS
SA02[Section Assessment]:::SA
CC --> SO02
SO02 --> LO03
SO02 --> LO04
LO03 --> U05
LO03 --> U06
LO04 --> U07
LO04 --> U08
U05 --> LS03
U06 --> LS03
U07 --> LS04
U08 --> LS04
LS03 --> LA03
LS04 --> LA04
LA03 --> SS02
LA04 --> SS02
SS02 --> SA02

classDef CC fill:#002A4E,color:#ffffff;
classDef SO fill:#7C235E,color:#ffffff;
classDef LO fill:#F78D3A,color:#ffffff;
classDef U fill:#C69214,color:#ffffff;
classDef LS fill:#F78D3A,color:#ffffff;
classDef LA fill:#337DA9,color:#ffffff;
classDef SS fill:#7C235E,color:#ffffff;
classDef SA fill:#337DA9,color:#ffffff;


```

# To Do
- [ ] Add anti-patterns
- [ ] Add resources
- [ ] Add examples
- [ ] Add tools
- [ ] Add videos
- [ ] Add books
- [ ] Add courses
