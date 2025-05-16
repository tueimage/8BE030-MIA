# Medical Image Analysis course (8BE030)
This course is a sequel to the introductory medical imaging course 8BB050 in which some of the basic principles of image analysis were covered and the introductory machine learning course 8BB020. In 8BE030 we will concentrate on the more advanced image analysis methods and on how they can be used to tackle clinical problems. Topics covered include image registration, segmentation and deep learning applications in medical image analysis.

## Learning outcomes
After passing this course, the student is able to:
1. explain the fundamental principles behind image transformations, point- and intensity-based medical image registration.
2. identify the required transformation model, correct (homogeneous) 2D transformation matrices, image similarity measure, and optimization method, given an example of a medical image registration problem.
3. implement segmentation problems in feature space using clustering or classification methods. 
4. apply graph cut algorithms, based on min-cut/max-flow, under a suitable formulation to perform image segmentation.
5. illustrate the mathematical foundations of statistical shape models (SSMs) and the practical steps to construct SSMs.
6. explain the different building blocks of (convolutional) neural networks and how supervised and unsupervised machine learning techniques can be applied to medical image analysis problems.
7. implement suitably designed medical image analysis methods using basic engineering and mathematical techniques (such as optimization) in Python.
8. perform the analysis and the interpretation of the performance of medical image analysis methods using appropriate validation metrics.

## Use of Canvas
This GitHub page contains information about the course and the study material. The Canvas page of the course will be used additionally for sharing course information that cannot be made public, quizzes, submission of the practical work and posting questions to the instructors and teaching assistants (in the Discussion section). Students are highly encouraged to use the Discussion section in Canvas for general questions (e.g., issues with programming environment, methodology questions).

TLDR: GitHub is for content, Canvas for communication and submission of assignments.


## Schedule
The 2025 edition of the course will be given on campus. The lectures will not be recorded to encourage on-campus participation.

The schedule is as follows:

* **Lectures**: Mondays 08:45 – 10:45 & Thursdays 13:30 – 15:30
* **Guided self-study**: Mondays 10:45 - 12:45 & Thursdays 15:30 - 17:30
* **Location**: All lectures are in VEC 0.113 except for Tuesday in week 8 (check your timetable)


The course schedule is summarized below:

| Week | Day | Date   | Time        | Activity                                 | Module              | Lecturer         | Topic                                                                                                        |
| ---- | --- | ------ | ----------- | ---------------------------------------- | ------------------- | ---------------- | ------------------------------------------------------------------------------------------------------------ |
| 1    | Thr | 24/Apr | 13:30-15:30 | Lecture                                  | Registration        | C. Scannell  & R. Su | Course introduction; introduction image registration; Geometrical transformations                            |
|      | Thr | 24/Apr | 15:30-17:30 | Guided selfstudy                         | Registration        |                  |                                                                                                              |
|      |     |        |             |                                          |                     |                  |                                                                                                              |
| 2    | Mon | 28/Apr | 08:45-10:45 | Lecture                                  | Registration        | R. Su | Point-based registration                                                                                     |
|      | Mon | 28/Apr | 10:45-12:45 | Guided selfstudy                         | Registration        |                  |                                                                                                              |
|      | Thr | 01/May | 13:30-15:30 | Lecture                                  | Registration        | R. Su | Intensity-based registration                                                                                 |
|      | Thr | 01/May | 15:30-17:30 | Guided selfstudy                         | Registration        |                  |                                                                                                              |
|      |     |        |             |                                          |                     |                  |                                                                                                              |
| 3    | Thr | 08/May | 13:30-15:30 |       Lecture       |      Segmentation             | R. Su             |       Introduction to image segmentation                                                                      |
|      | Thr | 08/May | 15:30-17:30 | Guided selfstudy                         | Project work        |                  |                                                                                                              |
|      |     |        |             |                                          |                     |                  |                                                                                                              |
| 4    | Mon | 12/May | 08:45-10:45 | Catch up day (NO LECTURE)                              |         | - |                                                                                      |
|      | Mon | 12/May | 10:45-12:45 | Guided selfstudy                         | Project work        |                  |                                                                                                                                                     
|      | Thr | 15/May | 13:30-15:30 | Lecture                                  | Segmentation        | R. Su | Segmentation in feature space                                                                                             |
|      | Thr | 15/May | 15:30-17:30 | Guided selfstudy                         | Segmentation        |                  |                                                                                                              |
|      |     |        |             |                                          |                     |                  |                                                                                                              |
| 5    | Mon | 19/May | 08:45-10:45 | Lecture                                  | Segmentation        | C. Scannell      | Graph-cuts                                                                                                   |
|      | Mon | 19/May | 10:45-12:45 | Guided selfstudy                         | Segmentation        |                  |                                                                                                              |
|      | Thr | 22/May | 13:30-15:30 | Lecture                                  | Segmentation        | C. Scannell      | Statistical shape models                                                                          |
|      | Thr | 22/May | 15:30-17:30 | Guided selfstudy                         | Segmentation        |                  |                                                                                                              | 
|      |     |        |             |                                          |                     |                  |                                                                                                              |
| 6    | Mon | 26/May | 23:59       | DEADLINE Report project 1 (registration) |                     | |      |
|      | Mon | 26/May | 08:45-10:45 | Lecture                                  | DL+applications     | C. Scannell      | Convolutional neural networks                                                           
|      | Mon | 26/May | 10:45-12:45 | Guided selfstudy                         | Segmentation        |                  |                                                                                                              |
|      |     |        |             |                                          |                     |                  |                                                                                                              |
| 7    | Mon | 02/Jun | 08:45-10:45 | Lecture                                  | DL+applications     | R. Su            |  Deep learning applications (registration)                                                                   |
|      | Mon | 02/Jun | 10:45-12:45 | Guided selfstudy                         | Segmentation        |                  |                                                                                                              |
|      | Thr | 05/Jun | 13:30-15:30 | Guest lecture (Philips)                  |                     |                  |                                                                    |
|      | Thr | 05/Jun | 15:30-17:30 | Guided selfstudy                         | Segmentation        |                  |                                                                                                              |
|      |     |        |             |                                          |                     |                  |                                                                                                              |
| 8    | Tue | 10/Jun | 08:45-10:45 | Lecture                                  | DL+applications     | C. Scannell      |  Deep learning applications (segmentation)                                                                   |
|      | Tue | 10/Jun | 10:45-12:45 | Guided selfstudy                         | Segmentation        |                  |                                                                                                              |
|      | Thr | 12/Jun | 13:30-15:30 | Lecture                                  | DL+applications     | C. Scannell      |  Unsupervised deep learning for medical image analysis                                                       |
|      | Thr | 12/Jun | 15:30-17:30 | Guided selfstudy                         | Segmentation        |                  |                                                                                                              |
|      |     |        |             |                                          |                     |                  |                                                                                                              |
| 9    | Mon | 16/Jun | 08:45-10:45 | Lecture                                  |                     | C. Scannell  & R. Su     | Questions & preparing for the exam                                                                   |
|      | Thr | 19/Jun | 23:59       | DEADLINE Report project 2 (Segmentation) |                     |                  |                                                                                                              |
|      |     |        |             |                                          |                     |                  |                                                                                                              |
| 10/11   |  |CHECK TIMETABLE|  | WRITTEN EXAM                             |                     |      |

## Lectures handouts and connection with notebooks
Please find below an overview of the lecture handhouts, the contents discussed, and the corresponding notebook(s).

| Lecture handouts (PDF) | Filename                                                        | Contents                                                                                                                   | Notebook(s)                                |
| ---------------------- | --------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------ |
| 1a                     | Course introduction                                             | Practical information about the course                                                                                     | 0.1                                        |
| 1b                     | Introduction to image registration; Geometrical transformations | Review of linear algebra; Introduction to image registration; Geometrical transformations                                  | 1.1                                        |
| 2                      | Point-based registration                                        | Point-based registration (theory); Optimization; Evaluation of registration accuracy                                       | 1.2                                        |
| 3                      | Intensity-based registration                                    | Probability theory; Intensity-based similarity metrics; Optimization; Gradient descent; Intensity-based image registration | Spread over three notebooks: 1.3, 1.4, 1.5 |
| 4                      | Introduction to image segmentation                              | Thresholding-based segmentation; Gaussian mixture models; Evaluation metrics for image segmentation.                       | Continue with 1.3, 1.4, 1.5                |
| 5                      | Catch-up lecture                                                | ...                                                                                                                        | Registration project work                  |
| 5                      | Segmentation in feature space                                   | Segmentation by K-Means clustering; Segmentation by classifiers; Generalization and overfitting                            | 2.1, 2.2 2.3                               |




# Practical work (exercises and project work)
During the practical sessions the students can work on practical exercises and the project (however, it is expected that students will also work on the project in their own time). The goal of the practical exercises is to help study and understand the material, and develop code and methods that can be used to complete the project work. Your are expected to do this work independently with the help of the teaching assistants during the guided self-study sessions (begeleide zelfstudie). You can also post your questions in the Discussion section in Canvas at any time.

NB: Sign yourself up for a project group in Canvas->people->groups.

## Software

**IMPORTANT: It is essential that you correctly set up the Python working environment by the end of the first week of the course so there are no delays in the work on the practicals.**

To get started, carefully follow the instructions [here](https://8dc00-mia-docs.readthedocs.io/en/latest/reader/0.1_Software_guide.html).

## Assessment
The assessment will be performed in the following way:
* Project work: 30% of the grade (both projects have equal contribution)
* Written exam (open answer and multiple-choice questions): 70% of the grade

To pass the course the written exam grade needs to be > 5.0 and the final grade needs to be > 5.5.

Grading of the assignments will be done per group, however, it is possible that individual students get a separate grade from the rest of the group (e.g. if they did not sufficiently participate in the work of the group). More info on the assessment criteria can be found [here](rubric.md).

## Lecturers and teaching assistants
Course instructors:
* dr. Cian Scannell (Assistant Professor) - c.m.scannell@tue.nl
* dr. Ruisheng Su (Assistant Professor) - r.su@tue.nl

Teaching assistants:
*  Joris Mentink
*  Job Schöller
*  Dirk Sollewijn Gelpke
*  Danny Struijk


The main communication with the teachers will be via Canvas and regularly scheduled lectures/self-study. We recommend the Discussion section in Canvas as the primary communication channel as this is visible for all students and teachers. 


