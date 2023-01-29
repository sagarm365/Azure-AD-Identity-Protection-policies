# Azure-AD-Identity-Protection-policies

Azure AD Identity Protection Policy: User-Risk to All Users High/Sign-In Risk and Allow Require MFA.

<h2>Description</h2>
Project consists of a creating a Risk-based access policies as a part of Azure AD Identity Protection policies. Risk-based access policies, there are two types of risk policies in Azure Active Directory (Azure AD) Conditional Access we can set up to automate the response to risks and allow users to self-remediate when risk is detected: Sign-in risk policy and User-risk policy. In this practical, it is auto applying for High risk level.
<br />


<h2>Environments Used </h2>

- <b>Microsoft Azure Portal</b> 
- <b>Azure AD Identity Protection service</b>

<h2>Prerequisites</h2>

-<b> Sensitivity labels can be created or modified by anyone assigned the following roles:
 - Conditional Access Administrator
 - Security Administrator
 - Global Administrator
 </b>
- <b> Licenses: Azure AD Premium P2, Enterprise Mobility and Security E5 plan</b>


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
