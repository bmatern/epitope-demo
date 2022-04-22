# epitope-demo
This repository contains sample files and instructions for a live PIRCHE and HLA-EMMA demo

# Contents

* "Slides" contains power point presentation, with an introduction to the epitope concepts.
* "CaseStudies" contains the input and output files for PIRCHE and HLA-EMMA analysis
 * You may still interpret the output files if the software is not available at this moment.

# How to Download Demo Files

It is possible to access all of the files directly here on Github, or optionally, you may download the files to your own computer, to open them in Excel or another software.

1) (If you're not already here) Go to the github website in your browser:
[https://github.com/bmatern/epitope-demo](https://github.com/bmatern/epitope-demo)

2) Click the green [Code] button, then Select [Download ZIP]
![image](https://user-images.githubusercontent.com/14239618/164648242-b41971e9-4a4f-4bd1-a874-cd536928958e.png)

3) Extract the .zip file (It might be in your "Downloads" folder) TODO: Get a screenshot in English
![image](https://user-images.githubusercontent.com/14239618/162721359-a25908c1-cc50-45f7-9e4a-102e6d0b9222.png)


# Case-study
(provided by Kirsten Geneugelijk) 

Patient_O., blood group B, is a 34 year old male who is on kidney dialysis for almost 4 years. He is registered on the active waiting list since September 2016. He has the following HLA typing:

`
Patient_O,A*02:01,A*01:01,B*07:02,B*08:01,C*07:01,C*07:02,DRB1*15:01,DRB1*03:01,DQB1*06:02,DQB1*02:01
`

The patient is not immunized, which means that he doesn’t have detectable levels of preformed HLA antibodies. The father of patient O. (Donor O) is willing to donate her kidney to his son, but donor O has blood group A. The HLA typing of donor O. is the following:

`
Father,A*02:01,A*02:01,B*08:01,B*07:02,C*06:02,C*07:01,DRB1*03:01,DRB1*13:01,DQB1*06:02,DQB1*02:02
`

In the meantime the patient O. is still registered on the active kidney transplantation waiting list. At a certain time the patient get two deceased donor kidney offers.

Deceased donor 1 (blood group B) has the following HLA typing:

`
Deceased_1,A*02:01,A*01:01,B*44:03,B*08:01,C*01:02,C*07:02,DRB1*15:01,DRB1*03:01,DQB1*06:02,DQB1*02:01
`

Deceased donor 2 (blood group B) has the following HLA typing:

`
Deceased_2,A*02:01,A*01:01,B*07:02,B*08:01,C*07:01,C*01:02,DRB1*15:01,DRB1*03:01,DQB1*06:02,DQB1*02:01
`

These are the three potential donor strings combined:
`
Father,A*02:01,A*02:01,B*08:01,B*07:02,C*06:02,C*07:01,DRB1*03:01,DRB1*13:01,DQB1*06:02,DQB1*02:02

Deceased_1,A*02:01,A*01:01,B*44:03,B*08:01,C*01:02,C*07:02,DRB1*15:01,DRB1*03:01,DQB1*06:02,DQB1*02:01

Deceased_2,A*02:01,A*01:01,B*07:02,B*08:01,C*07:01,C*01:02,DRB1*15:01,DRB1*03:01,DQB1*06:02,DQB1*02:01
`

Which donor would you prefer to use for this kidney transplantation: a living donor or a deceased donor? Calculate PIRCHE and EMMA scores for each donor to help you make a decision. 

# How to register for PIRCHE

We have created temporary accounts to use PIRCHE during EFI 2022, you should have received an email inviting you to join Ben Matern's Laboratory in PIRCHE.com.

![image](https://user-images.githubusercontent.com/14239618/162724397-9c26a848-fc17-4f4b-a6f9-8f2d90b31599.png)

Please change your password. 

If there are troubles creating the account
* We can try to resolve it
* If it is a larger issue, the PIRCHE analysis output files are also provided in [this repository](https://github.com/bmatern/epitope-demo/tree/main/CaseStudies/SolidOrgan_1)

# Analysis in PIRCHE 

1) Login at the [PIRCHE Website](http://www.pirche.com)
![image](https://user-images.githubusercontent.com/14239618/164643044-a9509ad8-067c-4787-b7dd-5cba19a8fce8.png)

2) In the home page, choose "SOT" (solid organ transplantation) option (top right screen), then select "Single Patient":
![image](https://user-images.githubusercontent.com/14239618/164647747-c53505e8-a246-43e8-94f8-dedfc00a88fc.png)

3) For both Patient and Donors, push the [dna/ser] button to switch to "dna", because our HLA genotypes are DNA-based, not Serological types.
![image](https://user-images.githubusercontent.com/14239618/164646914-650bc0f8-e9c3-4812-bf9f-6d0dfe798d44.png)

4) For the Patient, and then the Donors, Copy-paste the patient and donor HLA strings from the Case Study above into the "Input Wizard" fields: <img width="1271" alt="image" src="https://user-images.githubusercontent.com/18530731/159691608-0046f9d6-4e14-43bc-9499-753007b5750c.png">
 
5) Analyze your results.... 

# Analysis in HLA-EMMA

1) https://hla-emma.com/

2) Download the software

3) Install it in Windows

4) Do the Analysis and interpret the results

What if you don't have a Windows computer?

* Output files for HLA-EMMA are provided in [this repository](https://github.com/bmatern/epitope-demo/tree/main/CaseStudies/SolidOrgan_1)
