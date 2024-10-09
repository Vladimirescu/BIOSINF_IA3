
# Project Description: Implementing Adversarial Attacks and Defense Mechanisms

**Objective:**  
The purpose of this project is to explore the vulnerabilities of machine learning models to adversarial attacks and to implement defense mechanisms to improve their robustness. Students will work in teams to design and carry out an experiment demonstrating the effectiveness of both attacks and defenses in a chosen classification task.

## Project Tasks:

1. **Team Formation:**  
   Students will form teams of up to 2 members.

2. **Choose a Classification Task:**  
   Each team must select a classification problem from the following possible tasks:
   - **Object Recognition:** Classifying images into categories, such as identifying objects in photographs.
   - **Music Genre Classification:** Categorizing music tracks based on their genre using audio features.
   - **Sentiment Analysis:** Classifying text data (e.g., reviews or tweets) as positive, negative, or neutral sentiment.
   - **Facial Expression Recognition:** Identifying emotions portrayed in facial expressions from images.
   - **Spam Detection:** Classifying emails as spam or not spam based on textual features.
   - **Medical Image Diagnosis:** Classifying medical images (e.g., X-rays, MRIs) for disease detection.
   - **Document Classification:** Categorizing documents or articles into topics or genres.

3. **Implement Adversarial Attacks:**  
   Teams will implement two different adversarial attack algorithms. The attacks can be chosen from the ones presented in the class or can be other methods, both black-box or white-box. The students are encourged also to come-up with their own version. Examples of suitable attacks include:
   - **[Projected Gradient Descent (PGD)](https://www.utdallas.edu/~mxk055100/courses/adv-ml-19f/1706.06083.pdf):** An iterative attack method that refines the adversarial example in multiple steps.
   - **[Carlini & Wagner Attack](https://ieeexplore.ieee.org/iel7/7957740/7958557/07958570.pdf):** A powerful optimization-based attack for crafting adversarial examples.
   - **[DeepFool](https://openaccess.thecvf.com/content_cvpr_2016/papers/Moosavi-Dezfooli_DeepFool_A_Simple_CVPR_2016_paper.pdf):** A method that rapidly generates perturbed images while remaining as close to the original as possible.
   - **[DDN](http://openaccess.thecvf.com/content_CVPR_2019/papers/Rony_Decoupling_Direction_and_Norm_for_Efficient_Gradient-Based_L2_Adversarial_Attacks_CVPR_2019_paper.pdf)**: Decouples the direction and the norm of the adversarial perturbation that is added to the image.
   - **[FMN](https://proceedings.neurips.cc/paper_files/paper/2021/file/a709909b1ea5c2bee24248203b1728a5-Paper.pdf)**: Proposes a more efficient attack generation compared to DDN

4. **Implement Defense Mechanisms:**  
   Teams will implement two defense techniques against adversarial attacks. The defenses can be chosen for the strategies presented in the course, or others found in the literature. Possible defense mechanisms include:
   - **Adversarial Training:** Training the model with a mixture of normal and adversarial examples to improve robustness.
   - **Gradient Masking:** Using techniques that obscure the gradient information to make it harder for adversaries to generate effective attacks.
   - **Defensive Distillation:** A technique that aims to reduce the sensitivity of the model to adversarial perturbations through a two-step training process.
   - **Feature Squeezing:** Reducing the complexity of the input by squeezing out unimportant features to lower the attack effectiveness.
   - **Lipschitz Regularization:** Train the network under spectral constraints in order to reduce the effect of the perturbation.

5. **Demonstration of Work:**  
   Each team will have to do the code implemetation of the chosen methods, **without using an existing library**. Each team will be required to demonstrate their implementation and findings. This should include:
   - Showing the results of the classification task without adversarial attacks.
   - Demonstrating the effects of the implemented adversarial attacks on the model's performance.
   - Presenting the results of the defense mechanisms and their impact on restoring accuracy against adversarial examples.

6. **Documentation and Source Code:**  
   Teams must provide clean and well-documented git repository including the source-code for their implementation. This should include:
   - A README file that explains how to set up and run the code.
   - A brief description of the algorithms and methods used.
   - Any additional notes that may assist us in understanding the project.

7. **Presentation:**  
   At the end of the project, each team will present their work, highlighting:
   - The classification task chosen and the rationale behind it.
   - The implementation details for the adversarial attacks and defense mechanisms.
   - The results of their experiments, including visualizations where appropriate.
   - Lessons learned throughout the process.

## Evaluation Criteria:  
Projects will be evaluated based on the following:
- Creativity in selecting the classification task and implementing algorithms.
- Effectiveness of the adversarial attacks and defenses.
- Clarity and organization of the presentation and documentation.
- Quality and thoroughness of experimental results and analysis.

## Topic assignment: 
The following table smmarises some possible choices for the project. Feel free to mix-and-match however you want the attacks, defenses and application that you choose. Each team has up to December 23rd to decide upon the configuration they will test for their final project (application/ 2 attacks/ 2 defenses). The following rules must apply: 
- There cannot be two teams with the same configuration
- No more than two distinct teams can choose the same application.
 Configuration assignment is first come, first served, though in case nobody signs up for some topics, we may ask some students to switch to ensure coverage.
To secure a project configuration, the students will fill in the sign-up document provided in the Teams group. 

| **Nr** | **Attack** | **Defense category** | Application |
|:-------:|:--------:|:--------:|:--------:|
| 1 | PGD | Adversarial Training | Object Recognition
| 2 | Carlini & Wagner Attack | Gradient Masking | Music Genre Classification
| 3 | DeepFool | Defensive Distillation | Sentiment Analysis
| 4 | DDN | Feature Squeezing | Facial Expression Recognition
| 5 | FMN | Lipschitz Regularization | Spam Detection
| 6 | | | Medical Image Diagnosis
| 7 | | | Document Classification
