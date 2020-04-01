---
layout: post
title: The importance of minimum security
date: 2020-04-01 20:00:00 -0200
categories: en security
---
Today I will talk about small actions, big impacts and passwords. I warn you, I'm going to push at open doors here.

## The password example
Let's take a simple example : a bad guy with a black hat wants to have access to all your social media accounts.

Often, the minimal length for a password is 8 characters. Let's take a look :
```
Only letters in lower case:
26^8 = 208 827 064 576 possibilities

Lower and upper cases:
52^8 = 53 459 728 531 456 possibilities

52^8 / 26^8 = 256
```
So the number of possibilities has been multiplied by 256, just by using upper letters in our password, which does not delight our black-hat hacker.
As the `^n` shows, the difficulty to crack the password increase exponentially. And I am just talking about 8-characters passwords with lower and upper case. If you add numbers, special charaters, and increase the length, your password will be almost unbreakable. Moreover, having single-use passwords reinforce the security, because this work has to be done for each account.

Obviously, this is just an example. If someone **really** wants your password, he will not spend weeks cracking it...

![xkcd: Security](https://imgs.xkcd.com/comics/security.png "xkcd: Security")

You should also bear in mind that a secure password is [easy to remember, hard to guess](https://en.wikipedia.org/wiki/Password_cracking#Easy_to_remember,_hard_to_guess).

## Risk
It is possible to generalize what I said before in a exponential curve following the equation `y=(1/2)^x`:

![Risk curve](/pics/risk_curve.png)

The main property of exponential curves is that they are not linear. Therefore, a variation on the X axis will not create the same one on the Y axis .

If the majority of people were in the second half of this curve, many security flaws could be avoided.

There is also somthing which I have not told yet: the common passwords. We are in 2020, man is able to walk on the Moon since more than 50 years, and the most hacked password is [123456](https://en.wikipedia.org/wiki/List_of_the_most_common_passwords) (in front of 'password' since 2013!). Just using a passphrase which is not in the top 500 of most hacked passwords is already a huge step into security.

I see risk as 2 components : difficulty and cost. 

![Risk scheme](/pics/risk_stickman.png)

To illustrate, choosing a weak password and applying it to all your social media accounts is choosing the low difficulty, but the high cost (a lot of bad things will happen if the black-hat guy found it...). The most secure way to create a password seems to be choosing the high difficulty, low cost way (a different and strong pass for each website).

Passwords managers can look great, but all your secrets rely on a master password. You have to be confident in its robustness if you want to reduce the cost and difficulty factors (*[pass](https://www.passwordstore.org/) for the win !*). Of course, using [multi-factor authentification](https://en.wikipedia.org/wiki/Multi-factor_authentication) plummet the cost factor.

## Last word
Of course, I'm talking about theorical security : password cracking etc. Techniques like [social engineering](https://en.wikipedia.org/wiki/Social_engineering_(security)) are not taken into consideration here.

On the paper, being a minimum protected is not so hard. Most of the time, it is a problem of time. Security is put aside because it is faster to have the same password everywhere. Easy to remember, frequently easy to guess too. But it is like the seatbelt : it is useless as long as you don't have an accident.

Obviously, nothing can replace the lack of good security behavior online, except training and awareness. In security as in life in general, small actions can have huge impacts.

*A reaction ? Something's wrong ? [Tell me](https://eze-kiel.github.io/contact/) !*