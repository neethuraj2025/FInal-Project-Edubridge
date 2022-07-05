
<html>
  <h1 align='center'>
    Migraine Classification
  </h1>
  
  
  <h2>
    Objective
  </h2>
  <p1>
      To build a model to predict migraine 
  </p1>
  <img src="https://dornsife.usc.edu/assets/img/news/story/3670.jpg" alt="migraine_image">
  
  
   <h2>
    Overview
   </h2>
   <p1>
     A migraine is a headache that can cause severe throbbing pain or a pulsing sensation, usually on one side of the head. It's often accompanied by nausea, vomiting, and extreme sensitivity to light and sound.This dataset provided for users whose they want to apply machine learning practices. This dataset collected from many more clients.
   </p1>
  
  
  <h2>
     Acknoweldgment :
  </h2>
  <p1>
    This Datset is taken from Kaggle
  </p1>
  
  <h2>
    Datset 
  </h2>
  <p1>
  https://www.kaggle.com/datasets/weinoose/migraine-classification
  </p1>
  
  

  <h2>
    Dataset details
  </h2>
  <p1>
  <table>
  <tr>
    <th>Field</th>
    <th>Description</th>
    
  </tr>
  
  <tr>
    <td>Age</td>
    <td>Age of the patient</td>
    
  </tr>
  <tr>
    <td>Duration</td>
    <td>Duration of headache</td>
    
  </tr>
  <tr>
    <td>Frequency</td>
    <td>Frequency of headache</td>
    
  </tr>
  <tr>
    <td>Location</td>
    <td>Area of headache</td>
    
  </tr>
  <tr>
    <td>Character</td>
    <td>Headache character</td>
    
  </tr>
  <tr>
    <td>Intensity</td>
    <td>Intensity of the pain</td>
    
  </tr>
    
  <tr>
    <td>Nausea</td>
    <td>Whether the patient had nausea or not</td>
    
  </tr>
  <tr>
    <td>Vomit</td>
    <td>Whether the patient vomited or not</td>
    
  </tr>
  <tr>
    <td>Phonophobia</td>
    <td>Whether the patient have Phonophobia(Fear of Sound)</td>
    
  </tr>
  <tr>
    <td>Photophobia</td>
    <td>Whether the patient have Photophobia(Discomfort in bright light)</td>
    
  </tr>
  <tr>
    <td>Visual</td>
    <td>Clarity of vision</td>
    
  </tr>
  <tr>
    <td>Sensory</td>
    <td>Sensory disturbances(aura) present</td>
    
  </tr>
    
  <tr>
    <td>Dysphasia</td>
    <td>Is Dysphasia(Language difficulties) present</td>
    
  </tr>
  

  <tr>
    <td>Dysarthria</td>
    <td>Dysarthria is there or not(inability to control muscles for speech)</td>
    
  </tr>
  
  <tr>
    <td>Vertigo</td>
    <td>Vertigo is there or not(spinning feeling)</td>
    
  </tr>
  <tr>
    <td>Tinnitus</td>
    <td>Tinnitus is there or not(Hearing sound from inside of one's body)</td>
    
  </tr>
    
  <tr>
    <td>Hypoacusis</td>
    <td>Hypoacusis(Hearing loss) is there or not</td>
    
  </tr>
 
  <tr>
    <td>Diplopia</td>
    <td>Is Diplopia is there or not(some degree of hearing loss)</td>
    
  </tr>
  
  <tr>
    <td>Defect</td>
    <td>Any defect is there or not</td>
    
  </tr>
  
  <tr>
    <td>Ataxia</td>
    <td>Ataxia is present or not(co-ordination and balance issues)</td>
    
  </tr>
  
  <tr>
    <td>Conscience</td>
    <td>Does conscience issues persist(sense of right and wrong)</td>
    
  </tr>
  
  <tr>
    <td>Paresthesia</td>
    <td>Is Paresthesia is there or not(a burning sensation)</td>
    
  </tr>
  
  <tr>
    <td>DPF</td>
    <td>Cell density sensing factor</td>
    
  </tr>
  
  
  <tr>
    <td>Type</td>
    <td>Type of migraine(category)</td>
    
  </tr>
    
  </table>
  </p1>
  
  
  <h2>
    Problem Statement:
  </h2>
  <p1>
     This dataset collected from migraine patients.Based on the symptoms the migraine is classfied into different categories. The objective is to apply machine learning techniques on this data and predict migraine categories from features.
  </p1>
  
 

  
  <h2>
    Implementation
  </h2>
 <p1>
 Libraries<br>
 <ul>
  <li>NumPy</li>
  <li>Pandas</li>
  <li>Sklearn</li>
  <li>Matplotlib</li>
  <li>Seaborn</li>
</ul>
</p1>
    
  
 
 
  <h2>
   Approach
  </h2>
  <p1>
The aim is to create a model that helps the users to apply machine learning approach to predict the satisfaction level. Here, the models used are
<ul>
  <li>Logistic Regression</li>
  <li>Naive Bayes</li>
  <li>KNN</li>
  <li>Decision Tree</li>
  <li>Random Forest</li>
  <li>AdaBoost</li>
</ul>
  </p1>
  
  
 <h2>   
  Conclusion
 </h2>
<p1>
<ul>
  <li>Time taken is maximum for Random forest and minimum for Naive Bayes</li>
  <li>Accuracy is maximum for Naive Bayes and minimum for KNN</li>
</ul>
  <table>
  <tr>
    <th>Model</th>
    <th>Accuracy</th>
    <th>Time taken</th>
    
  </tr>
  <tr>
    <td>Logistic Regression</td>
    <td>84%</td>
    <td>0.05</td>
    
  </tr>
  <tr>
    <td>Decision Tree Classifier</td>
    <td>83%</td>
    <td>0.011</td>
    
  </tr>
  <tr>
    <td>Random Forest</td>
    <td>89%</td>
    <td>0.13</td>
    
  </tr>
  <tr>
    <td>Naive Bayes</td>
    <td>91%</td>
    <td>0.009</td>
    
  </tr>
  <tr>
    <td>KNN</td>
    <td>60%</td>
    <td>0.01</td>
    
  </tr>
  <tr>
    <td>ADA Boost</td>
    <td>71%</td>
    <td>.069</td>
    
  </tr>
  </table>
  <ul>
  <li>
  Comparing Naive Bayes is the best from among the models trained to predict the accurate result with an accuracy of 91% and time taken to execute is 0.009
  </ul>
  </li>

</p1> 


</html>
 
  

