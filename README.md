---
nav_order: 1
permalink: /
---

# Structured Rapid Development

`Design Patterns to Streamline Learning Design and Development.`

WGU's vision is to be the world's most innovative, student-centric university. Structured Rapid Development uses these design patterns to streamline the learning product design and development.

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

## Pathway Patterns

Pathways are organized sets of achievements that usually lead to some sort of credential (e.g. a degree, a certificate). There are several typical patterns that pathways take.

- Associate Pathways
- Bachelor Pathways
- Master Pathways
- Professional Pathways

## Learning Experience Patterns

Modules are the sub-xBlocks of pathways. They could be found at the certificate, course, competency, or sub-competency level.

### Case Patterns

- [Decision Case](./experiences/cases/DecisionCase.md)
- [Evaluation Case](./experiences/cases/EvaluationCase.md)
- [Problem-Diagnosis Case](./experiences/cases/ProblemDiagnosisCase.md)
- Outlier
- Role Play
- Longitudinal

### Practice Patterns

- [Deliberate Practice](./experiences/practice/DeliberatePractice.md)
- Scaffolded Assistance
- Distributed
- Variable

### Problem Patterns

- [Well-Structured Problems](./experiences/problems/WellStructuredProblem.md)
- [Ill-Structured Problems](./experiences/problems/IllStructuredProblem.md)

### Design Patterns

- [Design Thinking](./experiences/design/DesignThinking.md)
- Maker Spaces

### Inquiry Patterns

- [Scientific Method](./experiences/inquiry/ScientificMethod.md)
- Socratic Questioning

### Other Patterns

- [Engage, Guide, and Apply](./experiences/other/EngageGuideApply.md)

## Activities

- [A-Z Index](./activities/Alphabetically.md)
- [By School](./activities/School.md)
- [By Modality](./activities/Modality.md)
- [By Topic](./activities/Topics.md)

## Layouts

- [Article](./layouts/Article.md)
- [Blog](./layouts/Blog.md)
- [Content](./layouts/Content.md)
- [Gallery](./layouts/Gallery.md)
- [Intro](./layouts/Intro.md)
- [Media](./layouts/Media.md)
- [Other](./layouts/Other.md)

## [xBlocks](./xBlocks/README.md)

## OEX Structure

<div class="mermaid">
graph TD;
CC[Course Content]:::CC;
SO01[Section Opener]:::SO;
LO01[Lesson Opener]:::LO;
LO02[Lesson Opener]:::LO;
U01[Unit]:::U;
U02[Unit]:::U;
U03[Unit]:::U;
U04[Unit]:::U;
LS01[Lesson Summary]:::LS;
LS02[Lesson Summary]:::LS;
LA01[Lesson Assessment]:::LA;
LA02[Lesson Assessment]:::LA;
SS01[Section Summary]:::SS;
SA01[Section Assessment]:::SA;
CC --> SO01;
SO01 --> LO01;
SO01 --> LO02;
LO01 --> U01;
LO01 --> U02;
LO02 --> U03;
LO02 --> U04;
U01 --> LS01;
U02 --> LS01;
U03 --> LS02;
U04 --> LS02;
LS01 --> LA01;
LS02 --> LA02;
LA01 --> SS01;
LA02 --> SS01;
SS01 --> SA01;
SO02[Section Opener]:::SO;
LO03[Lesson Opener]:::LO;
LO04[Lesson Opener]:::LO;
U05[Unit]:::U;
U06[Unit]:::U;
U07[Unit]:::U;
U08[Unit]:::U;
LS03[Lesson Summary]:::LS;
LS04[Lesson Summary]:::LS;
LA03[Lesson Assessment]:::LA;
LA04[Lesson Assessment]:::LA;
SS02[Section Summary]:::SS;
SA02[Section Assessment]:::SA;
CC --> SO02;
SO02 --> LO03;
SO02 --> LO04;
LO03 --> U05;
LO03 --> U06;
LO04 --> U07;
LO04 --> U08;
U05 --> LS03;
U06 --> LS03;
U07 --> LS04;
U08 --> LS04;
LS03 --> LA03;
LS04 --> LA04;
LA03 --> SS02;
LA04 --> SS02;
SS02 --> SA02;
</div>
