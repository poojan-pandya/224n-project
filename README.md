# 224n-project

Have you ever wondered if you're an asshole? Our model can tell you for sure*! We developed a deep learning model which processes input text from the r/AmItheAsshole community on Reddit, and produces a natural language explanation for why (or why not) the poster is an asshole.

\*Not sure at all, our model just seeks to imitate Reddit and has no basis for moral judgement

## Technical Details
We used an adversarial training approach, inspired by GANs often used in computer vision. We used BART and T5 implementations from the HuggingFace transformers library as a baseline and as a generator for our GAN. For the discriminator, we experimented with various architectures. You might be wondering why all of the Experiment notebooks are named after fruits. We were having trouble keeping track of all of our configurations, so we decided to give each experiment a fruit name. In our paper (`CS224N_Project_Report.pdf`), you can find descriptions for all of the fruits in Table 3!
