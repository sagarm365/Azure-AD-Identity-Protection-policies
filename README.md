# Azure-AD-Identity-Protection-policies

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

1. Azure portal --> Azure AD Identity Protection
2.	User risk policy --> select users, set High User risk, set Block access
3.	Sign-In risk policy --> select users, set High User risk, set Allow access (Require MFA)
4.	Done



<h3>Screenshots:</h3>

<p align="center">
User-Risk: <br/>
<img src="user risk.png" height="50%" width="50%" />
<br />
<br />
Result: <br/>
<img src="1.png" height="50%" width="50%"/>
<br />
<br />
Sign-in Risk: <br/>
<img src="sign in risk.png" height="65%" width="50%"/>
<br />
<br />
Result: <br/>
<img src="2.png" height="65%" width="50%"/>
<br />
<br />



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
