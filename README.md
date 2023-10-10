# Starbucks

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>
The code was tested using Python version 3.9. 
For other necessary libraries please use requirements.txt
```bash
pip install -r requirements.txt
```

## Project Motivation<a name="motivation"></a>

This project is dealing with Starbucks advertising promotion campaign data and concentrated on 
1.	evaluation how successful the new promotion campaign was using A/B Testing. The optimization is based on maximization of two types of metrics 
    -	Incremental Response Rate (IRR)
    -	Net Incremental Revenue (NIR)
2.	building a Machine Learning model in order to detect hidden patterns and so making the promotion more profitable. 



## File Descriptions <a name="files"></a>

```bash
starbucks/
├── Starbucks.ipynb        # the notebook with AB Testing evaluation and Machine Learning optimization
├── README.md              # readme file
├── requirements.txt       # all necessary libraries
├── Test.csv               # test data
├── training.csv           # training data
├── test_results.py        # python script to test and compare results 

```


## Results<a name="results"></a>

The main findings of the code can be found at the post
1. "Why should your company do an AB testing? Starbucks A/B Testing Step by Step Part I" available [here](https://eneuburg.medium.com/why-should-your-company-do-an-ab-testing-88d42ec8337c).
2. "Random Forest: a Machine Learning Model in Marketing Strategy & Decision Making, Better than A/B testing ? Starbucks optimizing the results with Random Forest after A/B Testing Part II" available [here](https://eneuburg.medium.com/random-forest-a-machine-learning-model-in-marketing-strategy-decision-making-better-than-a-b-4ccfc0fb36d1)

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
 

Must give credit to Starbucks for providing the data. 



###### Copyright (C) 2021 November
###### TO THE FULLEST EXTENT PERMITTED UNDER APPLICABLE LAW, THE CODE COMPONENTS ARE PROVIDED BY THE AUTHORS, COPYRIGHT HOLDERS, CONTRIBUTORS, LICENSORS, “AS IS”.

######  DISCLAIMED ARE ANY REPRESENTATIONS OR WARRANTIES OF ANY KIND, WHETHER ORAL OR WRITTEN, WHETHER EXPRESS, IMPLIED, OR ARISING BY STATUTE, CUSTOM, COURSE OF DEALING, OR TRADE USAGE, INCLUDING WITHOUT LIMITATION THE IMPLIED WARRANTIES OF TITLE, MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NON-INFRINGEMENT.
######  IN NO EVENT WILL THE COPYRIGHT OWNER, CONTRIBUTORS, LICENSORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION). HOWEVER, CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THE CODE COMPONENTS, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE. 


