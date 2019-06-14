# Introduction
<ul>
    <li>The aim of this challenge is to <b>identify dangerous trips</b> by bookingID, based on various telematics data. </li>
    <li>My approach to this challenge is to use a <b> Supervised Learning Machine learning algorithm.</b></li>
    <li>The algorithm will utilize <b>Euclidean distance</b> to compare with training data to determine the nature of each trip</li>
</ul>

# Methodology
<ol>
    <li>Read Training Data into a dataframe and read all telematics data associated with it.</li>
    <li>Store each trip as a "trip" object in a dictionary, with key being bookingID and value being the object.</li>
    <li>For each trip in the raw data, compare against all trips in the training data and retrieve the trip that has the highest similarity based on Euclidean Distance (ie. which point in the training data is most similar to the trip in the raw data)</li>
    <li>If the highest similarity is above a threshold, it is deemed to be similar to a dangerous trip and thus has a high probability of being dangersous as well</li>
</ol>

# How to use script
<ul>
    <li>Scipt should be placed in the same directory as the training data and raw data.</li>
    <li>Training Data should be placed in a "Training File" folder and raw data placed in a "Raw Data" folder.</li>
    <li>All cells in the Script Jupyter Notebook should be run</li>
    <li>Final Output will be placed in the same directory </li>
</ul>

# Conclusion
<ul>
    <li>Given more training sets, the model is better able to find other trips which are dangerous as well </li>
    <li>More research could be conducted to find a more suitable threshold </li>
</ul>
