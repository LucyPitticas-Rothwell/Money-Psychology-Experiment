# Detailed Experiment Overview and Guide

**1. Experiment overview**

This experiment is based on a series of experiments carried out by Vohs et al (2006), “The psychological consequences of money”. These experiments were designed to test the idea that money negatively changes people’s behaviour towards others.
The aim of the experiments in this programme were, specifically, to measure the extent to which exposure to money-related objects and concepts influenced people’s likelihood to ask for and offer help.
The hypothesis was that reminders of money, relative to non-money reminders, would lead to reduced requests for help and reduced helpfulness toward others.

**2. Description of procedure:**

Participants are randomly assigned to two conditions. In one condition (money prime), participants were reminded of money; control participants were not reminded of money. All participants first completed a descrambling task, which activated neutral concepts (control) or money concepts (money prime). The descrambling task consists of 5 sets of five jumbled words. Participants created sentences using the five words. In the control condition, the phrases primed neutral concepts (e.g., “Can you hear the birds?” became “I like to ride my bike”). In the money-prime condition, the phrases primed the concept of money (e.g., “She earns more than you” became “I have won £500 cash”. Participants in the money prime condition were also primed with images of money throughout.

Next, participants were given an impossible problem that involved arranging 16 coloured disks into a 16-grid square without allowing any two squares of the same colour to appear in the same horizontal, vertical or diagonal line. Participants were told there was a researcher live on standby, and that if they need help, they just needed to click the “help” button on the screen, and the researcher would respond with a tip. Persistence on the problem before asking for help was the dependent measure.

After the squares puzzle, a note arises on the screen explaining that the researcher is an undergraduate looking for help coding data, and asking whether the participant would be able to help. The note explains that each data sheet takes approximately 5 minutes to code. Participants indicate how many data sheets, if any, they would be willing to code. The number of sheets the participants offers to complete for the researcher is the dependent measure.


**3. Experimenter’s manual:**

To use this experiment, you simply need to send the (theoretical) URL to people you wish to participate.
By default, participants need to be 18 or over, which is mandated in the demographics page.
The following information will be automatically collected from each participant during this study, and written to a csv file in this folder called “Results CSV”:

- Age, Gender, Education Level
- Condition - whether participant was in money condition (“mc”) or the control group (“cc”)
- “Time squares”/ dependent variable 1: Time taken to ask for help during puzzle (a measure of self-sufficiency/ willingness to be helped by others)
- “Help offered”/dependent variable 2: Number of sheets agreed to be completed by participant (a measure of willingness to help others)

**Adaptation**

The programme needs no adaption for basic use. However, some flexibility has been built in case you would like to tailor elements of it:
- Increase number of sentences needing completed in the scramble task: Provided in the experiment folder are two text documents called “wordsMoney” and “wordsNeutral”. These documents hold the sentences which are used in the scramble task. To increase number of runs, simply 1) add extra sentences to the documents, in the same jumbled order as the others, and 2) change the number of “runs” in the nextScrambClicked() function (line 158) to the number of runs you want.

**Reference:**

Kathleen D. Vohs, Nicole L. Mead and Miranda R. Goode (2006). “The Psychological Consequences of Money”. Science 314 (5802), 1154-1156. 

