# An Introduction to Earth and Environmental Data Science

**About This Adapted Resource**

The foundation of this educational resource is the excellent open-source textbook *An Introduction to Earth and Environmental Data Science*, created by Ryan Abernathey, Kerry Key, Tim Crone, Julius Busecke, and the broader community that contributed to it. Their original work provides a valuable starting point for learning Python in the Earth Sciences, and we encourage you to visit the original project at: https://earth-env-data-science.github.io/

We have adapted the original textbook as a resource for high school educators, aiming to introduce the fundamentals of weather data science and provide practical guidance on running the Weather Research and Forecasting (WRF) model. Our modifications primarily include:

* **Removed Lessons:** Certain sections from the original text that were less relevant to our focus have been omitted.
* **Added Lessons:** New content and examples have been added ex. working with WRF model output, specific Python libraries for atmospheric science.

The goal of this adaptation is to provide a tailored learning experience while acknowledging the significant contribution of the original authors. The original history and motivation section follows.



**All content derived from the original and added in this adapted version is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0) license](https://creativecommons.org/licenses/by-sa/4.0/).** 

---

## History

This book grew out of a course developed at Columbia University called _Research Computing in Earth Science_.
It was written mostly by [Ryan Abernathey](https://rabernat.github.io), with significant contributions from
[Kerry Key](https://emlab.ldeo.columbia.edu/index.php/team/kerry-key/), 
[Tim Crone](https://github.com/tjcrone), and [Julius Busecke](https:www.juliusbusecke.com).
By separating the book from the class, we hope to create an open-source community resource for Python education
in the Earth and Environmental Sciences.

## Motivation and Scope

Computing has become an indispensable tool for nearly all Earth and Environmental Scientists, but it doesn't often appear in our curriculums.
This book focuses on _data analysis_, a subset of computing in which the data already exist, e.g.from observations or from the output of a simulation, but have to be transformed into understanding.
There are many different ways to gain understanding, but most workflows often boil down to:

- read data files
- perform some analysis operations, from very simple (e.g. take the mean) to very complex (e.g. train a deep neural network)
- visualize the output in a plot

This book doesn't attempt to teach deep learning; its goal is to teach the basic foundations of Earth and Environmental Data Science which are often overlooked.
The material is designed to be accessible for Earth Science graduate students in any discipline, with no prerequisites.

This book is intended to introduce new graduate students to modern computing software, programming tools and best practices that are broadly applicable to the analysis and visualization of Earth and Environmental data.
This includes an introduction to Unix, version control, and basic programming in the open-source Python language.
The bulk of the content is devoted to in-depth exploration of the numerical analysis and visualization packages which comprise the modern Scientific Python ecosystem, including Numpy, Scipy, Matplotlib, Pandas, Xarray, using real Earth and Environmental datasets.

## Learning Goals

After completing all of the material, students should have the ability to:

- Use unix commands to work with files and directories
- Navigate the JupyterHub Environment effectively
- Identify common geoscience data formats and the python packages which can load them
- Perform basic exploratory data analysis on Earth and Environmental data, distinguishing between
  - _Tabular data_: rows and columns
  - _Gridded data_: multidimensional numerical arrays
- Use visualization to enhance interpretation of data, including maps and interactive visualizations
- Construct complete, well-structured programs in Python
- Practice reproducible research through version control and binder

## Recommended Course Structure

This course material can be used however you want.
However, it was developed for a full-credit, semester-long course that meets twice a week.
The idea is to complete one lecture and one homework assignment per week.
One of the weekly meetings consists of a lecture in which the instructor presents the week's lecture, with students typing along.
The other should be used as "collaborative time," during which the students work on their assignments, ask questions, and interact with their peers.
A final project is an important capstone experience for a semester-long course.
