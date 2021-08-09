# UIUCTF-2021
Writeups for the UIUCTF 2021 competition. 
First of all would like to congratulate the organizers of the CTF, as this has been one of my favourite CTF's so far.
Very fun and creative challenges, and extremly supportive moderators.

I still very much new to the CTF world and even though I did not solve all the challenges I had aimed for I will be doing writeups for some challenges that in the meanwhile I took the time to solve.

Great description of the competition can be found in the official competition website: <https://uiuc.tf>

I participated in Team FF9 and placed 135 with 659 points.

Any suggestions let me know! Here is my discord *Franfrancisco9 #0105*

List of the categories and challenges I solved:
- meta (the hard ones)
    - [Welcome to UIUCTF'21]()
    - [Join our Discord]()
- osint
    - [OSINT The Creator]()
    - [OSINT The Creator 2]()
    - [Chaplin's PR Nightmare - 1]()
    - [Chaplin's PR Nightmare - 2]()
    - [Chaplin's PR Nightmare - 3]()
    - [Chaplin's PR Nightmare - 4]()
    - [Chaplin's PR Nightmare - 5]()
    - [Chaplin's PR Nightmare - 6]()
    - [Chaplin's PR Nightmare - 7]()
 
List of the categories and challenges I attempeted but did not solved during the competition time:
- osint
    -  [Chaplin's PR Nightmare - 8]()
-jail
    - [phpfuck]()
    - [baby_python_fixed]()
    - [baby_python]()
   
*Note: For every challenge I will present the points they had at the end of the competition (the points are adjusted during the competition according to the number of solves)*

*Note 2: For every challenge I will give my personall evaluation of difficulty*

*Flags in the format uiuctf{...}*

## meta
>Introductory category and just for fun. Usually called sanity.

#### **Welcome to UIUCTF'21 (1 Point)**

First challenge when you entered the competition made for fun as a welcoming text, flag was given in the beautiffull background of the CTF main page:
>uiuctf{secret_pictures}

#### **Join our Discord (1 Point)**

Second challenge was the classic discord one wher the flag is usually in the description of one of the channels, usually the rules one.
>uiuctf{y0u_j01n3d_tH3_dIsCorD!!!}

## osint
>Category that consists in looking online for clues and hints to find the flags

### **OSINT The Creator (50 Points)**
This first challenge was very straightfoward. The description said the following:

>There is a flag on a few of the organizer's profiles. Find it!

By opening one of said profiles we see a "\spoiler" text:

![Image of OSINT The Creator](https://github.com/franfrancisco9/UIUCTF-2021/blob/main/OSINT_Creator.png)

Just click it and we get our flag:
>uiuctf{@b0uT_m3_suppOrT5_maRkD0wN}

### **OSINT The Creator 2 (50 Points)**
For this one I have to admit I complicated way too much.

I thought twitter was too obvious so ended up checking every other possible social media of the creator, even went so far as to pm him for Signal info ahah(sorry :) ).

For context I did that in the first 20 minutes as I was trying to get first blood, then we got the hint that it was twitter only.

Then it was just a matter of doing "CTRL F" with "uiuctf{" and scroll down through twitter until I got a match, and sure thing:
>uiuctf{it5_@_sEcr3t_t0ol_thAT_w!ll_he7p_u$_l@ter}

### **Chaplin's PR Nightmare**
For this sequence of challenges (1 to 8) I will go through the line I followed during the competition.
As an add-on this was by far the best OSINT I have ever did, mainly because there is a story and line you can follow from challenge to challenge making it entertaining as well as ver amusing.

**1:**

