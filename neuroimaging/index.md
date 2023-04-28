---
title: Neuroimaging
nav:
  order: 4
  tooltip: About neuroimaging 
---

# {% include icon.html icon="fa-solid fa-brain" %}Neuroimaging and Data Science
{:.center}

{%
  include button.html
  link="neuroimaging/#neuroimaging-tools"
  text="Neuroimaging Tools"
  icon="fas fa-gear"
  flip=true
%}

{%
  include button.html
  link="neuroimaging/#data-science"
  text="Data Science"
  icon="fas fa-table"
  flip=true
%}

# Neuroimaging tools
A number of remarkable tools exist to measure and localize the activity of the brain non-invasively. These tools form the primary basis of the field of cognitive neuroscience, which is dedicated to understanding the relationships between cognition and brain activity. NCIL lab director Aaron Newman has published a book that provides and overview of these techniques, [*Research Methods for Cognitive Neuroscience*](https://us.sagepub.com/en-us/nam/research-methods-for-cognitive-neuroscience/book242924), as well as the Dalhousie University course NESC/PSYO 3137. On this page we provide a bit more information on the two techniques we use most in NCIL, and which lab members are most likely to gain experience with.

## Electroencephalography (EEG)
EEG is a technique used for recording ‘brain waves’, or more technically the electrical activity produced by the brain. EEG achieves this by using electrodes that are placed on the scalp, and recording the summed electrical signals the brain produces to operate. NCIL has two state-of-the-art EEG systems available for research use, each with up to 64 electrodes. The majority of projects in NCIL use EEG, and this is what most trainees get access to. Our lab manager, Dr. Cindy Hamon-Hill, runs EEG training sessions at the start of every term to help onboard new lab members. 

{% capture text %}
The most important thing to understand about EEG is that while it is very good at answering questions about when in time a cognitive process occurs, and how that process is affected by different experimental manipulations, it is not good at localizing where in the brain activity occurs. Typically many brain regions are active at one time, and the inside of the head is an excellent conductor of these electrical signals. Thus the signals we record with electrodes on the outside of the scalp tend to be largest where the signals happen to add up, which is not necessarily directly over the part of the brain that is generating the signal. In cognitive neuroscience research, most people use EEG in two ways: event-related potentials (ERPs), and frequency-domain analyses.
{% endcapture %}
{%
  include feature.html
  image="images/cindy_eeg_2.JPG"
  link=""
  title=""
  text=text
%}

{% capture text %}
**ERPs** focus on EEG activity that is time-locked to an event of experimental interest. Commonly, this is the onset of a stimulus, such as a picture or a word. The ERP typically contains a series of peaks and troughs focused over certain parts of the scalp. We call these ERP *components* and they are typically what we focus on in ERP experiments. Different ERP components are associated with different cognitive processes. For example, one called the N400 is associated with processing the meanings of words (and also pictures), while one called the P600 is associated with grammatical processing in sentences. **Frequency-domain analyses** involve applying a mathematical transformation to the EEG signal, to computer the power (size) of the signal in different frequency bands. "Frequency" refers to how many peaks/troughs occur in a signal in a given period of time, like 1 second. Human EEG tends to be organized into different frequency bands (delta, theta, alpha, beta, and gamma), which can be associated with different cognitive processes.
{% endcapture %}
{%
  include feature.html
  image="images/DSC_3734 copy.JPG"
  link=""
  title=""
  text=text
  flip=true
%}

## Magnetic Resonance Imaging (MRI)
MRI is used to get images of various parts of the body, including the brain, using a combination of magnetic fields and radio waves. MRI is one of the best ways to look at the brain, because it is very safe (it doesn't use radiation or x-rays), and it can provide both high-resolution anatomical images, and functional images showing which areas "light up" during different cognitive tasks. MRI scanners are very expensive to install and maintain; for this reason, we do not have an MRI scanner in NCIL, but we have access to MRIs for research purposes at the nearby IWK and QEII health centres. MRI studies are very expensive to run and typically we can only conduct an MRI research study if we have a significant research grant to cover these costs.

{% capture text %}
Functional MRI (fMRI) works by measuring the amount of oxygen delivered to different parts of the brain. When neurons (brain cells) are active, more oxygen is delivered to those parts of the brain. This means that fMRI has excellent spatial resolution: we can localize where activity is occurring down to the level of a few millimetres. On the other hand, fMRI does not have the same sensitivity as EEG to when activity occurs. This is because the changes in blood oxygenation that we measure are an indirect measure of the electrical activity of neurons. Whereas we can distinguish different EEG signals that are separated by only a few milliseconds in time, the signal we measure with fMRI changes only on the order of seconds. Thus fMRI and EEG are complementary techniques that can each answer different questions in cognitive neuroscience.
{% endcapture %}
{%
  include feature.html
  image="images/child_in_MRI_scanner.png"
  link=""
  title=""
  text=text
%}

In addition to fMRI, MRI scanners can produce other types of scans that are useful in research. These include anatomical scans that allow us to measure things like cortical thickness and shape, and diffusion tensor images (DTI), which allow us to visualize and quantify the white matter tracts that connect different brain areas.

# Data Science
Coding (computer programming) is a vital skill in cognitive neuroscience. While many tasks can be completed using familiar software and GUIs (point-and-click graphical user interfaces), in NCIL much of our lab — including running experiments, managing data, and analyzing it — depends on custom software written in the Python and R languages. While you don't need to know how to code to get started volunteering or working on a research project in NCIL, this ability will become increasingly important the longer you stay, and the more you do, in the lab. Coding skills are also extremely valuable on the job market, and when applying to many graduate programs. Not only do coding skills look great on your CV, but they are good for you as well — coding teaches you to tackle problems in a systematic and logical way, breaking them down into small parts and addressing them in a sequential manner. 

There are many great resources for learning how to code. All NCIL lab members get free access to [DataCamp](https://datacamp.com), an online learning platform for data science. As well, Dr. Newman has written a free online textbook, [*Data Science for Psychology and Neuroscience in Python*](https://neuraldatascience.io), an associated [YouTube channel](https://youtube.com/playlist?list=PLtfEWMIgWS22MMZjPIzBRE2cHhMcvEKwp), and teaches a course based on this book, NESC/PSYO 3505 *Neural Data Science*. The [SURGE] sandbox also offers regular [*Discover Coding*](https://www.surgeinnovation.ca/discover) workshops on both Python (developed by Dr. Newman) and R (developed by NCIL alumnus Simon Leger).