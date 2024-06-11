
<!DOCTYPE html>
<html>

<body>
    <h1>Project Description</h1>
    <p>Create a multiclass model to classify CTG features into the three fetal health states.</p>
    <p>Reduction of child mortality is reflected in several of the United Nations' Sustainable Development Goals and is a key indicator of human progress. The UN expects that by 2030, countries end preventable deaths of newborns and children under 5 years of age, with all countries aiming to reduce under‑5 mortality to at least as low as 25 per 1,000 live births.</p>
    
  <h2>Data</h2>
    <p>This dataset contains 2126 records of features extracted from Cardiotocogram exams, which were then classified by three expert obstetricians into 3 classes:</p>
    <ul>
        <li>Normal</li>
        <li>Suspect</li>
        <li>Pathological</li>
    </ul>
    
  <h2>What is a Cardiotocogram?</h2>
    <p>A cardiotocogram (CTG) is a technical means of recording the fetal heartbeat and the uterine contractions during pregnancy. It is used to monitor fetal well-being and to detect any fetal distress.</p>
    
  <h2>Features</h2>
    <h3>Fetal Heart Rate (FHR) Related</h3>
    <ul>
        <li>Baseline value: Baseline Fetal Heart Rate (FHR) (beats per minute)</li>
        <li>Accelerations: Number of accelerations per second</li>
    </ul>
    
  <h3>Fetal Movement</h3>
    <ul>
        <li>Fetal movement: Number of fetal movements per second</li>
    </ul>
    
  <h3>Uterine Activity</h3>
    <ul>
        <li>Uterine contractions: Number of uterine contractions per second</li>
        <li>Light decelerations: Number of light decelerations (LDs) per second</li>
        <li>Severe decelerations: Number of severe decelerations (SDs) per second</li>
        <li>Prolonged decelerations: Number of prolonged decelerations (PDs) per second</li>
    </ul>
    
  <h3>Variability</h3>
    <ul>
        <li>Abnormal short term variability: Percentage of time with abnormal short term variability</li>
        <li>Mean value of short term variability: Mean value of short term variability</li>
        <li>Percentage of time with abnormal long term variability: Percentage of time with abnormal long term variability</li>
        <li>Mean value of long term variability: Mean value of long term variability</li>
    </ul>
    
  <h3>Histogram Features</h3>
    <ul>
        <li>Histogram width: Width of histogram made using all values from a record</li>
        <li>Histogram min: Histogram minimum value</li>
        <li>Histogram max: Histogram maximum value</li>
        <li>Histogram number of peaks: Number of peaks in the exam histogram</li>
        <li>Histogram number of zeroes: Number of zeros in the exam histogram</li>
        <li>Histogram mode: Histogram mode</li>
        <li>Histogram mean: Histogram mean</li>
        <li>Histogram median: Histogram median</li>
        <li>Histogram variance: Histogram variance</li>
        <li>Histogram tendency: Histogram tendency</li>
    </ul>
    
  <h3>Target Variable</h3>
    <ul>
        <li>Fetal health: Encoded as 1-Normal; 2-Suspect; 3-Pathological. It is our target column in the dataset.</li>
    </ul>
</body>
</html>
