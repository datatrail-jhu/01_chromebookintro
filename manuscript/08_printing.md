# Chromebook security

In some ways a Chromebook provides some security for you. Chrome OS has a number of [security features](https://support.google.com/chromebook/answer/3438631?hl=en) that are constantly being improved by Google. We will discuss updating your Chromebook in a later section, but the updates ensure that at a basic level your Chromebook will have good security features. For example, data wil be encrypted when passing through a web browser and each browser window will be sandboxed so a web app open in one browser window can't access data from another window. 

But there are still some steps that you can take to make sure that your Chromebook is secure. This will be particularly important if your Chromebook is lost or stolen, but will also be useful if you share your computer with family or friends. Since a data scientist is often working with data that may be private or sensitive, it is important that if they lose their computer, they don't risk losing the data they are working on. Setting your Chromebook up to be secure from the start is an important step for any data scientist. 


### Setting your Chromebook password

One of the most important parts of securing your Chromebook is making sure that you have a good password. Good passwords are long, easy for you to remember, but hard for other people to guess. Don't use simple passwords like "12345" or "password", don't use your name, your date of birth, or other details that would be easy to guess if someone saw your Facebook profile. 

Good passwords have a few important characteristics:

1. They are long, ideally more than 10 characters
2. They are easy for you to remember. 
3. They are not a commonly used password. 

One way to create relatively good passwords is to string together four or five random words. This approach was made popular by an xkcd cartoon. For example a password made with this approach would be "bikerainsmellblue". This passowrd has more than 10 characters, is easy for you to remember, and is unlikely to be used by a lot of other people. Try to pick words that aren't related to each other. Then you only have to remember the four words to remember your password. 


![xkcd suggested a good password combines four random words.](images/07_chromebook_security/07_chromebook_security-2.png)


Another way to create a password is to choose a line from a book or movie and choose the first one to three letters of each word. For example, you might use the line "Once upon a midnight dreary, while I pondered, weak and weary, " then you could change that to "onupamiddrwhipoweanwe". You can then just remember the line that you have chosen and the fact that you used a certain number of letters from each word. Again, its a good idea to pick a line from a poem or a book that is less famous to do this. 

You can improve either of those password schemes by capitalizing some letters or turning words like "too" into numbers to make them more unique. The key is just to have a password that is not very common, easy to remember, and would be hard for other people to guess. 


### Requiring password to wake from sleep

Now that you have set a good password you can make your Chromebook more secure by making sure that anyone will have to use the password to log in. To do this you need to again open up your personal settings by clicking on your personal avatar in the bottom of your screen and then click on the gear to open your personal settings.

![Open your personal settings](images/07_chromebook_security/07_chromebook_security-3.png)

Once you have your personal settings open you can click on the "Screen Lock" settings.

![Open the Screen Lock settings.](images/07_chromebook_security/07_chromebook_security-4.png)

You'll be required to input your (hopefully good!) password. 


![Input your password.](images/07_chromebook_security/07_chromebook_security-5.png)

Then you can turn on screen lock by clicking the option in the upper right hand corner of the screen for "Show screen lock when waking from sleep". 


![Input your password.](images/07_chromebook_security/07_chromebook_security-6.png)


Now if you close your Chromebook, put it to sleep, or log out, you will have to input your password to get access to your account. This will prevent other users from getting access to your Chromebook account even if they get ahold of the physical device.

### Two step verification

If you are dealing with very sensitive data or want to be more secure about who can access your account, you can turn on two step verification. All this means is that you can set it up so that entering your password is not enough to unlock your computer. You will also need to get a text message to your phone with a special code each time that you log in. This means that even if someone gets ahold of your Chromebook, they would also have to have your phone to be able to log into your account. Two step verification is often required for data scientists working in industry and is a good idea to prevent loss of your account information. 

To turn on two step verification first go to the website https://www.google.com/landing/2step and click on "Get Started" in the upper right hand corner of the screen. 

This will take you through the 


### Managing apps and devices


### Slides and Video

![Updating Your Chromebook](https://youtu.be/UDYbOEp8Y3s)

* [Slides](https://docs.google.com/presentation/d/1-nW4KgJOVcfbRx4Vot_x6ZgoQGFItIxqIHZBXtLHDr8/edit?usp=sharing)

{quiz, id: quiz_07_chromebook_security}

### Chromebook security quiz

? TRUE/FALSE: You will always have to manually update your Chromebook. Otherwise, it will not update.

a) TRUE
B) FALSE

? TRUE/FALSE: Manually updating your Chromebook can be done in a couple simple steps.

A) TRUE
b) FALSE


{/quiz}

