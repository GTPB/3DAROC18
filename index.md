---
layout: page
title: 3DAROC18
tagline: 3C-based data analysis and 3D reconstruction of chromatin folding
description: 3C-Data Analysis and 3D Chromatin Folding
---

![](IMAGE)

## Course Description

3C-based methods, such as Hi-C, produce a huge amount of raw data as pairs of DNA reads that are spatially close in the cell nucleus. Overall, these interaction matrices have been used to study how the genome folds within the nucleus, that is one of the most fascinating problems in modern biology. The rigorous analysis of the paired-reads using computational tools has been essential to fully exploit the experimental technique, and to study how the genome is folded in the space. Currently, there is a huge expansion on the wealth of data on genome structure with the availability of many datasets of Hi-C experiments down to 1 kb resolution (see for example: [Hi-C Data Browser](http://hic.umassmed.edu/welcome/welcome.php); [3D Genome Browser](http://promoter.bx.psu.edu/hi-c/view.php) or [Aiden Lab](http://www.aidenlab.org/data.html)). In this course, participants will learn to use TADbit, a software designed and developed to manage all the dimensionalities of the Hi-C data:

 - 1D - Map paired-end sequences to generate Hi-C interaction matrices
 - 2D - Normalize matrices and identify constitutive domains (compartments, TADs)
 - 3D - Generate populations of model structures which reproduce the Hi-C interaction matrices
 - 4D - Compare samples at different time points

Participants can bring specific biological questions and/or their own 3C data to analyze during the course. At the end of the course, participants will be familiar with the TADbit software, and will be able to fully analyze Hi-C data. 
*__Note__: Although the TADbit software is central in this course, alternative software will be discussed for each part of the analysis.*

## Target Audience

The course is designed for experimental researchers and bioinformaticians at the graduate and post-graduate levels which are interested in studying the genome spatial organization. 

It is likely that the participants to this course aim at getting involved in generating Hi-C data for  chromosome structure determination, or that they just want to be able to correctly interpret and analyse publicly available data.

## Detailed Program

### Day 1

<table style="width:100%">
  <tbody>
    <tr style="padding: 25px">
      <th>Lectures (pdf)</th>
      <th>Core pipeline (notebooks)</th>
      <th>Annex (notebooks)</th>
    </tr>
    <tr>
     <td>
       <ul>
        <li> <a href="/Presentations/Day1/01_20180917_Welcome.pdf">Welcome</a></li>
        <li> <a href="/Presentations/Day1/02_20180917_introduction_to_structure_determination.pdf">Intro structure determination</a></li>
        <li> <a href="/Presentations/Day1/03_20180917_3D-genomes_overview.pdf">3D Genomes overview</a></li>
        <li> <a href="/Presentations/Day1/04_20180917_Intro_TADbit.pdf">Intro TADbit</a></li>
        <li> <a href="/Presentations/Day1/05_20180917_NGS_for_HiC.pdf">NGS for HiC</a></li>
        <li> <a href="/Presentations/Day1/06_20180917_linux.pdf">Intro UNIX</a></li>
        <li> <a href="/Presentations/Day1/07_20180917_python.pdf">Intro Python</a></li>
       </ul>
     </td>
     <td>
       <ul>
        <li> <a href="/Notebooks/00-Hi-C%20quality%20check.ipynb">Hi-C Quality check</a></li>
        <li> <a href="/Notebooks/01-Mapping.ipynb">Mapping</a></li>
        <li> <a href="/Notebooks/02-Parsing%20mapped%20reads.ipynb">Parsing mapped reads</a></li>
       </ul>
    </td>
    <td>
       <ul>
        <li> <a href="/Notebooks/A0-Preparing%20your%20computer%20for%20HiC%20data%20analysis.ipynb">Software installation</a></li>
        <li> <a href="/Notebooks/A1-Preparation%20reference%20genome.ipynb">Prepare reference genome</a></li>
        <li> <a href="/Notebooks/A2-Download%20published%20Hi-C%20experiments.ipynb">Download Hi-C experiment</a></li>
       </ul>
    </td>
   </tr>
  </tbody>
</table>


---

### Learning objectives

### Instructors
---

The source for this course webpage is [on github](https://github.com/GTPB/Web_course_template).
