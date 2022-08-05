---
layout: default
title: DREAM Project Site
---

* TOC
{:toc}

## About Me

Hi, I’m Kate, a graduate student in CS, focusing on Machine Learning. This summer, I’m researching Explainable AI methods for Natural Language Processing. I’m interested in what and how models encode information into their hidden representations. In my free time, I like to walk my dog around Pike Place Market and read books with my philosophy club.

## About My Advisor

# Bruce Maxwell, Ph.D

I was a professor and chair of the CS Department at Colby College from 2013 until 2020. I then started up the Khoury College MS CS and MS CS Align Programs at the Roux Institute in Portland, ME from 2020-2022 before moving to the Northeastern Seattle Campus as Teaching Professor and Assistant Director of Computing Programs. I'm continuing to work with the MS CS Align Program at Northeastern, and bridge program for students without an undergraduate CS degree to become computer scientists and software engineers.

My teaching and research interests include Computer Vision, Robotics, Computer Graphics, Game Design, and Data Analysis and Visualization. I worked with the the Maine Concussion Management Initiative [MCMI] from 2010-2020 helping develop tools for analyzing and monitoring concussions in high school and college athletes as well as using measurements of balance to quickly identify potential concussions.

Outside of the classroom and lab I enjoy music (violin and viola), swimming, running, biking, hiking, birding, carpentry, and gardening.

## About My Project

In recent years, the development of Big Language Models — a collection of pre-trained Transformer models used for transfer learning — has led to increased performance on many natural language processing benchmarks. Interestingly, though, how these models learn patterns in the data — what information about language they encode into hidden representations — is largely unknown.

To explore the hidden representations, researchers have developed probing classifiers, which are simple diagnostic models trained on an LM’s hidden representations. These probes achieve high accuracy on simple classifications, such as identifying part of speech or syntactic dependency. Researchers have believed that this high accuracy indicates the LMs actually encode this linguistic information in the hidden representations, but recently others have raised the question: when using this method to explain NLP models, how do we know that LMs encode this information and not that the probing classifier memorizes it?

To investigate this question, I intend to run probing experiments similar to those above, but with an additional step in the process: before training the probe, I will use a linear classifier to isolate the vector of dimensions encoding linguistic information e.g. “noun-ness.” I will then project out this vector from the hidden representation. I hypothesize that the probe will no longer achieve high accuracy after removing this information, confirming that probes correctly analyze linguistic information encoded by LMs.


[My Final Report](files/finalreport.pdf)

## My Blog

[My Blog](blog.html)
