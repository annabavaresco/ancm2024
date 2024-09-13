.. Example documentation master file, created by
   sphinx-quickstart on Sat Sep 23 20:35:12 2023.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Advanced Neural and Cognitive Modelling 2024
===================================
This website contains the materials for the lab sessions of the couse Advanced Neural Cognitive Modelling 2024.

The TA for these labs is `Anna Bavaresco <https://annabavaresco.github.io/>`_. 
Please reach out to her if you have any questions related to the materials on this website.

.. note::
    The content of this website is largely based on materials 
    from the `2022 edition <https://clclab.github.io/ANCM/intro.html>`_ of the couse, 
    which were curated by `Marianne de Heer Kloots <https://mdhk.net/>`_ and 
    `Ashley Burgoyne <https://www.mcg.uva.nl/people/jaburgoyne/>`_.

+++++++++++++++
Goals and teaching principles behind the assignments
+++++++++++++++

Trivial as it may sound, the tutorials included in this course were created mainly for you to **learn**.
This means that you should ideally experience the notebooks as challenging but not overwhelming. If,
for any reason, you find the contents too easy or too hard, feel free to politely point this out to 
the TA(s) and they will do their best to adjust the course materials based on your learning needs and goals.

+++++++++++++++
Grading system
+++++++++++++++

Each of your lab submissions can be assigned a maximum of 2 points and the overall grade will be an 
average of the individual scores. If you are not happy with the grade of one of your assignments, you
have the possibiliy of resubmitting it. This will not completely erase your previous grade, but the new 
grade for your assignment will be the average between the old and the new grade. When converting the final 
points (mean of all the four assignment) to an actual grade, a 0 will be converted to a 4, a 1 to 7, 
and 2 to 10.

Each assignment will be graded acconding to the following criteria:

#. **Quality of the code**: whether your code is correct, well-structured, and well-commented

#. **Strength of motivation**: this refers to how well you can explain and motivate the conclusions
   you draw from your small experiment. Note that the "correctness" of the conclusions will be taken into
   account but you won't get full points of you state the "right" conclusion without motivating it well. 
   At the same time, if you don't get to the expected conclusion but make insighful speculations about your 
   results, you will still get some points

#. **Writing style**: whether contents are expressed clearly, concisely, and using appropriate terminology.

For each of the above criteria, you will receive a score ranging from 0 to 2:

*  **0** (converted to 4): assignment not turned in without a valid motivation

*  **0.5** (converted to 5.5): code just drafted, style poorly curated, motivation inconsistent

*  **1** (converted to 6): code present and running but not very well commented/motivated, 
   style understandable but often using inappropriate/colloquial terms and structures, 
   the main ideas are roughly present but not justified/explained well

*  **1.5** (converted to 8): code nicely written and including the required steps but containing minor 
   mistakes, good style which might benefit from minor improvements, good motivation but not fully 
   supporting the expected conclusion

*  **2** (converted to 10): good and well-documented code including all the expected steps, nice academic writing style
   with appropriate terms, solid and well-explained motivations.

.. note::
   The assignments are not perfectly balanced in the amount of coding and/or writing 
   they require. When averaging the scores for the aforementioned criteria, their 
   prominence in the assignment will also be taken into account. In other words,
   if you write great code but a somewhat unclear textual explanation for an assignment
   where the coding workload is clearly greater than the explanation-writing workload,
   the number of points that you get will be still high, as it is more influenced by the
   coding. 

+++++++++++++++
Questions you may have about the assignments/tutorials
+++++++++++++++

**Do I have to attend computer labs?**
Attending computer labs is not mandatory, so no need to worry if you have schedule conflicts. If you don't, however,
consider attending the computer labs in person, as it will make it easier for you to ask clarification questions to the 
TA(s) and/or discuss any doubts you may have with coursemates.

**What do I have to submit? A notebook, a PDF, or both?**
You should submit both a notebook and a PDF. The notebook should include the code to reproduce your analyses/results.
As for the PDF, please include there any written answer/report that the assignment/question require. Consider also including 
some figures or tables, if you think it might be convenient to present your
results more effectively. Tables and figures will not count toward the page/word limit (if there is any).

**When will I see the grade for my assignment?**
The TA(s) will do their best to grade the assignment as soon as they can, but it may
not always be possible for them to grade each assignment before the next submission deadline. 
You will, however, definitely get feedback on your assignments throughout the
course, so that you have the chance to improve and increase your final grade, 
if you wish.

**Can I work on the notebooks together with coursemates?**
Assignments are submitted and graded individually. However, it is known that peer learning can significantly
improve the learning experience for students. If you find yourself stuck on a topic/notebook and you feel
that working on it with a coursemate might help you learn, you are absolutely welcome to do so. Remember, however,
that the goal should always be for you to **learn** contents, not to passively copy a solution that
your coursemate came up with. 

**Can I use ChatGPT to help me with the notebooks?**
Similar to the previous question, the answer is, it depends. If you are looking for a shortcut to submit
the best possible report with the minimum effort, the answer is no. If, on the other hand, you are stuck on 
something and too shy to reach out to coursemates and TA(s), then using ChatGPT to get more clarity on a
topic/question is perfectly acceptable. Again, remember that simply copy-pasting something ChatGPT-generated
is not acceptable and won't probably teach you anything. Using ChatGPT to improve the style of your 
report is also discouraged: if you don't try to work on your writing style yourself, it's never going to improve!

**I have an offline question about the computer labs. Should I contact the TA right away?**
The TA(s) are there to help you and do their best to answer your questions. However, they are unfortunately human beings
with limited time and resources. This means that, if they get too many emails/requests, they will inevitably
be slow in responding. If you have a question about the computer labs, it may be good to check with your coursemates
if the information wasn't communicated clearly or if you accidentally missed it, and contact the TA only after. 
If you find that other students
have (or might have) the same doubt you have, please also consider posting your question on Canvas, as the answer
may be useful for other coursemates.


**Due to unforeseeable circumstances, I will be unable to submit the assignment(s) within the deadline. What should I do?**
Contact the TA or the course coordinator. If you have good reasons for being unable to submit the assignment,
they will most likely understand and do their best to find a solution that is suitable for you.

+++++++++++++++
Contents:
+++++++++++++++

   .. Section 1: Week 1
   .. 1_Logistic_regression_for_musical_tags.ipynb

   .. Section 2: Week 2
   .. 2A_Language_Model_Refresher.ipynb
   .. 2B_RSA_with_fMRI_Data.ipynb
   .. 2C_LM_Surprisal_and_EEG_data.ipynb

.. toctree::
   :maxdepth: 1
   :caption: Week 1:

   week_1/1_Logistic_regression_for_musical_tags.ipynb

.. toctree::
   :maxdepth: 1
   :caption: Week 2:

   week_2/2A_Language_Model_Refresher.ipynb
   week_2/2B_RSA_with_fMRI_Data.ipynb
   week_2/2C_LM_Surprisal_and_EEG_data.ipynb

.. toctree::
   :maxdepth: 1
   :caption: Week 3:

   week_3/3_IRT_Stan.ipynb


   