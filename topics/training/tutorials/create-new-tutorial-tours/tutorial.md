---
layout: tutorial_hands_on
topic_name: training
tutorial_name: create-new-tutorial-tours
---

# Introduction

Galaxy is a great solution to train the bioinformatics concepts:

- numerous bioinformatics tools are available (almost 5,000 in the ToolShed)
- it can be used by people without amy computer science skills
- it trains to use technology, outlining available resources and efforts that have made them accessible to researchers
- it is scalable

In 2016, the Galaxy Training Network decide to set up a new infrastructure for delivering easily Galaxy related training material. The idea was to develop something open and online based on a community effort, as most of the time in Galaxy. 

We take inspiration from [Software Carpentry](https://software-carpentry.org). We collected everything on a GitHub repository: [https://github.com/galaxyproject/training-material](https://github.com/galaxyproject/training-material). We decided a structure based on tutorials with hands-on, fitting both for online self-training but also for workshops, grouped in topics. Each tutorial follows the same structure and comes with a technical support to be able to run. 

In this tutorial, you will understand how to design and develop a new tutorial fitting in this training material repository. As doing helps to understand, we will develop a small tutorial to explain BLAST with the full infrastructure to be able to run this tutorial anywhere. 

> ### Agenda
>
> In this tutorial, we will deal with:
>
> 1. [Setting up a new tutorial](#setting-up-a-new-tutorial)
> 2. [Filling the metadata](#filling-the-metadata)
> 3. [Checking the tutorial generation](#checking-the-tutorial-generation)
> 5. [Filling the tutorial content](#filling-the-tutorial-content)
> 6. [Adding slides](#adding-slides)
> 7. [Setting up the technical support](#setting-up-the-technical-support)
> 8. [Submitting the new tutorial to the GitHub repository](#submitting-the-new-tutorial-to-the-github-repository)
> {: .agenda}

# Creating a Galaxy Interactive Tour

A Galaxy Interactive Tour is a way to go through an entire analysis, step by step inside Galaxy in an interactive and explorative way. It is a great pedogogic way to run the tutorial directly inside Galaxy

> ### :pencil2: Hands-on: Create a Galaxy Interactive Tour
>
> 1. Create a Galaxy Interactive Tour for the tutorial
> 2. Add it to the `tours` directory
{: .hands_on}