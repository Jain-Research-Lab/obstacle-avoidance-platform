# obstacle-avoidance-platform
Title: Obstacle Avoidance Platform

Date of Release: December 2020

Associated Publication: Katherine J. Williams, Madeleine S. Yuh, and Neera Jain, "A Computational Model of Coupled Human Trust and Self-confidence Dynamics," ACM Transactions on Human-Robot Interaction 2023.

Link to Publication: https://dl.acm.org/doi/full/10.1145/3594715

Suggested Citation: Please reference the associated publication above when using any of the code contained in this repository.

Contact Information: Neera Jain, Purdue University, West Lafayette, Indiana, U.S.A, neerajain@purdue.edu

Folder/File description
  - css folder is for cascading style sheets. It can control the layout of multiple web pages all at once.
  - images folder contains all image files utilized aside from those used for initial instructions of the game
  - instructions folder contains all image files used for the instructions phase of the game.
  - js contains all necessary JavaScript files
    - pgt.js is the JavaScript file that contains all relevant functions necessary to run the game (e.g. penguin movements). 
    - random_theta.js contains the JavaScript functions that alter the assistance value (in this case, a scaling factor) during trials.
  - Results folder contains all results in txt form.
    - Results are sorted into 4 folders depending on the ordering of scaling factor changes. See notes for more detail.
  - index.html is the HTML file that controls the user interface of the game.
  - .php files are used for filehandling (saving results files)

NOTES:
**Automation Assistance - Scaling Factor:** In this experiment, the automation assistance is a scaling factor applied to the penguin's movement via mouse drag and click, ranging from 0.7 to 1.5. There are three groupings of scaling factors: Low (0.7, 0.8, 0.9), Medium (1.0, 1.1, 1.2), and High (1.3, 1.4, 1.5). The first five and last five trials use different groupings of scaling factors (e.g. trials 1-5 Low, trials 6-10 High), in which the specific scaling factor is randomized within the set of available scaling factor values within the group. To account for ordering effects, participants are randomly given a combination of scaling factor groups in the experiment. These are sorted into the following results folders:
  - Change_1: Low    -> Medium
  - Change_2: High   -> Medium
  - Change_3: Medium -> Low
  - Change_4: Medium -> High

For more details on the experiment, please refer to the publication.
