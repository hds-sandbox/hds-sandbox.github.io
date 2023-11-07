---
layout: page
title: News
permalink: /news/
nav_order: 2
hide:
  - navigation
  - footer
---

<center>
# News and Events
</center>

Sandbox data scientists routinely lead or contribute to courses and workshops at host universities in Denmark. Check out upcoming events in the table below!

<h3 align="center" style="margin:0px"> Upcoming Sandbox Training Events</h3>

{{ read_csv('../assets/upcomingcourses.csv') }}

---

<h3 align="center" style="margin:0px"> News & Updates</h3>

#### 9/11/2023 - Updated Proteomics Sandbox App supporting of a Biostatistics course at SDU
The Proteomics Sandbox Application has recently undergone a significant update, enhancing its security features to ensure safer usage for its users. In this latest iteration, Sandbox data scientist Jacob Fredegaard Hansen has expanded the app's software suite by introducing two new tools: DIA-NN and MZmine, catering to the metabolomics field. Furthermore, the pre-existing software within the application has been refreshed and updated to the latest versions, ensuring that the Proteomics Sandbox Application remains at the cutting-edge of the field. Excitingly, this application will be actively utilized in the course "BMB831: Biostatistics in R II" at the University of Southern Denmark throughout this autumn, showcasing its relevance and applicability in academic settings.

#### 25/10/2023 - 'Research Data Management for NGS Data' with DeiC (Technical University of Denmark)
Sandbox data scientist Jose Alejandro Romero Herrera ran the first instance of a new module on research data management practices he developed specifically for NGS data. Twelve participants were hosted in conjunction with DeiC at DTU, and were exposed to tools like bash, conda, git, and cookie cutter in their quest to organize their omics data.

#### 07/09/2023 - 'Digging into the Health Data Science Sandbox' at the Danish Bioinformatics Conference 2023 (Aarhus University)
The full team of Sandbox data scientists hosted a 4 hour workshop at the Danish Bioinformatics conference where they gave a taster session of each of our 3 omics apps. We learned that multi-omics analysis were a substantial draw for the crowd at the DBC and are making plans to address this interest in future events.

#### 29/08/2023 - 3 days of Sandbox demos at Aarhus University
Sandbox data scientist Samuele Soraggi hosted a three day speed run through Sandbox apps at the Bioinformatics Research Center. The 26 participants joined for genomics, transcriptomics, and/or proteomics app demos depending on their interests. This thorough omics demo had maxed out participant sign-ups and an enthusiastic crew enjoyed the sessions alongside a bit of networking across disciplines. We plan to host more of these type of workshops given the event's success!

#### 19/06/2023 - 3 days of bulk RNA-seq at the University of Copenhagen
Our teaching team (from the Sandbox, the HeaDS DataLab, and reNEW's genomics platform) hosted another 3 day workshop on bulk RNA-seq. The 34 participants used the updated version of the UCloud Transcriptomics App which provided the smoothest experience yet for both trainers and trainees. A new goal for the next course run is to add a student project to support independent implementation and exploration of the course content.

#### 31/05/2023 - Sandbox App updates on UCloud rolled out
New versions of the Genomics Sandbox App, the Transcriptomics Sandbox App, and the Proteomics Sandbox App have all been launched on UCloud this month! Check out the new components in the training modules such as a GWAS module in Genomics and new tools in Transcriptomics and Proteomics. Updates were also informed by the different courses supported during Spring 2023. With these courses wrapping up this month, the associated new training materials have also been included in the new versions of the apps.

#### 18/01/2023 - Second bulk RNA-seq course at the University of Copenhagen

On 18th of January we taught the second iteration of our bulk RNA-seq course to researchers (from PhD students to professors) at SUND at the University of Copenhagen. We had ~50 workshop participants joining us for three days of lectures and exercises on UCloud. This time, we introduced preprocessing theory (read QC, alignment and quantification) and the use of automated workflows using the [nf-core rnaseq pipeline](https://nf-co.re/rnaseq).

For those that could not enroll for this session, you can find the updated material [here](https://hds-sandbox.github.io/bulk_RNAseq_course/). We have moved the datasets and slides to a [zenodo repository](https://zenodo.org/record/7565997)

We'd like to extend our thanks to our workshop collaborators, data scientists from the SUND DataLab at KU's Center for Health Data Science as well as the genomics platform at the NNF Center for Stem Cell Medicine (reNEW). 


#### 10/01/2023 - Sandbox support for Spring 2023 courses

##### Sandbox support for 'Population Genomics'

Exercises for an [MS course on Population Genomics](https://kursuskatalog.au.dk/en/course/117821/Population-Genomics) taught by Prof. Kasper Munch at Aarhus University are being implemented on UCloud by Sandbox data scientist Samuele Soraggi. Students will explore the training materials on UCloud during the Spring 2023 semester, after which the materials will be accessible to any UCloud user via the Genomics Sandbox App.  

##### 'Fra real-world data til personlig medicin' with Course Platform & Sandbox support
The second round of the course ['Fra real-world data til personlig medicin'](https://personligmedicin.ku.dk/kursus/realworld/) in KU's MS in Personlig Medicin begins in January with an introduction to CLL-TIM, a predictive model for chronic lymphocytic leukemia deployed by Prof. Carsten Niemann, an introduction by Sandbox coordinator Jennifer Bartell to the new Course Platform at Computerome built with Sandbox help for hosting courses with HPC resources, and an introduction to building predictive models using TidyModels in R by Prof. Rasmus Broendum. The course will run through April with 10 continuing education students building their own predictive models using a new and improved synthetic CLL dataset developed by Sandbox data scientist Sander Boisen Valentin. Jennifer and Rasmus are also manning the Sandbox Slack workspace to field student questions about the dataset and their model building.

##### Sandbox support for 'Single-cell, Single-Molecule: The Next Level in Cell Biology'
An NNF-funded course, ['Single-cell, Single-Molecule: The Next Level in Cell Biology'](https://kursuskatalog.au.dk/en/course/118020/Single-cell-Single-molecule-The-Next-Level-in-Cell-Biology) combining experimental and computational approaches to RNA sequencing is starting at Aarhus University. In addition to course-responsible professor Stig Andersen and co-teachers Victoria Birkedal and Thomas Boesen, Sandbox PI Mikkel Schierup will be contributing along with Sandbox data scientist Samuele Soraggi. Samuele is adapting the Transcriptomics App material on UCloud to supply tutorials and exercises for this hefty course as well as serving as a teaching assistant. The course materials will be available to all users of the Transcriptomics Sandbox App on UCloud in the future.

#### 8/01/2023 - Soft launch of the new Course Platform at Computerome
Sandbox data scientist Jesper Roy Christiansen has been integral to the development of a new ['Course Platform'](https://www.computerome.dk/solutions/course-platform) at Computerome, the HPC platform at the Technical University of Denmark. Built as a collaboration between the Sandbox and Computerome, the Course Platform will host its first users, students in 'Fra real-world data til personlig medicin', a course of KU's MS in Personlig Medicin. Sandbox coordinator Jennifer Bartell and Sandbox PI Martin Boegsted have also been involved in testing this new system during course setup. See the above link as well as [HPC Access](https://hds-sandbox.github.io/access) for more details on this platform and how you can also use this new platform to host courses (with or without Sandbox involvement!).
  

#### 30/11/2022 - Sandbox support for 'Advanced Statistical Learning'
Sandbox data scientist Samuele Soraggi spent two weeks teaching for the Fall 2023 course ['Advanced Statistical Learning'](https://kursuskatalog.au.dk/da/course/115396/Advanced-Statistical-Learning) taught by Prof. Asger Hobolth at Aarhus University.


#### 15/11/2022 - Sandbox support for a workshop in the series 'Workshops in Applied Bioinformatics' at SDU
Sandbox data scientist Jacob Fredegaard Hansen created a tutorial on how to use ColabFold for a one day workshop as part of the ['Workshops in Applied Bioinformatics'](https://odin.sdu.dk/sitecore/index.php?a=searchfagbesk&internkode=bmb209&lang=en) series taught by Sandbox collaborator Veit Schwammle. The material is accessible on the Sandbox website (see [Modules](https://hds-sandbox.github.io/modules/), Proteomics) for any UCloud user alongside the UCloud ColabFold App.


#### 10/12/2022 - Transcriptomics Sandbox app launched on UCloud!

We have deployed our second standalone Sandbox app on UCloud! Please see the [Access](https://hds-sandbox.github.io/access/UCloud) page for instructions on how to find our Sandbox apps on UCloud - This one is titled 'Transcriptomics Sandbox' and module documentation is linked from the UCloud app page as well as here in [Modules](https://hds-sandbox.github.io/modules).


#### 06/09/2022 - Genomics Sandbox app launched on UCloud!

We have deployed our first standalone Sandbox app on UCloud! Please see the [Access](https://hds-sandbox.github.io/access/UCloud) page for instructions on how to find our Sandbox apps on UCloud - this first one is titled 'Genomics Sandbox' and module documentation is linked from the UCloud app page as well as here in [Modules](https://hds-sandbox.github.io/modules).

#### 18/08/2022 - Bulk RNA-seq course at University of Copenhagen

Today we began teaching our brand new bulk RNA-seq course to researchers (from PhD students to professors) at SUND at the University of Copenhagen. We had 32 workshop participants join us for two days of lectures and exercises on UCloud. We'd like to extend our thanks to our workshop collaborators, data scientists from the SUND DataLab at KU's Center for Health Data Science as well as the genomics platform at the NNF Center for Stem Cell Medicine (reNEW). 

For those that could not enroll for this session, you can find the relevant material [here](https://hds-sandbox.github.io/bulk_RNAseq_course/).

#### 01/06/2022 - Genomics course at Aarhus University

A month-long course in Genomics taught by Professors Mikkel Schierup and Stig Andersen has started with lead supercomputing support on UCloud by Sandbox data scientist and course instructor Samuele Soraggi. Computational exercises in NGS analysis were deployed in a UCloud project for use by 47 graduate students with primarily molecular biology and clinical backgrounds and no prior supercomputing experience! Post-course update: We received many positive reviews on use of the Genomics Sandbox training materials on UCloud! 

#### 22/04/2022 - Basics of Personalized Medicine - final wrap-up

Our first course, Basics of Personalized Medicine, wrapped up this month with student project presentations which described their approaches to analysis of the synthetic Chronic Lymphocytic Leukemia dataset created for the course. Course reviews highlighted the helpfulness of Sandbox staff in troubleshooting R problems and the tremendous amount that students learned about predictive modeling.

#### 04/01/2022 - Basics of Personalized Medicine - MS in Personal Medicine program

The first course supported by the Sandbox is launching this month - 'Basics of Personalized Medicine' - where students in the new Master in Personal Medicine program at University of Copenhagen are introduced to predictive modeling using electronic health records.
