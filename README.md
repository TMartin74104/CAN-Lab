# HRE Lab 4 - Virtual CAN

This lab is designed to introduce students to some of the basics of a Controller Area Network (CAN) interface. Students will use a virtual CAN simulator to understand how a CAN network functions and some of the challenges reverse engineering it.

## Required Equipment
* Linux Machine (barebone OS or VM)

## Assignment

On a Linux machine, students should set up the Instrument Cluster Simulator for SocketCAN (links for setting up are in the Resources section below). Students should then play around with the simulator to get familiar with some of the tool's capabilities. Finally, students should write a readme report answering the following questions and discussing what they learned. Write 3-5 sentences for each question.

### Questions/Findings
1. Explain some of the ways to capture/manipulate CAN traffic with ICSim. How are they useful?
2. In general, what are CAN identifiers used for and how does the numbering scheme work (explain arbitration)?
3. Attempt to find the identifier for one or more of the different outputs on the display (ex. speedometer). Why do you think the identifier corresponds to the output? If you can't, why not?
4. Can you transmit false data and get the output to display? If not, explain how one would go about transmitting false data to something like the speedometer.
5. Explain why reverse engineering a CAN network is difficult. How could a tool like this be improved to help reverse engineering capabilities?
6. If you were hacking a vehicle, how would you access a vehicle's CAN bus?

### Research
Using your experience during this lab, in class discussion, and external sources, how would you, in general, evaluate the security of CAN? Would you say it is secure? Are there changes or improvements that you would recommend be implemented? (2-3 Paragraph Discussion)

---

## Requirements & Deliverables
* Lab report including:
  * Answers to all of the questions
  * Supporting screenshots and/or pictures and files


## Timeline & Submitting Work
* For full credit on this lab, a well-documented write-up must be submitted by **11:59PM Friday, March 19th, 2021**.

## Resources
* [ICSim GitHub Page](https://github.com/zombieCraig/ICSim)
* [InfoSec Newspaper Lab for ICSim](https://www.securitynewspaper.com/2018/05/03/hack-car-tool/)
* [Automobile Networks and CAN Slides](/Lectures/14_Automobile_Networks_and_CAN.pdf)
