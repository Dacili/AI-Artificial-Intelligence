# AI - Artificial Intelligence
## What is AI?
AI is a set of technologies that **enable computers to perform a variety of advanced functions**.  
(Ability to see, understand and translate spoken and written language, analyze data, make recommendations,...)


## Generative AI
A branch of AI that enables software applications to **generate new content**.  
Content can be: natural language dialogs, images, video, code, and other formats.   

### Language model
The ability to generate content is based on a **language model**, which has been **trained with huge volumes of data** - often documents from the Internet or other public sources of information.  
There are 2 types:  
1. **Large language models (LLMs)** - **very powerful** and generalize well, but can be **more costly** to train and use  
2. **Small language models (SLMs)** - tend to **work well** in scenarios that are more **focused on specific topic** areas, and usually **cost less**.  
<img width="480" height="360" alt="image" src="https://github.com/user-attachments/assets/7bc46439-77c9-4a49-96e8-7e9c10fcc819" />   

      
**Common uses** of generative AI include:  
chatbots and AI agents, creating new documents or other content, translation, summarizing, or explaining...

## Computer vision
Computer vision is accomplished by using **large numbers of images to train a model**.  

**Image classification** is a form of computer vision in which a model is:  
- trained with images that are **labeled** with the main subject of the image,  
- so that it can analyze **unlabeled images** and  
- identify/**predict the subject** of the image.     
<img width="509" height="268" alt="image" src="https://github.com/user-attachments/assets/a0eba59c-318d-487b-8dbf-a02c144c0f72" />  
  
**Object detection** is a form of computer vision in which the model is trained to **identify** (draw a box around) the location of specific **objects in an image**.  
<img width="694" height="452" alt="image" src="https://github.com/user-attachments/assets/a3775526-db29-485c-8a60-9f3055721f98" />  

**Semantic segmentation** is an advanced form of object detection where, *instead of drawing a box around the subject*, **the model can identify the individual pixels** in the image that belong to a particular object.  
<img width="896" height="525" alt="image" src="https://github.com/user-attachments/assets/8b786eeb-667e-484f-b213-95b478b1bda8" />  

**Common uses** of computer vision include:  
key-word (tag) generation for photographs, visual search, monitoring stock levels or identifying items, security video monitoring, authentication through facial recognition, robotics and self-driving vehicles...

## Speech
**Speech recognition (speech-to-text)** is the ability of AI to "hear" and interpret speech, audio -> text.  
<img width="296" height="133" alt="image" src="https://github.com/user-attachments/assets/bfaaec5c-2b1e-4d26-a3b8-9f7c3cf1a559" />   
    
**Speech synthesis (text-to-speech)** is the ability of AI to vocalize words as spoken language, text -> audio.  

AI speech technology is evolving rapidly to handle challenges like ignoring background noise, detecting interruptions, and generating increasingly expressive and human-like voices.   


**Common uses** of AI speech technologies include:   
personal AI assistants, transcription of meetings, audio descriptions of video or text, speech translation between languages...



## Natural language processing (NLP)
NLP = enable computers to **understand and communicate with human language**.   

<img width="760" height="680" alt="image" src="https://github.com/user-attachments/assets/6cec9153-7ab0-481a-b66b-880188540a85" />   
  
Common NLP tasks include:  
 - **Entity extraction** - identifying mentions of entities like people, places, organizations in a document    
 - **Text classification** - assigning a document to a specific category.    
 - **Sentiment analysis** - determining whether a body of text is positive, negative, or neutral and inferring opinions.  
 - **Language detection** - identifying the language in which text is written.  

<img width="918" height="341" alt="image" src="https://github.com/user-attachments/assets/bd60e86a-3bc7-4e6b-ab99-8c5e7ec653ff" />  

**Common uses** of NLP technologies include:  
analyzing documents or transcripts of meetings, analyzing social media posts, product reviews, or articles to evaluate sentiment and opinion...

## Extract data and insights
**Optical character recognition (OCR)** - converts typed, handwritten, or printed **text, from images into text**.   
<img width="602" height="360" alt="image" src="https://github.com/user-attachments/assets/8987772d-c9b7-426c-8a79-cffaea637296" />

More advanced models can extract information from audio, images, and videos.  


**Common uses** of AI to extract data and insights include:  
automated processing of forms and other documents, large-scale digitization of data from paper forms,...

## Responsible AI
### What is bias?
**Bias**: Occurs when training data is **not representative of the real-world population**.    
For example, if a facial recognition model is trained mostly on *lighter-skinned* individuals, it may struggle to accurately identify people with *darker skin* tones, **leading to discriminatory outcomes**.  

### Responsible AI principles:
**Fairness**: *minimize bias* for fairness.  
**Reliability and safety**: AI is based on probabilistic models, it is not infallible. AI-powered applications need to take this into account and mitigate risks accordingly.  
**Privacy and security**: don't reveal private personal or organizational details.    
**Inclusiveness**: AI should be open to everyone; don't exclude some users.  
**Transparency**: AI can sometimes seem like "magic", but it's important to make users aware of how the system works and any potential limitations it may have.  
**Accountability**: people and organizations that develop and distribute AI solutions are accountable for their actions.  

![Uploading image.png…]()

-----

<img width="500" src="https://github.com/user-attachments/assets/33698a58-cf3e-416f-8f9a-9e6394e24b05">  
https://www.geeksforgeeks.org/ai-ml-ds/?ref=shm  
https://www.geeksforgeeks.org/machine-learning/  

## Concepts of AI to learn:
- ### Machine learning (ML)
- ### Deep learning (DL)
- ### Generative AI (LLMs)
- ### Data science (DS) e and analytics
- ### AI projects
- ### AI frameworks and tools (TensorFlow, PyTorch, or Scikit-learn)
------

## 1. Machine learning (ML)
ML enables computers to learn from data and make predictions.   
ML is the subset of AI that focuses on **the development of algorithms and statistical models** that enable computer systems or machines to perform tasks without being explicitly programmed to do so.  
Understanding mathematical concepts relevant to ML, such as *linear algebra, calculus, and probability*, is crucial for effectively designing and training ML models.   
<img src="https://github.com/user-attachments/assets/5eb12742-e9c8-40d2-9352-82db06ba49b2">  


------
## 2. Deep learning (DL)
Deep Learning is a subset of ML that focuses on training **artificial neural networks (ANNs)** with multiple layers to learn from large volumes of data.  
These neural networks, inspired by the structure and function of the human brain, are composed of **interconnected nodes** called **neurons**.  
The term **“deep”** refers to the **multiple layers** in these networks, allowing them to learn hierarchical representations of data.  
![image](https://github.com/user-attachments/assets/652aa89c-ab71-4614-b5c9-eff4aad4bb6c)  

Deep learning excels in tasks such as:  
| Task  | What is it | Tasks | Math | 
| ------------- | ------------- | ------------- |------------- |
| **Computer Vision**  | focuses on enabling computers to interpret and understand visual information from the real world, similar to the way humans do.   |image classification, object detection, facial recognition, image segmentation...   |linear algebra, calculus, and image processing techniques    |
| **Natural language processing (NLP)**  |  focuses on enabling computers to understand, interpret, and generate human language in a meaningful way.   |text and speech, to extract insights, derive meaning, sentiment analysis, language translation, named entity recognition, text summarization, and question answering.    |  probability, statistics, and machine learning    |

![image](https://github.com/user-attachments/assets/92a2ddb6-a36c-485c-867b-2810e885dd17)

------
## Machine vs deep learning
> **Deep** learning can **learn from its own errors** while **machine** learning needs a **human to intervene**.
------
## 4. Data science (DS) and analytics
Data analysis involves the process of inspecting, cleaning, transforming, and modeling data to uncover insights, patterns, and trends.  
Data Science is an interdisciplinary field that combines various techniques and methods from statistics, mathematics, computer science, and domain-specific knowledge to extract insights and knowledge from structured and unstructured data.   
<img width="400" src="https://github.com/user-attachments/assets/0e2f39fd-b755-46af-b2d3-709db85fbd46">  
## Data science vs Data Analytics
While both fields involve working with data to gain insights, **data science** often involves using data to build models that can **predict future outcomes**,  
while **data analytics** tends to focus more on **analyzing past** data to inform **decisions in the present**.

------

