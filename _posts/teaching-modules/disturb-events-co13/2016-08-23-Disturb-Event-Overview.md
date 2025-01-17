---
layout: post
title: "Overview: Quantifying The Drivers and Impacts of Natural Disturbance Events – The 2013 Colorado Floods"
date: 2016-04-10
authors: [Leah A. Wasser, Megan A. Jones]
dateCreated: 2015-12-05
lastModified: 2016-11-10
categories: [teaching-modules]
tags: [R, time-series]
mainTag: disturb-events-co13
scienceThemes: [disturbance]
packagesLibraries: [ggplot2, plotly]
description: "This lesson demonstrates ways that scientists identify and use 
data that they use to study disturbance events. Further, it encourages students 
to think about why we need to quantify change and different types of data 
needed to quantify the change. This lesson focuses on flooding as a natural 
disturbance event with impacts on the local human populations. Specifically, it 
focuses on the causes and impacts of flooding that occurred in 2013 throughout 
Colorado with an emphasis on Boulder County." 
code1:
image:
  feature: teachingModule.jpg
  credit: A National Ecological Observatory Network (NEON) - Teaching Module
  creditlink: http://www.neonscience.org
permalink: /teaching-modules/disturb-events-co13/
comments: false
---

{% include _toc.html %}



**Estimated Duration:** 75 minutes (with suggestions for shorter or longer duration)

**Themes:** Ecological Disturbance

**Audience:** Undergraduate courses

**Class size:** Any (adapt the Q&A/Discussion questions to small group
discussions or instructor-led introductions as needed)

**Technology Needed**

* Instructor
    + Internet access: if presenting, live from the website or accessing videos.
    + Computer & projector
    + Optional: audio capabilities for videos
* Student:
    + Optional: Computer/device with internet access 

**Materials Needed**

None


## Lesson Overview for Instructors 
This lesson demonstrates ways that society and scientists identify and use data 
to understand disturbance events by focusing on the 2013 Boulder County, Colorado
flooding events. Further, it encourages students to think about 
why we need to quantify change and the different types of data needed to quantify 
landscape change after a disturbance event. 

This lesson focuses on flooding as a natural disturbance event with impacts on 
humans. While the drivers and impacts of flooding extend beyond the metrics used
in this lesson, we use subsets of these datasets to elicit discussion 
surrounding how we can study flooding and how the event impacts humans: 

* Palmer Drought Index: <a href="http://www7.ncdc.noaa.gov/CDO/CDODivisionalSelect.jsp" target="_blank"> NOAA's Climate Divisional Database (nCLIMDIV)</a>
* Precipitation: <a href="http://www.ncdc.noaa.gov/cdo-web/search" target="_blank"> National Climatic Data Center-NOAA </a>
* Stream Discharge: <a href="http://waterdata.usgs.gov/nwis" target="_blank"> USGS stream gauges </a>
* Before/After Terrain Data: <a href="http://www.neonscience.org/science-design/collection-methods/airborne-remote-sensing" target="_blank"> NEON AOP LiDAR-derived Elevation Models </a>
* Before/After Imagery: various sources, each image has source information 

The teaching data subsets can be found on and downloaded from the 
<a href="https://figshare.com/s/dc58120c46959d4116c3" target="_blank">
NEON Data Skills account on FigShare</a>. 


## Lesson Components

* <a href="{{ site.baseurl}}/teaching-modules/disturb-events-co13/detailed-lesson" target="_blank"> Detailed Lesson Page
* Data Activities in R Lessons (additional time required)
    + <a href="{{ site.baseurl }}/R/nCLIMDIV-Palmer-Drought-Data-R" target="_blank"> Palmer Drought Severity Index Data </a>
    +  <a href="{{ site.baseurl }}/R/COOP-precip-data-R" target="_blank">Precipitation Data</a>
    + <a href="{{ site.baseurl }}/R/USGS-Stream-Discharge-Data-R" target="_blank"> Stream Gauge Data</a> 
    + <a href="{{ site.baseurl }}/R/NEON-lidar-flood-CO13" target="_blank"> LiDAR Data</a>
    + <a href="{{ site.baseurl }}/R/Plotly" target="_blank"> Data Visualization with Plotly</a> - 
    This lesson is supplemental to the other Data Activities and explains how to use the Plotly R package to create & share interactive plots.


## Lesson Goals 
This lesson focuses on how data can be used to quantify the drivers and impacts
of natural disturbance events and why the quantification is important to for
society’s understanding of, forecasting of, and recovery from disturbance events. 

### Science Objectives
After the lesson, students will be able to: 

* Explain how and why data are needed to support scientific inquiry.
* Summarize how data can be collected and used to quantify a flood event, 
including precipitation and stream gauges and lidar .
* Organize the various drivers and impacts of disturbance events to show 
causation. 
* Diagram relationships between different variables (drivers and impacts) and 
how they influence disturbance events.
* Describe how disturbance events can impact society. 
* Contrast how different types of data can be used to quantify changes in terrain. 
* Summarize what lidar data are and several ways the data can be used.
* Explain the concept of a “100-year event” and why we might have two 100-year floods five years apart.
* Define: disturbance event, LiDAR, stream discharge (including CFS – cubic feet per second), and floodplain. 

### Data Skills Objectives
See optional R based Data Activities for individual data skills objectives.

## Data & Coding Extensions
All data used in this activity are freely available (<a href="https://figshare.com/s/dc58120c46959d4116c3" target="_blank">
NEON Data Skills account on FigShare</a>). 

The code for data manipulation and creation of the visuals is available at the 
end of each lesson. Throughout each lesson these activities are listed as 
Optional Data Activity. This could be used in the classroom, in a lab, or an 
out-of-classroom setting for students already familiar with basic coding and 
working with data (e.g. graduate students in a cross-listed course). 

## Suggestions for Presenting Lesson
The detailed lesson page can be used directly to teach from, for students to 
follow along with the instructor, or to serve as a reference for students before 
or after the class. 

Instructors may also choose to download text, figures, graphics or video from 
this site and present the lesson in the medium of their choice. 

## Teaching Modules Collection
This lesson plan is part of larger collection of lessons utilizing data 
collected during the 2013 Colorado Floods that are designed for undergraduate 
and graduate students. All lessons and related materials can be found on the 
<a href="http://www.neondataskills.org/" target="_blank"> NEON Data Skills portal</a>.

## Use of NEON Teaching Modules 
All lessons developed by the National Ecological Observatory Network are 
open-access (CC-BY) and designed as a resource for the greater community. 
General feedback on the lesson is welcomed in the comments section <Link> for 
each lesson page. If you develop additional materials related to or supporting 
this lesson, and are willing to share them, we provide the opportunity for you 
to share them with other instructors. Please contact
<a href="mailto:neondataskills@BattelleEcology.org?subject=Comment%20RE%3A%20Teaching%20Module">NEON Data Skills</a> 
or, if familiar with GitHub, submit a pull request with the materials to the 
lesson’s repo (available from the lesson’s webpage). All materials will be
reviewed by NEON staff prior to inclusion or linking to from the NEON Data 
Skills portal. 
