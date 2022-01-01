# [Toy Artificial Intelligence lab.](https://ladooniani.github.io/tailab/) 
 
 ![alt text](https://github.com/ladooniani/tailab/blob/master/assets/toy_artificial_intelligence_lab_logo.png)

**Toy Artificial Intelligence\
Research, innovation and technology development\
Intelligent systems and robotics laboratory**

#

![alt text](https://github.com/ladooniani/tailab/blob/master/assets/tai_lab_terbinari_cbm_project_logo.png)

## Terbinari CBM Tet.01 Operating program
 
 ![alt text](https://github.com/ladooniani/terbinari-cbm/blob/main/image/terbinari-cbm-tet-lado-oniani-tai-lab.jpg)
 
 
### ✔️ Content

 - [Software and device](#Software-and-device)
 - [Interface control ](#Interface-control )
 - [NLP semantic analysis methods algorithms](#NLP-semantic-analysis-methods-algorithms)
 - [Commands and functions control](#Commands-and-functions-control)
 - [Functionality](#Functionality)
 - [Research](#Research)

## Software and device

Terbinari operating program represents interactive training and conversation model, natural language processing, understanding and generation syntactic and semantic analysis/matching logic algorithms, and controller operating methods.

Artificial conversational entity performs input/output question-answering, learning, spoken dialog system with multi-function chat-bot interface and anthropomorphic humanoid robot Control Bot Mechanism animatronics operator. The cervical motility device implements mouth speech events motion and eyes/head tracking contact and response under facial detection/recognition process of computer vision.

The bot operates individual unique memory content updated by interlocutor input in frames of the system legal code. The answer defines output for dialogue as a tool of reflective analysis by returning efferent recall from human-like machine cognitive function. Embodies autonomous companion simulator as trainable virtual teaching assistant and agent of compensatory intercourse for various interactive communication tasks.

## Interface control 
 
![alt text](https://github.com/ladooniani/tailab/blob/master/assets/terbinari-tet-cbm-0.jpg)

    • Input text-box
    • Output answer display 
    • TT/TV/VV/EX modes, answer processing type, function, and system message indicator
    • ACD enable/disable
    • "OA On/Off" Output appeal
    • "IC/Close" Voice-to-voice chat conversation tool open/close button
    • "UPD/Save BAC" backup update load button
    • "BAC" backup saving download button
    • "Synch" robot synchronization button
    • "Pipe" module connection button
    • Video device selection 
    • Serial port selection 
    • Speech recognition reference selection 
    • Speech recognition language selection 
    • Detection and recognition tracking monitor
    • Voice-to-voice chat conversation tool
    • Voice-to-voice chat conversation tool system volume real-time value and pass/block indicator 

![alt text](https://github.com/ladooniani/tailab/blob/master/assets/terbinari-tet-cbm-2.jpg)


## NLP semantic analysis methods algorithms

The operated choice between methods occurs at the level of input processing or mode condition and enters into interconnected work under functions control interface. 

### Direct answer chain

The simple and rigidly logical method represents automatic direct question-answer exchange learning and dialog process where the basic principle is output the answer to the question if the answer exists or request the answer to the new question. 

    q1a. q1b. q1c…
    a1a. a1b. a1c...
    q2a. q2b. q2c…
    a2a. a2b. a2c...

To start training and conversation open input window and insert:

    user: how are you? 
    _bot: fine, and you?
    user: perfect
    _bot: what is "perfect"?

  Request indicates that the answer does not exist.
 
    user: just perfect
    _bot: your answer "just perfect" saved 

  Compound of answer to the question saved: 

    user: Perfect
    _bot: Just perfect

  Using ending mark for multiple answer: 

    _bot: what is "perfect"?
    user: just perfect. it is perfect. you are perfect. yes, perfect
    
    user: perfect
    _bot: you are perfect
    user: perfect
    _bot: it is perfect
  
   Getting of new answer to exist question requires asking to request for a new adding to answer/multi-answer for question:   

    user: ask
    _bot: I want to know, how to answer to the question "hello"
    user: hi. whats up. hello. hey
    _bot: if you ask "hello" I answer "hi"

### Definition answer

Returns the answer to the subject with definition about the subject by determination of noun with basic question form: 

    user: true (DAC)
    _bot: true is true       
    user: what is true? (DA)
    _bot: true is condition

### Inverse definition answer

Returns attitude to the subject by inversion of pronoun and adjective content:

    user: What is your favorite color? 
    _bot: My favorite color is green    
    
### Contextual question
 
Answer with link to previous answer context by exist conjunction:

    user: who are you
    _bot: I am your friend              
    user: why?
    _bot: because I like you  
    
### Contextual answer

Provides adding and request method to create and return contextual dialogue node. Adding keyword "ctx" to question opens contextual answer creation sequence:

    user: how to teach "ctx"
    _bot: what to teach?              
    user: answers to questions
    _bot: how to teach?     
    user: insert questions. insert answers
    _bot: why to teach?   
    user: to teach me. to get conversation 

    user: how to teach?
    _bot: Insert answers
    user: what answers?
    _bot: answers to questions

### Vertical stair answer 

Mode-dependent stochastic optimization, including borrowed functions from other methods, and processing with several types of output in case of the "no answer" condition and adding of the new compound is not available. Processing flows by the stair of conditions with incipient step, which counts subject value and looks for containing answers with the context in the compound, while a move to the terminal noun value, otherwise the “answer not found” condition becomes true.

### Output appeal

Outputs questions and answers from existing memory assigned list or random/contextual choice.  

    _bot: mercury temperature is 801 fahrenheit

### Inference root algorithm

Returns the meaning curve of the word or sentence by weighing noun links in the whole memory context. 

## Commands and functions control

### Modes 
                            
- TT (Text to Text) Learning mode
- TV (Text to Voice) Test mode
- VV (Voice to Voice) Conversation mode
- EX (Voice to Voice) Waiting submode

### Mode access state marker

- ⚪ Modes that accesses and processes the current function
- 🟢 Modes that have access to current mode
- 🟡 Limited access to another mode
- ⚫ Unavailability in mode

### Dialog keys

- what is (noun definition)
- you, your, I, my (inverse definition of subject)
- why (contextual answer to previous sentence)
- what, why, how (contextual node)

# Commands

To start conversation and training dialog, request your answer. 

✔️ Note: Use dot to split input into multi-answer/question insert. 

## Modes

### chat
#### Switch chat modes 

TT (Text-to-Text) Training Mode ⚪ TT | 🟢 TV | ⚫ VV | ⚫ EX Initial textual training and conversation chat mode, switch between (Text-to-Text) and TV (Text-to-Voice) Testing Mode 🟢 TT | ⚪ TV | 🟢 VV | ⚫ EX Text-to-Speech voice response and animatronics control display anthropomorphic visualization design of eyes motion computer vision method and viseme animation set according  [System.Speech.Synthesis Namespace SpeechSynthesizer.VisemeReached Event](https://docs.microsoft.com/en-us/dotnet/api/system.speech.synthesis.speechsynthesizer.visemereached?view=netframework-4.8) using Microsoft [System.Speech.Synthesis](https://docs.microsoft.com/en-us/dotnet/api/system.speech.synthesis?view=netframework-4.8) system default Zira and Irina voice reference.

#
### speak 
#### On/Off Voice Mode

"Speak" turn on/off VV (Voice-to-Voice) Conversation Mode 🟡 TT | 🟢 TV | ⚪ VV | ⚫ EX, condition does not allows training and represents only conversation mode. 

✔️ Note: Make sure that your system audio input is of good quality to avoid speech recognition failures.

## Conversation controls 

### tet 
#### Attention
Access: ⚪ TT | ⚪ TV | ⚪ VV | ⚫ EX

 Calling the name to get recall of attention or interrupt current monologue speech during the voice modes:

    user: tet
    _bot: what?

#
### yes 
#### Confirmation to accept condition
Access: ⚪ TT | ⚪ TV | ⚪ VV | ⚫ EX

### no 
#### Confirmation to cancel condition
Access: ⚪ TT | ⚪ TV | ⚪ VV | ⚫ EX

Confirmations to accept or cancel condition:

    user: format 
    _bot: you sure?
    user: yes
    _bot: memory cleared 

#
### stop 
#### Stop conversation. Exit back from 'continue'
Access: ⚫ TT | ⚪ TV | ⚪ VV | ⚪ EX 

To interrupt speech, request "stop" To exit back from "ex" waiting state, say "stop" or "stop and continue". 

    _bot: this documentation presents… 
    user: stop
    _bot: ok 

#
### again 
#### Repeat phrase 
Access: ⚫ TT | ⚪ TV | ⚪ VV | ⚫ EX

To repeat phrase, request "again":

    _bot: this documentation represents… 
    user: again
    _bot: this documentation represents overview of the terbinari system.      

#
### wait 
####  Pause speech 
Access: ⚫ TT | ⚫ TV | ⚪ VV | ⚪ EX

To pause speech, say "wait" EX (Voice-to-Voice) Waiting State. Command interrupts speech and enters program into closed input/output waiting state during voice-to-voice conversation.

    _bot: this documentation represents…
    user: wait

#
### continue 
####  Continue speech
Access: ⚫ TT | ⚫ TV | ⚫ VV | ⚪ EX

### stop and continue 
####  Exit back from 'wait'
Access: ⚫ TT | ⚫ TV | ⚫ VV | ⚪ EX

To exit and continue speech, say "continue" or "stop and continue" without continuation. 

    user: continue
    _bot: …overview of the terbinari system.

## Memory update

### ctx 
#### To add context answer
Access: ⚪ TT | ⚪ TV | ⚫ VV | ⚫ EX

To add contextual node, use keyword "ctx":

    user: how to teach ctx
    _bot: what to teach?
    user: answers to your question
    _bot: how to teach?
    user: insert questions. insert answers
    _bot: why to teach?
    user: to teach me

Request access ⚪ TT | ⚪ TV | ⚪ VV | ⚫ EX:

    user: how to teach?
    _bot: insert answers
    user: what answers?
    _bot: answers to your question

#  
### ask 
####  To get request for answer 
Access: ⚪ TT | ⚪ TV | ⚫ VV | ⚫ EX

Answer or request keyword "ask" for adding to exist single/multi answer/question:   

    user: ask me something
    _bot: I want to know, how to answer question (question)?
    user: some answer
    _bot: ok, if you ask "question" I answer "some answer"

## Memory edit

### format 
#### Format Memory
Access: ⚪ TT | ⚪ TV | ⚫ VV | ⚫ EX

To format memory for default content insert "format" and confirm condition. Formatting removes memory runtime and persistent data.
 
    user: format 
    _bot: you sure?
    user: yes
    _bot: memory cleared 
    user: no
    _bot: skipped 
    user: tet
    _bot: formatting command reset. what?

#
###  remove 
#### Remove last compound 
Access: ⚪ TT | ⚪ TV | ⚫ VV | ⚫ EX

To remove last input, request "remove":

    user: perfect
    _bot: what is perfect?
    user: just perefct (typo or unwonted answer)
    _bot: saved
    user: remove
    _bot: last compound removed (in case of answer or) last input removed (in case of question) 

#
### delete 
####  Delete current compound
Access: ⚪ TT | ⚪ TV | ⚫ VV | ⚫ EX

To remove actual answer compound, insert "delete": 

    _bot: just perefct (typo or unwonted answer)
    user: delete
    _bot: compound removed 
        
👉 Save and upload memory file backup to avoid loss of your original content in case of unexpected shut down or runtime error. Since storing of memory executes with completing of session, this will cause memory reset with default content.

## Requests

###  en/fr/ru 
#### Switch language input language code
Access: ⚪ TT | ⚪ TV | ⚪ VV | ⚫ EX

#
###  Astronomy 
#### Download astronomy questions/answers memory set
Access: ⚪ TT | ⚪ TV | ⚪ VV | ⚫ EX

#
###  time 
#### Time and date
Access: ⚪ TT | ⚪ TV | ⚪ VV | ⚫ EX

#
###  information 
#### Information about Terbinari project, same as "terbinari" with PDF 
Access: ⚪ TT | ⚪ TV | ⚪ VV | ⚫ EX

#
### exit 
####  Close program with confirmation 
Access: ⚪ TT | ⚪ TV | ⚪ VV | ⚫ EX

#
### open chain 
####  Show memory content 
Access: ⚪ TT | ⚪ TV | ⚪ VV | ⚫ EX

✔️ Note: With sequential insertion order request "open chain" first displays DAC second memory chain IRA value matrix keys.
    
## Scenario

### what is your name 
#### Acquaintance
Access:  ⚪ TT | ⚪ TV | ⚪ VV | ⚫ EX

To pass through acquaintance scenario ask for name:  

    user: what is your name?
    _bot: my name is tet. what is yours? (first time)
    user: my name is mark
    _bot: If your name is mark, say (yes), otherwise repeat your name
    user: yes
    _bot: nice to talk to you mark 
    user: what is your name? (second time)
    _bot: my name is tet.
 
#
###  my name 
####  User name
Access:  ⚪ TT | ⚪ TV | ⚪ VV | ⚫ EX

To introduce yourself, input your name:   

    user: my name is inna

During the Vision recognition process, detected face will be associated with this name. Check detection with TT or TV modes and insert your name, then say hello. 

#
### how old are you 
#### Age
Access: ⚪ TT | ⚪ TV | ⚪ VV | ⚫ EX

Ask about the "age":  

    user: how old are you?
    _bot: according to the system time, I am one year old
 
## Tools

### - numb +-/* numb 
#### Request for math calculations
Access: ⚪ TT | ⚪ TV | ⚪ VV | ⚫ EX

To request single mathematical computation, use operators to calculate sums. Calculator designed as an element of dialog flexibility without providing such multiple calculations e.g. if result to computation 2+4+6-10*100 is equal to -988 In case of single computation answer will be 2 plus 4 is equal to 6, 4 plus 6 is equal to 10, 6 minus 10 is equal to -4, 10 multiplied by 100 is equal to 1000 

    user: How much will be 777+ 455 and 120 / 54 and 1898*221 and 5101-3101 (TT/TV)
    _bot: 777 plus 455 is equal to 1232, 5101 minus 3101 is equal to 2000, 120 divided by 54 is equal to 2.22222222222222, 1898 multiplied by 221 is equal to 419458
    user: 777 + 455 (VV)
    _bot:  1232 
 
#
### filter 
#### On/Off Spelling correction filter
Access: ⚪ TT | ⚪ TV | ⚫ VV | ⚫ EX

To turn on/off spelling correction filter, request "filter", which is useful during textual trading In chat mode. 

    user: filter 
    _bot:  spelling correction filter on
    user: hoow olz arx yous (Typo)
    _bot:  in accordance with the current system time, I am 1 year old (Input processed as “how old are you”)

## Vision

### vision 
#### Vision mode On/Off
Access:  ⚫ TT | ⚪ TV | ⚪ VV | ⚫ EX

To assign command for a new request, add access key (c1) in your answer.

    user: open your eyes
    _bot: your question "open your eyes". give me answer
    user: ok c1
    _bot: your answer "ok" saved, assigned to the command key c1
    user: close your eyes
    _bot: your question "close your eyes". give me answer
    user: ok c1
    _bot: your answer "sure" saved, assigned to the command key c1
    user: open your eyes
    _bot: ok. vision on
    user: close your eyes
    _bot: ok. vision off

#
### hi and see 
####  Keywords to get face recognition response
Access: ⚪ TT | ⚪ TV | ⚪ VV | ⚫ EX

    user: hi
    _bot: hello (user name)

#
### clear 
#### Delete recognition data
Access: ⚪ TT | ⚪ TV | ⚪ VV | ⚫ EX

👉 Panel allows you to choose video device and track computer vision.

## Default filters 

### Censor

Does not allows input with various types of information as abusive language, violence, human biological properties, physical relations and basic existential conditions for all parts of memory

#
### Encyclopedic 
Access: ⚪ TT | ⚪ TV | ⚫ VV | ⚫ EX 

Provides minimal information about the subject of input with the subsequent abolition of the function for particular noun after receiving of answer

#
### Power mode note
Access: ⚫ TT | ⚪ TV | ⚪ VV | ⚪ EX 

Visualization and animatronics control requires using of High Performance power plan in Windows 10 OS Control Panel\Hardware and Sound\Power Options

## Persistent data 

Files folder located by path C:\Users\User\AppData\Roaming\Terbinari, which contains haarcascade xml file, "base" sub-folder with face recognition data, and 6 system text documents.

     📄 Taoz1/0 - DAC Memory (Encrypted DAC memory)
     📄 Taoz2/X - IRN Memory (Encrypted IRA memory)
     📄 Taoz3 - RP (System)
     📄 Taoz4 - CP (System)
     📄 Taoz5/Y - Local registration user access key (Encrypted)
     📄 submem - Memory backup 


## Download markdown pdf

📃 [Download pdf](https://)

## 💖 Support project

Your donation will help expand independent research workflow, improve the laboratory environment, and speed up the conceptual strategy process, which leads to more involved research in frames of related technology, forming an educational platform for creative/intellectual collaboration and search for other references.

To support the project follow the donation link: 

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=GRGH6SL9EL72U">
  <img src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif" alt="Donate with PayPal" /><br><br>
</a>

To get updates from research workflow, please follow us on social networks and subscribe to [YouTube channel](https://www.youtube.com/channel/UC0Z161RgR5KpwPLvEDzkk9Q?view_as=subscriber) 

  <a href="https://www.youtube.com/channel/UC0Z161RgR5KpwPLvEDzkk9Q/featured"> <img src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/youtube.svg" alt="Youtube" height="20" style="vertical-align:top; margin:4px"></a>
   <a href=" https://www.facebook.com/terbinari" target="_blank" rel="noopener noreferrer"> <img src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/facebook.svg" alt="Facebook" height="20" style="vertical-align:top; margin:4px"></a>
   <a href="https://www.instagram.com/terbinari_cbm/" target="_blank" rel="noopener noreferrer"> <img src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" alt="Instagram" height="20" style="vertical-align:top; margin:4px"></a>
  <a href="https://twitter.com/ArtificialToy" target="_blank" rel="noopener noreferrer"> <img src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" alt="Twitter" height="20" style="vertical-align:top; margin:4px"></a>
   <a href="https://www.linkedin.com/company/tailab/" target="_blank" rel="noopener noreferrer"> <img src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" alt="Linkedin" height="20" style="vertical-align:top; margin:4px"></a>
   
## Lab

### 🔬 [TAI lab](https://ladooniani.github.io/tailab/) 

<sub>📃 [TAI lab. Terbinari CBM project pdf](https://github.com/ladooniani/tailab/blob/master/docs/tai.pdf)<sub>

<sub>Copyright © 2016-2021 Lado Oniani, TAI Lab. All Rights Reserved<sub>

 
