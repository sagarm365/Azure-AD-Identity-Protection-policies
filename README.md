# Azure-AD-Identity-Protection-policies

# Sensitivity-Labels
Create a sensitivity label called Business Sensitive. Auto Apply if US Bank account number is used

<h2>Description</h2>
Project consists of a creating a Sensitivity Label. Use Sensitivity labels that you want to make available for apps and other services. Sensitivity labels from Microsoft Purview Information Protection let you classify and protect your organization's data, while making sure that user productivity and their ability to collaborate isn't hindered. In this practical, it is auto applying for sensitive data i.e. US Bank Account number.
<br />


<h2>Environments Used </h2>

- <b>Microsoft Purview Compliance Portal</b> 

<h2>Prerequisites</h2>

-<b> Sensitivity labels can be created or modified by anyone assigned the following roles:
 - Sensitivity Label Administrator
 - Compliance Data Administrator
 - Compliance Administrator
 - Security Administrator
 - Global Administrator
 </b>
- <b> Licenses: Microsoft 365 Enterprise E3 or E5 SKUs, or Microsoft 365 Business Premium SKU</b>


<h2>Program walk-through:</h2>

<h3>Steps: </h3>

1.	Compliance portal (Purview) --> Information Protection --> ‘ +Create a label’
2.	Give a Name , Description --> Next
3.	Select ‘Files & emails’ --> choose ‘mark the content of files’
4.	Content marketing (turn on) --> Tick ‘Add a watermark’ --> customize it
5.	Auto labelling for files & emails --> Select ‘Content details’ as ‘Sensitive info types’
6.	Select ‘US bank account number’ as sensitive info types
7.	Add --> Next
8.	Review settings & Finish
9.	Create label --> Done


<h2>Program walk-through:</h2>

<p align="center">
Compliacne portal menu: <br/>
<img src="Info protection menu.png" height="50%" width="50%" />
<br />
<br />
New Create Sensitivity Label: <br/>
<img src="creating sensitivity label.png" height="50%" width="50%"/>
<br />
<br />
Scope of Label: <br/>
<img src="scope of label.png" height="65%" width="50%"/>
<br />
<br />
Protection Settings: <br/>
<img src="protection settings.png" height="65%" width="50%"/>
<br />
<br />
Content Marking: <br/>
<img src="content marking.png" height="65%" width="50%"/>
<br />
<br />
Select US Bank A/c No as Sensitivity Info type: <br/>
<img src="Sensitive info types.png" height="65%" width="50%"/>
<br />
<br />
Review and Finish: <br/>
<img src="Review.png" height="65%" width="50%"/>
<br />
<br />
Result: <br/>
<img src="Result.png" height="65%" width="50%"/>


</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
