The ENTIRE code is in the project-update-1.pynb.

You will see a lot of technical issues when importing modules into code.

I typed the code step by step in the beginning in Google Colab. The training took a lot of time, and I was notified that my usage is limited. So, I had to run the code in a Jupyter notebook in HPRC.

The progress went smoothly until I encountered a wrong result in the prediction of this tweet(Earthquake just hit! Building shaking, people running outside #emergency) as a non-disaster.

That's where something went wrong 

Then I rewrote the entire code and corrected it at the end, resulting in a good outcome. 

These outomes are :

 Tweet: "Forest fire near La Ronge Sask. Canada"
 predicted as Disaster

 Tweet: "On plus side look at the sky last night it was ablaze."
 predicted as Non-Disaster

 Tweet: "13,000 people receive #wildfires evacuation orders in California"  
  predicted as Disaster 

 Tweet: "I swear that jam will set the world ablaze"
 predicted as Non-Disaster
