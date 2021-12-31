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

### Mode state marker

- ⚪ Modes that accesses and processes the current function
- 🟢 Modes that have access to current mode
- 🟡 Limited access to another mode
- ⚫ Unavailability in mode

## Commands

To start conversation and training dialog, request your answer. 

✔️ Note: Use dot to split input into multi-answer/question insert. 

#### Modes

- chat >> Switch Chat Modes. TT/TV

"Chat" TT (Text-to-Text) Training Mode  ⚪ TT | 🟢 TV | ⚫ VV | ⚫ EX Initial textual training and conversation chat mode, switch between (Text-to-Text) and TV (Text-to-Voice) Testing Mode 🟢 TT | ⚪ TV | 🟢 VV | ⚫ EX Text-to-Speech voice response and animatronics control display anthropomorphic visualization design of eyes motion computer vision method and viseme animation set according  [System.Speech.Synthesis Namespace SpeechSynthesizer.VisemeReached Event](https://docs.microsoft.com/en-us/dotnet/api/system.speech.synthesis.speechsynthesizer.visemereached?view=netframework-4.8) using Microsoft [System.Speech.Synthesis](https://docs.microsoft.com/en-us/dotnet/api/system.speech.synthesis?view=netframework-4.8) system default Zira and Irina voice reference.

- speak >> On/Off Voice Mode. TV/VV

"Speak" turn on/off VV (Voice-to-Voice) Conversation Mode 🟡 TT | 🟢 TV | ⚪ VV | ⚫ EX, condition does not allows training and represents only conversation mode. 

✔️ Note: Make sure that your system audio input is of good quality to avoid speech recognition failures.

#### Conversation controls 

- tet >> Attention. TT/TV/VV ⚪ TT | ⚪ TV | ⚪ VV | ⚫ EX

 Calling the name to get recall of attention or interrupt current monologue speech during the voice modes:

    user: tet
    _bot: what?
  
- yes >> Confirmation to accept condition. TT/TV/VV ⚪ TT | ⚪ TV | ⚪ VV | ⚫ EX
- no >> Confirmation to cancel condition. TT/TV/VV ⚪ TT | ⚪ TV | ⚪ VV | ⚫ EX

Confirmations to accept or cancel condition:

    user: format 
    _bot: you sure?
    user: yes
    _bot: memory cleared 
  
- stop >> Stop conversation. Exit back from 'continue'. TV/VV/EX ⚫ TT | ⚪ TV | ⚪ VV | ⚪ EX. 

To interrupt speech, request "stop" To exit back from "ex" waiting state, say "stop" or "stop and continue". 

    _bot: this documentation presents… 
    user: stop
    _bot: ok 
  
- again >> Repeat phrase. TV/VV ⚫ TT | ⚪ TV | ⚪ VV | ⚫ EX

To repeat phrase, request "again":

    _bot: this documentation represents… 
    user: again
    _bot: this documentation represents overview of the terbinari system.      
  
- wait >> Pause speech. VV/EX ⚫ TT | ⚫ TV | ⚪ VV | ⚪ EX

To pause speech, say "wait" EX (Voice-to-Voice) Waiting State. Command interrupts speech and enters program into closed input/output waiting state during voice-to-voice conversation.

    _bot: this documentation represents…
    user: wait
  
- continue >> Continue speech. VV/EX ⚫ TT | ⚫ TV | ⚫ VV | ⚪ EX
- stop and continue >> Exit back from 'wait'. ⚫ TT | ⚫ TV | ⚫ VV | ⚪ EX

To exit and continue speech, say "continue" or "stop and continue" without continuation. 

    user: continue
    _bot: …overview of the terbinari system.

#### Dialog keys

- what is (noun definition)
- you, your, I, my (inverse definition of subject)
- why (contextual answer to previous sentence)
- what, why, how (contextual node)

#### Memory update

- ctx >> To add context answer. TT/TV ⚪ TT | ⚪ TV | ⚫ VV | ⚫ EX

To add contextual node, use keyword "ctx":

    user: how to teach ctx
    _bot: what to teach?
    user: answers to your question
    _bot: how to teach?
    user: insert questions. insert answers
    _bot: why to teach?
    user: to teach me

And request ⚪ TT | ⚪ TV | ⚪ VV | ⚫ EX:

    user: how to teach?
    _bot: insert answers
    user: what answers?
    _bot: answers to your question
  
- ask >> To get request for answer. TT/TV ⚪ TT | ⚪ TV | ⚫ VV | ⚫ EX

Answer or request keyword "ask" for adding to exist single/multi answer/question:   

    user: ask me something
    _bot: I want to know, how to answer question (question)?
    user: some answer
    _bot: ok, if you ask "question" I answer "some answer"

#### Memory edit

- format >> Format Memory. TT/TV ⚪ TT | ⚪ TV | ⚫ VV | ⚫ EX

To format memory for default content insert "format" and confirm condition. Formatting removes memory runtime and persistent data.
 
    user: format 
    _bot: you sure?
    user: yes
    _bot: memory cleared 
    user: no
    _bot: skipped 
    user: tet
    _bot: formatting command reset. what?
  
- remove >> Remove last compound. TT/TV ⚪ TT | ⚪ TV | ⚫ VV | ⚫ EX

To remove last input, request "remove":

    user: perfect
    _bot: what is perfect?
    user: just perefct (typo or unwonted answer)
    _bot: saved
    user: remove
    _bot: last compound removed (in case of answer or) last input removed (in case of question) 
  
- delete >> Delete current compound. TT/TV ⚪ TT | ⚪ TV | ⚫ VV | ⚫ EX

To remove actual answer compound, insert "delete": 

    _bot: just perefct (typo or unwonted answer)
    user: delete
    _bot: compound removed 
    
- open chain >> ... TT/TV ⚪ TT | ⚪ TV | ⚪ VV | ⚫ EX

    With sequential insertion order request "open chain" first displays DAC second memory chain IRA value matrix keys.
    
👉 Save and upload memory file backup to avoid loss of your original content in case of unexpected shut down or runtime error. Since storing of memory executes with completing of session, this will cause memory reset with default content.

#### Requests

- en/fr/ru >> to switch language input language code. TT/TV/VV
- time >> Time and date. TT/TV/VV
- information >> Information about. TT/TV/VV
- exit >> To close program with command and condition. TT/TV/VV

#### Scenario

- how old are you >> Age. TT/TV/VV
- what is your name >> Acquaintance. TT/TV/VV
- my name >>  User name. TT/TV/VV

#### Tools

- numb +-/* numb >> Request for math calculations. TT/TV/VV
- filter >> On/Off Spelling correction filter. TT/TV

#### Vision

- vision >> Vision mode. Vision On/Off. TV/VV

✔️ Note: To assign command for a new request, add access key (c1) in your answer.

- hi and see >> Keywords to get face recognition response. TT/TV/VV
- clear >> Delete recognition data. TT/TV/VV

👉 Panel allows you to choose video device and track computer vision.



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

 
