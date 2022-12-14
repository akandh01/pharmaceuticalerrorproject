 # Pharmaceutical Error Project 
 
 ## Medication Scanner Prototype 

## Project Background 
The three most common pharmaceutical errors are dispensing an incorrect medication, miscalculating a dose and failing to identify drug contraindications and interactions. These errors are likely caused by health care providers and the patients themselves. Due to this, an estimated 30 to 50 million prescriptions are filled incorrectly every year. These human errors can cause serious health issues for children under the age of 5 and the elderly. 

## Project Statement
This project will work to study the behaviors and routines of pharmacies and patients to determine how often pharmaceutical errors occur, which will consequently aid in finding a solution to the issue.

## Goals
To develop an AR prototype that is capable of scanning, taking a photo, counting, reading or interacting with prescription bottles using a QR code, barcode or container shape. In addition, to also creating a prototype that is capable of decreasing the amount of dosage miscalculations and overall pharmaceutical errors. 

## Target Audience 
The demographic most effected by pharmacy errors are children under the age of 5 and the elderly. Therefore, parents, healthcare workers and people who to take medication should be included in this study.

## Competitors
  ### Express Scripts
This app allows you to set up medication reminders and refill your prescription all in one. In addition, your health insurance can be connected so that you can track and and order your prescriptions all in one. 
  ### MyTherapy
Can track medication intake and overall mood and health. Can record symptoms and personalized tips for your treatment. Provides a health record that can be shared with your doctor to see where your health needs to be improved. 

## Interviews 

### Interview Questions 
* **How many times a month do you pick up a prescription from the pharmacy?**
- Have you ever had any issues with your prescription?
- What form of medication do you typically use?
- How many times a week do you need to take your medication?
- How long is the wait time at the pharmacy when you pick up your medication?
- Have you ever tried a medication tracking app?
- Have you ever had your medication delivered to your home?
- If there was one feature you wish pharmacies would change or implement what would it be?

## Interview Responses
### Participant 1:Anil
* **Once a month**
- One time they did not give me enough and I had to wait a few days before it could refill, so I didnt have any pills for a few days 
- Tablets and shots
- Daily , twice a day
- Not long prob like 3 min or so
- No, but I order my shots online 
- Yeh my shots 
- ???I mean its normally really quick to pick up my stuff but there could be a machine or something that fills the prescription for you so there's no pharmacist at all and you don't have to deal with anyone touching your stuff???..or you could have a dispenser machine that dispenses your drugs too and use a credit card???

### Participant 2: Shanta
* **Once a month**
- Sometimes they give me a different pill that looks different from the ones I normally take and they dont say anything so then I have to call the doctor and make sure its the right one 
- Tablets 
Once a day
- It depends sometimes it can be really quick if no one is there and if its a lot of people  it could take a few minutes 
- No 
- If its from a pharmacy far away yeh but if its the one right outside I go get it 
- ???I dont know doctors make a lot of mistakes and tablets and bottles come different everytime I go pick it up???.maybe they could double check it or look at it again to make sure its right. Everything is made by hand not machines."

### Participant 3: JonCarlo
* **I dont pick up prescriptions anymore. The only time I have is if I go to CityMD for a one-off illness. Id say maybe 4 or 5 times a year I have to pick up a prescription physically in a pharmacy.**
- Ive had issues with my prescriptions before. Mostly on a the insurance side of things but Ive also gotten the wrong dose of medication and ive also had a prescription that was never filled at the pharmacy so i never just never got that medication.
- The main form of medication I use now are self injectable needles for my Crohns disease. Other than that I mostly have to take ibuprofen for headaches. 
- I need to take my medication once every 8 weeks. But in the past I used to have to take up to 12 pills every morning. 
- When I have ti go to the pharmacy I can usually pick up the medication within the day the medication was prescribed to me. So Ive never waited more than 15 minutes at a pharmacy to pick medication.
- Ive never used a specific app to track my medication but I do use CVS Speciality now and then they let me track pretty much like how you can track an amazon package.
- Yes I get my medication delivered to my home every 8 weeks 
- Id like pharmacies to have a better way of organizing the prescriptions they fill out. Ive seen some medication be lost at the pharmacy or in their system it says they have it but the pharmacist cant find it 

### Participant 4: Priya
* **Maybe once**
- They've changed the way it looks without informing me and also they've refilled it without me calling them first when I had just picked up my medication a week prior 
- Topical creams and pills 
- Everyday, once a day at night 
- Normally its really fast but if someone is holding up the line or they can't find my prescription it can be a few minutes 
- No I just remember 
- Yes when my doctor sent my prescription to a different pharmacy far from my house it had to be delivered 
- I think there should be some sort of system that rechecks the pharmacists handling the medication just to make sure everything is right. Or there could be something that counts it and then the pharmacist just has to give it to the person so no one is handling it. 

## Results Summarized
From the participants interviewed, the following results were analyzed:
* **Pharmacists not telling patients that the physical look of their medication has changed**
- Wrong amount 
- Pharmacist refilling prescription on their own 
- More attention needed to labels and bottles 


## Getting Started: AR Project 

### Prerequisites

This prototype will be created using Unity. Specifically, the AR project setting. To test the prototype, users can use their phones.

### Installing

Follow these steps to create prototype: 

```
Create AR Core project
```
```
Open Build Settings and Switch Platform to IOS or Android 
```
```
Open Player Settings and install XR Plugin Management 
```
```
Select ARKit Plugin
```
```
Import AR Foundations Samples Unity Package and Download ArCore XR Plugin
```
```
In Player Settings set the Bundle ID and set requires ARKit Support and set allow "Unsafe" code
```
```
In Player Settings Add Description Text to Camera and Location Permissions
```
```
Open Basic Image Tracking Scene 
```
```
Open Build Settings and Add Open Scene
```
```
Create Build Folder and Build Xcode Project Files (or Build APK file for Android)
```
```
Attach phone or Ipad to computer
```
```
Add your Apple Account to Team for Unity-iPhone and Unity-iPhone Targets 
```
```
Press Play Button to Build and Install to iPhone or iPad
```
```
Open the AR Foundation App on iPhone
```
```
Open the barcode in the Unity Project and point phone at code
```


## Running the tests

The prototype can be utilized using your Iphone or Android devices. 

```
Use the AR Foundation App to scan the image from the Unity Editor 
```
The prototype is supposed to be able to scan the prescription and pill bottles to tell the patient the quantity, prescription, refill and important infornamtion about the prescription. 

## Prototype Features 
The main features of the prototype are:
* **Scanning medication containers or barcode using phone**
- Counting medication inside using a scan 
- Scanning container for prescription, refills and information


## Deployment
To deploy this prototype on a live system, users must access the cameras on their phone and scan their medication containers. They can do this by using the AR Foundation app. Once scanned, a pop up window would appear on their phones that notifies them of all the infornmation of their medication. 

## Future Development 
While the prototype is still in development, the main objective of this project is for patients to be able to count and recognize the amount of correct medication in the bottle by scanning the container using their phones. In this way, patients have a way of ensuring the correct medication without even having to open the container. Any changes or problems with the prescription would automatically be recognized and from there the patient can contact their pharmacy or health care provider for help. 
The central point of this prototype is to decrease the amount of errors that occur by healthcare workers when distributing and filling prescriptions. By adding another level of security where patients have another outlet to double check their medication, it helps ensure that errors are less prevelant in the healthcare field.
