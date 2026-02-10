# Guide To CTF - By Matthew


## Contents
- [Introduction](#introduction)
- [What You'll Learn](#what-youll-learn)
- [Getting Started](#getting-started)
- [Useful Websites](#useful-websites)
- [Your First Puzzle](#your-first-puzzle)

<hr>

## Introduction



**PicoCTF** is a beginner-friendly **Capture The Flag (CTF)** platform designed to teach **cybersecurity fundamentals** through hands-on puzzles. In a CTF, participants solve challenges to uncover hidden **flags**, which are strings of text that confirm a successful solution.

<Strong>Example</strong> of a flag: 'guideToCTF{tH1s_c0uld_b3_a_f1ag_2jg95asn}'.
Flags are unique identifiers for each puzzle, and are complex to stop you from guessing them in a competition.
They are designed to stand out from normal code or language, so that you know when you have found it.
Sometimes, they are encrypted in a cipher so that you won't notice it straight away!

This repository introduces you to **real-world security concepts** by encouraging you to **analyze problems, experiment with tools, and think critically** like cybersecurity professionals.
<hr>

## What You'll Learn

<ul>
  <li><strong>Linux command line basics</strong> and file system navigation</li>
  <li><strong>Cryptography fundamentals</strong> such as encoding, hashing, and simple ciphers</li>
  <li><strong>Web exploitation concepts</strong> including HTML, JavaScript, and HTTP requests</li>
  <li><strong>Reverse engineering basics</strong> and program analysis</li>
  <li><strong>Introductory binary exploitation</strong> and memory concepts</li>
  <li><strong>Problem-solving and debugging strategies</strong> used in cybersecurity</li>
</ul>

CTF challenges emphasize <strong>hands-on learning, persistence, and creative thinking</strong>. No prior knowledge or experience is required to compete in competitions- you just need to be motivated to learn.
<hr>

## Getting Started

The first thing you'll need to start is a PicoCTF account. All you need to do is navigate to <a href='picoctf.org'><strong>picoctf.org</strong></a> and sign up for an account. There are a few questions you need to answer, e.g. what school you're at or what grade you are.
Once you have done this, it is a good idea to bookmark this site in your browser. Use *CMD+D* on Mac or *CTRL+D* on Windows.
Click on <strong>PRACTICE</strong> at the top or go to <a href='picoctf.org/practice'><strong>picoctf.org/practice</strong></a>. This part of the website is called the *Pico Gym*, or practice section. It is where you can find all the puzzles you will be trying to solve for practice. In a competition, the puzzles will be new and different to these puzzles. Most puzzles on the site are from previous year's competitions.

<hr>

## Useful Websites
(*You could bookmark these! Also, keep an eye out here in case I add more websites*)

<ul>
  <li><a href='cyberchef.org'><strong>cyberchef.org</strong></a>
  
  This website can be used to *decode or decrypt* some multi-layer ciphers and encrypted messages. 
  I use it mainly for the **Base64 decode** feature which is what most of the codes in PicoCTF are encrypted in.</li>

<details>
  <summary>Challenge</summary>
  Find out what this means:
  TmljZSBXb3JrIQpJZiB5b3UgY29tcGxldGUgYWxsIDEwIGNoYWxsZW5nZXMgaW4gdGhpcyBndWlkZSwgYSBzZWNyZXQgbWVzc2FnZSB3aWxsIGJlIHJldmVhbGVkLg==
</details>

  <li><a href='primer.picoctf.org'><strong>primer.picoctf.org</strong></a>
   
  This is part of PicoCTF, you can find it by going to PicoCTF then click learn, then Pico Primer.
  It is a helpful documentation for a range of useful information such as linux shells, python, web exploits, cryptography, C language and other things.
  If this sounds confusing, you can just skip over most of the topics and use this as a reference point.
  For some puzzles I might attach a recommended section in the Primer (like ***PRIMER 4.3***) to show what the puzzle is about and some extra info.
  </li>
  <details>
  <summary>Challenge</summary>
  Find this letter:
  The first letter in the title of section 2.4 in the Primer. If you visit the website, you should be able to see the different sections labeled 1.0, 1.1, 1.2 etc.
</details>


<li><a href='https://overthewire.org/wargames/bandit/'><strong>overthewire.org/wargames/bandit</strong></a>

This is a game that teaches you **UNIX**/**LINUX** terminal commands. You have to open it in your computer's terminal, which is called *Terminal* on Mac and Linux, or *Powershell* or even *Command Prompt* depending on your windows version. Unfortunately you can't play it on the website. If your terminal is blocked on your device by an administrator, e.g. a school laptop or work laptop, you may not be able to play this game.
  
  
  </li>
  <details>
  <summary>Challenge</summary>
    
  Linux is often described as *"_____-like"* and uses commands such as `ls` and `cd`. Fill in the blank, then use the first letter.
  
</details>
</ul>

<hr>

## Your First Puzzle

We'll start things off with a fairly easy puzzle. In the picoGym, search for *'Inspect HTML'* or go to <a href='https://play.picoctf.org/practice/challenge/275?page=4'>*Inspect HTML - PicoCTF*</a>. You should see a screen like this:

<img width="416" height="325" alt="Inspect HTML" src="https://github.com/user-attachments/assets/02dc41fb-29e4-486c-b179-6aa4947b7c62" />

###### (!) Note that there is a green tick in the top right. This is because I have solved this puzzle before. When you solve this puzzle, a green tick will appear for you as well.

Select '*Launch Instance*' to begin the challenge. Most challenges will also have this button, but some will not.
Launching the instance just means that a Pico puzzle will be hosted on a new website just for you and your computer. No-one else can access it. Puzzles that use this feature are generally to do with websites, rather than files or downloadable content.

<hr>
