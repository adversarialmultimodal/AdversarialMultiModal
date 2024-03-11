# Breaking the Bot Barrier: Evaluating Adversarial AI Techniques Against Multi-Modal Defense Models


## Abstract
Websites utilize several approaches to detect automated agents. The agents are deployed either for beneficial purposes such as search engine crawlers, or to perform tasks on behalf of the adversary such as scanning for vulnerabilities. 
Recent methods in detecting such agents include the analysis of the behavior that the agents show when visiting the website. In this paper, I) we describe a deep learning framework that analyzes the triggered browser events to classify the visitor. II) We develop two adversarial attacks in order to bypass the defense by generating adversarial vectors that are misclassified by the model. III) We discuss how applicable the attacks are by reviewing the limitations of the popular tools (i.e., Selenium and Puppeteer) used for the development of automated agents based on full-fledged browsers.

## Repository Structure
The reposirty includes different moduels introduced in the corresponding submitted paper. You can find details of each module in the following.

### Data
We have provided sample traces from each of the experimented agent types. Additionally, `data` directory includes the required codes for preprocessing of the raw json files to be used in future analysis.

### Main Python Notebook
The utilized `LSTM` model architecture as well as the required codes for training and test phases are available in the first section of `main` notebook.
Additionally, we have included the brute-force attack which has been successful to generate modified sequences of events that are misclassified by the model. The code for the attack is included in the second section of `main` notebook.
