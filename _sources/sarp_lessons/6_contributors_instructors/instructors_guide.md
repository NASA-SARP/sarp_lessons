# Instructor’s Guide - _Programming for Earth Science Researchers_

## Overview

The goal of this content is to teach Python programming for the purpose of earth science research in a fast-paced manner that gives a solid footing in foundational concepts. Most lessons are designed to be taught in approximately 60-75 minutes, and suggested progressions below show two 10 lesson sequences.

The content can be stand alone, but is most effective when used in conjunction with a hands-on application of coding skills. At NASA SARP that application is a 6-week independent research project. Any authentic hands-on experience, such as class projects or personal projects, would also provide that application element.

This website serves as an online textbook. It is made up of Jupyter notebooks, all of which are downloadable through the website (top right corner of each page), or directly through the associated github repository https://github.com/NASA-SARP/sarp_lessons. There are over 16 lessons on the website, many of which have associated exercises with answers.

## Core Instructional Concepts

### 1 - Teach Syntax, Build more Component Programmers

This content does not introduce a plethora of Python functions. It instead focuses on a smaller set of objects and methods, using them as a demonstration of how programming languages work. This focus on using syntax to build a mental model for programming is what gives students the understanding to become independent programmers that can discover and learn new methods and functions on their own, even after the lessons are complete.

### 2 - Data Structures First

This content is centered on the idea that two pieces of information form the basis of the relationship between coding and scientific research:
1. Python is organized into data structures
2. Data structures represent scientific data

These ideas are planted in the first two days of content. These two lessons focus on fairly introductory Python concepts (data types, Lists, and Dictionaries). However, the big ideas of those two lessons are that Lists and Dictionaries are data structures and that different types of data make more sense as a List vs. a Dictionary. In this way a mental model for data structures is built from the beginning.

While most earth science programmers with Python experience have seen List and Dictionaries before, few have considered the organization of Python into data structures. Past instructors at SARP have received positive feedback from more experienced programmers that this framework was helpful for them to deepen their Python knowledge, even though they had already seen the content before.

### 3 - Computational Skills alongside Coding Languages

A scientific Python programmer can only get so far if they cannot debug their code or write a filepath. Debugging in particular is often a skill that is too often assumed students will gain automatically. Poor debugging skills are a common reason students at SARP get discouraged and quit programming. For this reason, a set of lessons on important computational skills is provided, with the intention that they are integrated into Python lessons. The Example Lesson Progressions section below provides a few examples of how this could be done.

## Mix and Match Lesson Guide

The website content is broken into three sections:
1. Core Python Progression
2. Computational Skills
3. Open Science Tools

The primary material on this website is about teaching Python, but that material has a limit if additional computational skills are not taught as well.

The suggested method for teaching is to first build a Python progression that fits your students, then choose complementary computational or open science skills learning objectives to complement the Python progression. This modularity allows different instructors to build a progression that matches their teaching style and the learning needs of their students. Several example progressions are shown below.

## Example Lesson Progressions

The example progressions here are organized by the data type that a student would be primarily working with. No matter the data type, however, both tracks start with two hours of Python building blocks. These first two days are typically important for both novice and skilled programmers, as they set up the mindset of viewing Python as a set of data structures which represent their data. The two lessons can move faster for more advanced programmers (ex. perhaps combining them into one lesson), but are still important for setting up their mental framework for programming.

### Example 1 - Tabular Data Track

<!-- Testing a simple link. See {doc}`here <./env_setup>` for more information.

Also trying this syntax See {doc}`./env_setup` for more information.

Trying again but in another folder See {doc}`../1_python_progression/1-general_python/index` for more information.

Now testing a notebook. See {doc}`../1_python_progression/1-general_python/1-1_variables_types_ifstatements` for more information. -->



### Example 2 - Gridded Data Track

### Example 3 - Combined Tabular & Gridded Track

Past instructors have taught both the tabular and gridded data tracks to their students. If doing this, the suggestion is:
1. Teach tabular data first, as the pandas DataFrame is typically easier to grasp than an xarray DataSet
2. Build competency in one data structure first, then move to a second one. Mixing the two can be more confusing for student that aren’t familiar with either construct.
