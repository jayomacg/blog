---
published: false
---

# Tableau BER County Map Dashboard Walkthrough
## 12 Steps
1.	Download Tableau, free 2-week trail available
	
[Tableau Download](https://www.tableau.com/en-gb/trial/tableau-software) 

2.	Download Zip file of BER Public Database 

[BER Public Database Download](https://ndber.seai.ie/BERResearchTool/ber/search.aspx)

3.	Unzip file ( ~ 1 Gb file size )

4.	Open Tableau, on the left pane under Connect to a file, click text file, now find the unzipped BER file and click open.![TableauStep4.png]({{site.baseurl}}/_posts/TableauStep4.png)

5.	Click Update in Tableau and file will go into Tableau. Filtering the data is recommend, this can be done on the top right corner of the Data Source tab ![TableauStep5.png]({{site.baseurl}}/_posts/TableauStep5.png)

6.	In Sheet 1 or any new worksheet, find ( search function available ),drag and drop CountyName group onto middle of screen. ![TableauStep6.png]({{site.baseurl}}/_posts/TableauStep6.png)

7.	There will be errors, to remove errors right Click CountyName and select Geographic role , then select State/Province.![TableauStep7.png]({{site.baseurl}}/_posts/TableauStep7.png)
  
8.	There will be some errors left, to remove the remaining errors, click on the bottom right of the map click on the errors and select edit location ( or right click on Map and select edit location ). Then map the BER area name ( Dublin Postcode, City or County ) to the Tableau recognized county. One complete all errors disappear. ![TableauStep8.png]({{site.baseurl}}/_posts/TableauStep8.png)

9.	On the top right of the screen select Show Me and then select Maps. ![TableauStep9.png]({{site.baseurl}}/_posts/TableauStep9.png)

10.	Now the Map is complete and all the data is ready to be explored, An example below selects the BER rating ( kWh/m2/yr) drags and drops to color under marks and then right click and change from sum to average.![TableauStep10.png]({{site.baseurl}}/_posts/TableauStep10.png)

11.	Result, showing county and average BER value for that county:![TableauStep11.png]({{site.baseurl}}/_posts/TableauStep11.png)

12.	And now for the cherry on top! Edit color on top right, to make the differences stand out. Colored Result:![]({{site.baseurl}}/_posts/TableauStep12.png)
