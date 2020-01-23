# Mobile Typing Analysis
In this project, we analyze a typing dataset (Palin et al. 2019) which is the observations from a study with 37,000 volun- teers on how people type in mobile devices. The dataset comes from a observation research done by the HCI research group at Aalto University(directed by prof. Antti Oulasvirta). It was collected by a web-based transcription task. The task was to transcribe 15 English sentences and answer a questionnaire after. The participants of the task came from a public website (www.typingtest.com) for training and testing of typing skills. You can learn more about it via the following link:https://userinterfaces.aalto.fi/typing37k/. The paper of the original research can be found in the repo under the name of "Paper.pdf". 

The goal of our project is to see whether word per minute(wpm) and error rate can be predicted given the background information such as ages and genders of the volunteers, what kind of input features the volunteers use. We try with two different models to do the prediction, linear regression and hierarchical generalized linear model. Both of them are able to predict the predict wpm and error rate given the input of user background information. And hierarchical generalized linear model performs better than linear regression. The details of the experiments can be seen from the file "Report.pdf".

Author: Jun Zhang, Morteza shiripour 

If you want to quickly check out the whole project, you can also have a look at the [slides](https://docs.google.com/presentation/d/19BC6E27o2JvS8r5PxtMApFIT-78uYQHRdh8fVlHP-ag/edit?usp=sharing) of the whole project.

## References
Palin, K., Feit, A.M., Kim, S., Kristensson, P.O. and Oulasvirta, A., 2019, October. How do People Type on Mobile Devices?: Observations from a Study with 37,000 Volunteers. In Proceedings of the 21st International Conference on Human-Computer Interaction with Mobile Devices and Services (p. 9). ACM.
