# UIUCTF-2021
Writeups for the UIUCTF 2021 competition. 
First of all would like to congratulate the organizers of the CTF, as this has been one of my favourite CTF's so far.
Very fun and creative challenges, and extremely  supportive moderators.

I am still very much new to the CTF world and even though I did not solve all the challenges I had aimed for I will be doing writeups for some challenges that in the meanwhile I took the time to solve.

A great description of the competition can be found on the official competition website: <https://uiuc.tf>

I participated in Team FF9 and placed 135 with 659 points.

Any suggestions let me know! Here is my discord *Franfrancisco9 #0105*

List of the categories and challenges I solved:
- meta (the hard ones)
    - [Welcome to UIUCTF'21](https://github.com/franfrancisco9/UIUCTF-2021/blob/main/README.md#welcome-to-uiuctf21-1-point)
    - [Join our Discord](https://github.com/franfrancisco9/UIUCTF-2021/blob/main/README.md#join-our-discord-1-point)
- osint
    - [OSINT The Creator](https://github.com/franfrancisco9/UIUCTF-2021/blob/main/README.md#osint-the-creator-50-points)
    - [OSINT The Creator 2](https://github.com/franfrancisco9/UIUCTF-2021/blob/main/README.md#osint-the-creator-2-50-points)
    - [Chaplin's PR Nightmare Challenges](https://github.com/franfrancisco9/UIUCTF-2021/blob/main/README.md#chaplins-pr-nightmare)
        -[Number 1]()
        -[Number 2]()
        -[Number 3]()
        -[Number 4]()
        -[Number 5]()
        -[Number 6]()
        -[Number 7]()
        -[Number 8]()
        
-jail
    - [phpfuck]()
    - [baby_python_fixed]()
    - [baby_python]()
   
*Note: For every challenge, I will present the points they had at the end of the competition (the points are adjusted during the competition according to the number of solves)*

*Note 2: For every challenge, I will give my personal evaluation of difficulty*

*Flags in the format uiuctf{...}*

## meta
>Introductory category and just for fun. Usually called sanity.

#### **Welcome to UIUCTF'21 (1 Point)**

The first challenge when you entered the competition made for fun as a welcoming text, the flag was given in the beautiful  background of the CTF main page:
>uiuctf{secret_pictures}

#### **Join our Discord (1 Point)**

The second challenge was the classic discord one where the flag is usually in the description of one of the channels, usually the rules one.
>uiuctf{y0u_j01n3d_tH3_dIsCorD!!!}

## osint
>Category that consists in looking online for clues and hints to find the flags

### **OSINT The Creator (50 Points)**
This first challenge was very straightforward. The description said the following:

>There is a flag on a few of the organizer's profiles. Find it!

By opening one of the said profiles we see a "\spoiler" text:

![Image of OSINT The Creator](https://github.com/franfrancisco9/UIUCTF-2021/blob/main/OSINT_Creator.png)

Just click it and we get our flag:
>uiuctf{@b0uT_m3_suppOrT5_maRkD0wN}

### **OSINT The Creator 2 (50 Points)**
For this one, I have to admit I complicated way too much.

I thought Twitter was too obvious so ended up checking every other possible social media of the creator, even went so far as to pm him for Signal info Ahah(sorry :) ).

For context I did that in the first 20 minutes as I was trying to get first blood, then we got the hint that it was twitter only.

Then it was just a matter of doing "CTRL F" with "uiuctf{" and scroll down through Twitter until I got a match, and sure thing:
>uiuctf{it5_@_sEcr3t_t0ol_thAT_w!ll_he7p_u$_l@ter}

### **Chaplin's PR Nightmare**
For this sequence of challenges (1 to 8) I will go through the line I followed during the competition.
As an add-on, this was by far the best OSINT I have ever did, mainly because there is a story and line you can follow from challenge to challenge making it entertaining as well as very amusing.

Also, this allowed me to actually go through the entire challenges without checking the descriptions of each one, just by following the hints, truly amazing!

#### **1:**
This challenge introduces the story!
>Charlie Chaplin has gotten into software development, coding, and the like... He made a company, but it recently came under fire for a PR disaster. He got all over the internet before he realized the company's mistake, and is now scrambling to clean up his mess, but it may be too late!! Find his Twitter Account and investigate!

So we need to look for an account of CC that is related to coding and software on Twitter.

By searching on people for "Charlie Chaplin Coding" we immediately hit jackpot:

![Image PR 1](https://github.com/franfrancisco9/UIUCTF-2021/blob/main/PR_1.png)

Scroll down a bit and we see a tweet that has the following:
>A list of my favorite things
>1. Lists
>2. /lists
>3. Twitter
><3
And with a reply:
>Check out my other lists

Hmmm, suspicious, let's check these famous lists.
There we find a "Super Comedic Code" list where we have our first flag:
>uiuctf{pe@k_c0medy!}

#### **2.**
For the next challenge, I just followed the youtube link at the twitter bio which opened a classic old video of Charlie Chaplin in an IBM ad (I recommend you to watch [it](https://www.youtube.com/watch?v=LniQBHja9bw)).

By minute 0:57 we notice in red the flag below the IBM symbol! Jackpot!
>uiuctf{ch@plin_on_th3_tV!!}

#### **3.**
On the video description, there was a note about checking the website on the channel, so we went to the "about" section and got a link to a very fancy website:

![PR3](https://github.com/franfrancisco9/UIUCTF-2021/blob/main/PR_3.png)

Now for the sake of the length of this writeup I won't go about the contents of the entire website, although they are worth it, as it certainly took a lot of time and dedication, so [here](https://www.charliechaplin.dev) is the link if you want to check it out.

On the main page; you have a section with pictures of Charlie Chaplin that you can swipe. If you zoom on the second one you see our next flag hidden in the computer monitor!
>uiuctf{ch@pl1n_i5_eL337}

#### **5.**
Here I did not follow the proposed order, because as mentioned I was not even checking the descriptions and just following the natural flow of the overall setup.

In OSINT challenges you should always check for hidden links/information everywhere!

In the "About Us" section you could press an image of "Charlie Chaplin with cane", redirecting you to an Imgur account. Hmmm, that smels like another flag to me.

By clicking on the account name we would see two other photos, of Charlie Chaplin and the police (adequate since he seems to have released some bad files). Here it is for fun just because it is actually really funny:

![PR5](https://github.com/franfrancisco9/UIUCTF-2021/blob/main/PR_5.png)

In the one called "Charlie Chaplin Busted by Police" the comment had our flag:
>Charlie Chaplin Busted by Police

#### **4.**
Done in the wrong order but that was part of the fun of it. 

After the Imgur flag, I decided to go and finish analyzing the website.

Sure enough, in the "Contact" section there was a very suspicious form, so obviously, as a good OSINT investigator, I just filled it randomly to see if we had any luck.
Sure enough:
>uiuctf{w3_d0_nOt_v@lu3_yoUR_1nPuT}

#### **6.**
At the end of the same page of the form in challenge 5 we see the following:

>You can also find us on Linkedin, but you will have to search for us I forget what our name is, either like >"Charlie Chaplin Coding or Development" or "C3D" something like that.

Alright, so let's open Linkedin and search for that account and try some combinations:

>"Charlie Chaplin Coding or Development" - nothing
>"C3D" - nothing
>"Charlie Chaplin C3D" - nothing
>"Charlie C3D" - Bingo!

![PR6](https://github.com/franfrancisco9/UIUCTF-2021/blob/main/PR_6.png)

A quick scan and we see that he has some activity to check out.

Hosting an event, but nothing interesting there. But next the following comment:

>Had a great time at the event that I ran a few days ago.
>I hope everyone liked their top hats :)

Checking the experience we see that the event is called "Top Hat Development Night".

We search for it and there it was!
>uiuctf{pr0f3s5iOn@l_bUs1n3sS_envIroNm3n7}

#### **7.**
For this one, I checked the description which mentioned GitHub, hopefully not too many Charlie Chaplin's there.

Luckily we see that there is a Charlie Chaplin Dev account (same name as the Linkedin use, everything connected :))

![PR7](https://github.com/franfrancisco9/UIUCTF-2021/blob/main/PR_7.png)

Opening "C3D-Official" repository I immediately checked the commits.

We first have a security.txt that was deleted let's check out the contents:

>If this computer has a vulnerability, email me at charliechaplin.dev@gmail.com please thank

Ok, an email let's save that for later.

Further down we see "Ok phew resolved issue #3". So we need to check this issue, by clicking on #3. 

There we see a very dramatic message with the flag.
>KEY KEY KEY BAD BAD BAD COMPANY KEY RELEASED BAD BAD BAD
>WHAT DO I DO DELET DELET DELETE
>uiuctf{th3_TrUe_pR_N1gHtm@r3}

#### **8.**
So this last one was all-around what we could take more from that email we found earlier! I did not solve this during the competition time, unfortunately. Nonetheless, I learned a lot about very nice tools for OSINT as well as a very creative way to hide flags! (All of the above are worth 50 points this one ended up with 88)

[This](https://tools.epieos.com/email.php) site allows you to get info about any email!

If we input the found email we find very curious google information:

![PR8](https://github.com/franfrancisco9/UIUCTF-2021/blob/main/PR_8.png)

So it seems the Google ID associated with this gmail has been used in Google Maps to make a contribution (which means a picture of some area). By going to the link given we see an image in Montrose Beach with a flag on it!
>uiuctf{b0rk_b0rk_1_lOv3_mY_d0g<3}

Now, this was very interesting, because it never occurred to me the concept of Google ID.

In the end, this was with no doubt the best OSINT set of challenges so far, from the storyline to the sheer creativity throughout the challenges, it was an all-around amazing experience!






