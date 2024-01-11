# WhatsApp_Chat_Analyzer
The **WhatsApp Chat Analyzer** project is dedicated to providing users with a powerful and sophisticated tool for conducting in-depth analysis of their WhatsApp conversations. In an age defined by extensive communication through messaging platforms, this project offers users valuable insights into their chat data. By employing advanced data analysis techniques and compelling visualizations, this application empowers users to uncover meaningful patterns, sentiment trends, and communication dynamics within their WhatsApp conversations.

<h2>Features</h2> 

<h2>1. Data Parsing and Preprocessing:<br></h2>
<li>The project initiates by reading WhatsApp chat data from a specified file using Python's file handling capabilities.</li>
<li>Utilizing regular expressions (regex), it identifies and extracts relevant components such as timestamps, senders, and messages from each chat line.</li>
<li>The extracted data is then structured into a Pandas DataFrame, facilitating easy manipulation and analysis.</li>
<br>
<h2>2. Sentiment Analysis and Emoji Analysis<br></h2>
<li>Sentiment analysis is performed using the TextBlob library, which assigns a sentiment polarity score to each chat message.</li>
<li>A function categorizes messages as positive, negative, or neutral based on the sentiment score.</li>
<li>Another function extracts emojis from chat messages using regex, enabling emoji analysis.</li>
<br>
<h2>3. Data Analysis and Visualization<br></h2>
<li>Various data analysis techniques and visualizations are incorporated to provide insights:</li>
<ul style="list-style:disc;"><li>A word cloud visually represents frequently used words from the combined messages.</li>
<li>Monthly and daily usage charts showcase the volume of messages over time.</li>
<li>An activity map illustrates communication intensity by day and hour of the week.</li></ul>
<br>
<h2>4. Participant Analysis<br></h2>
<li>The application identifies and displays the most active participants based on their message counts.</li>
<li>Participant counts are computed and presented in a clear format.</li>
<br>
<h2>5. User Interaction and Execution<br></h2>
<li>The main function orchestrates the entire process by calling necessary functions and executing the analysis.</li>
<li>Users provide the path to the WhatsApp chat data file, which is then parsed and analyzed.</li>
<li>Analysis results, including sentiment analysis, emoji usage, visualizations, and participant information, are displayed for the user.</li>
<br>
<h2>6. Technologies and Libraries Used<br></h2>
<li>The architecture leverages various Python libraries, including Pandas, NumPy, Matplotlib, and TextBlob.</li>
<li>Regular expressions (regex) are employed for effective data extraction and manipulation.</li>
<li>The architecture is designed to be executed locally, providing users with the convenience of running the analysis on their own machines.</li>

<h1>Screenshot</h1>
![image](https://github.com/Dhruvil03/WhatsApp_Chat_Analyzer/assets/90698427/b81b8eb1-75df-4168-92ea-808e9cd0f6a1)


