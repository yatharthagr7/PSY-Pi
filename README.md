![Intro page](https://drive.google.com/uc?export=view&id=1XH3i7_4bbk1zE4XhImlhdGWnvT7lZr0F)
![gif](https://drive.google.com/uc?export=view&id=1mPliBGCSiCloPLsr2X7eHFnF8x4jnknP)
<h1>Presenting You the First Psychiatric Assistant PSY-PI</h1>

<h2>BACKGROUND</h2>
<p>
The pandemic played with the minds of all the humans beings on the planet. It was fruitful for someone and it was a disaster for many. This pandemic led to unemployment for many people who were devastated and it affected them deeply.

For students like us we were forced to engage ourselves with online classes and online learning took place at a major scale. Students who didn’t had the habit of being in front of their computers for a long time developed some psychiatry problems affecting their mental and personal health. Since everything came to a pause for a long time that is from school going kids playing outside to the people engaged in the industrial sectors. In three psychiatry case-control cohorts, we compared the perceived mental health impact and coping and changes in depressive symptoms, anxiety, worry, and loneliness before and during the COVID-19 pandemic between people with and without lifetime depressive, anxiety, or obsessive-compulsive disorders.
</p>
<h2>INTRODUCTION</h2>
<p>
Don’t Worry Now! We Team Pi present you PSY-Pi, Your personal Virtual Psychiatrist who let’s you know about your emotions and makes you aware about them. PSY-Pi works on the principle of computer vision. All we require is a working camera installed in your computer or laptop. PSY-Pi was made to give real time analysis of the behavioral changes observed in the person. Often behavioral changes or the mood swings leads to several mental health issues and people without knowing are admitted to the hospitals. We Team Pi had a vision of avoiding all those psychiatrists demanding huge amount of money. All you need to do is don’t waste money on them unnecessarily and head to our web page before when you require to analyse a person whether he/she is your classmate, friend, colleague, sibling, relative or any other relation you have with the other person.<br>

What we are suggesting here is we require someone to make their relative or a friend or their siblings to make them sit in front of our web app and then all you need to do is head to “Analyze” button below such that when the camera turns on all you need to do is ask questions to the person who you think may have developed some mental health issues.<br>

Just to give you a head’s up is that we require you to allow our web app to take your Video to analyze and then give you the output.
<p>
<h2>Problem Statement</h2>
<p>
Now a days, mental health has become a very important part in the healthcare sector, so people are becoming more aware and concern about their mental health, but people don’t know how and what should they do to check their mental health status. The current issue has played with the minds of the people where 1 out of 5 people suffer from mental health issues. Most percentage of people have been prone to depression and loneliness and they usually develop anxiety disorders. And to further tackle mental problems, psychiatrists usually take hefty amount of money.
</p>
<h2>Team Pi's Solution</h2>
<p>
We “Team Pi” presents you the virtual assistant, that will read the user’s facial expressions and generate report for the patient, which would help the patient to know their mental health status. They get a detailed report which they could further consult it with a professional psychiatrist in order to get an in depth view of their behavioural changes. We are making their task easier and also we are trying to aware the user’s about their current mental health issues. Rather than spending huge amounts of money to psychiatrists, user’s can go for our web application to view their detailed emotions.
</p>
<h2>So How does it Work then ?</h2>
<p>
We took a pre-trained model to minimise our time and further for making this we referred several documents for the same. <b>We also referred several other github repositories</b> to make it more better for the user. Currently our django application runs on a local server. <b>The model was made using tensorflow, python, keras, DB, HTML, CSS and JS.</b>

Here we are analysing the input video, for the datasets we are using the popular FER2013 Kaggle Challenge data set. The data consists of 48x48 pixel grayscale images of faces. <br>
The faces have been automatically registered so that the face is more or less centered and occupies about the same amount of space in each image.<br>
Final model first includes 3 consecutive blocks consisting of the following four layers : one-dimensional convolution layer - max pooling - spatial dropout - batch normalization. The numbers of convolution filters are respectively 128, 256 and 512 for each block, kernel size is 8, max pooling size is 2 and dropout rate is 0.3. Following the three blocks, we chose to stack 3 LSTM cells with 180 outputs each. Finally, a fully connected layer of 128 nodes is added before the last classification layer.<br>
A brief overview of how it works is:<br>
Camera input in the form of several frames -->>Face Detection -->>Facial Landmarks Detection -->>Classification -->>Output in the form of graph


[Click here for the datasets](https://drive.google.com/drive/folders/1MfXn-GFqrw1LRZ1Y3bEZXoJbu8iQIAEN?usp=sharing)
You can access all the datasets here.. Cheers !!

</p>
<h2>Challenges We Ran Into ! </h2>
<p>So it was really difficult to train but and embed in the backend. Also, Our main aim was to deploy it using domain.com but we couldn't since everything took time.<br>
At times Computer Vision wasn't able to detect properly and we were able to achieve it using haarcascade detection and many more. Well to be honest our team members were a beginner in web development but we tried learning django by reffering several online sites and we could come up with the current project shown.</p>

<h2>Accomplishments We Are Proud Of</h2>
<p>Yeah, We are proud of providing a statistical analysis to the user as our output giving probability of each emotion at real time response. Further, Computer Vision helped us a lot and later we could build a simple django application.</p>
<h2>What all we Learned then ?</h2>
<p>Being students we thrive to make much more better projects at each and every hackathon, where our primary goal remains to solve the problems which are usually not given importance too and our neglected as well in the daily scenario. <br>
Participating makes us do several things in a limited time where we learn quickly and try to make our best possible project.</p>
<h2>FUTURE GOALS</h2>
<p>
Our future aim is to add a personal assistant to make it communicate to the user realtime. Adding chatbots for asking frequent questions when the user returns to our web application. We also hoped to add real life psychiatrists, such that the user could also contact them and have feedback based on their analysis overall. So yeah, We tried making difference in the lives of these people.
</p>
<h1>Reminder: You Are UNIQUE !</h1>
<h2>I hope we made some difference in the lives of these people.</h2>

<h3> 🤝🏻 Connect with Team Pi </h3>
:star: Members of Team Pi

## Brains behind this project:

<a href="https://github.com/Curovearth"> :brain: Swarup Tripathy </a>

<a href="https://github.com/yatharthagr7"> :brain: Yatharth Agarwal </a>

<a href="https://github.com/anvit1618"> :brain: Anvit Agarwal </a>
