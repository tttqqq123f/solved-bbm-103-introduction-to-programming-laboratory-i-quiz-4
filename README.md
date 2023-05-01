Download Link: https://assignmentchef.com/product/solved-bbm-103-introduction-to-programming-laboratory-i-quiz-4
<br>



<h1></h1>

Accept your <a href="https://classroom.github.com/a/iQgCx0Eh"><em>4th Quiz</em></a><a href="https://classroom.github.com/a/iQgCx0Eh">.</a>

<h1>Introduction</h1>

Within the context of this quiz, you are going to gain experience on using different collections (dictionary, list and their functions) as well as on using File I O. The scenario of this work is receiving a message which is split into multiple packets and transferred over the Internet. Packets are not received in order in which they are sent.

Your program must read the input file, sort the packets and write the completed messages to an output file.

As you see from the input format, each line of input represents a single packet. each line is formatted as given below:

X (tab) Y (tab) message part

X represents message ID, Y represents packet ID. It is guaranteed that there will be no duplicate packets or message IDs.

Example Input:

Figure 1: An example of input file

1

Fall 2020

BBM 103: Introduction to Programming Laboratory I

Example Output:

Message 1

1498 0 The Road goes ever on and on

1498 1 Down from the door where it began.

1498 2 Now far ahead the Road has gone,

1498 3 And I must follow, if I can,

1498 4 Pursuing it with eager feet, 1498 5 Until it joins some larger way

1498 6 Where many paths and errands meet.

1498 7 And whither then? I cannot say.

Message 2

5181 0 There was plenty of everything left for Frodo.

5181 1 as well as the books, pictures were left in his possession.

5181 2 There was, however, no sign nor mention of money or jewellery:

5181 3 not a penny-piece or a glass bead was given away.

Message 3

6220 0 There were many Bagginses and Boffins,

6220 1 there were various Grubbs, and various Chubbs;

6220 2 and a selection of Burrowses, Brockhouses and Proudfoots.

6220 3 Some of these were only connected with Bilbo, and some 6220 4 of them had hardly ever been in Hobbiton before.

6220 5 The Sackville-Bagginses were not forgotten

6220 6 They disliked Bilbo and detested Frodo, 6220 7 written in golden ink.

The order of command-line arguments should be provided as follows:

python3 quiz4.py inputFile.txt outputFile.txt

<h1>Notes</h1>

<ul>

 <li>Do not miss the submission deadline.</li>

 <li>Save all your work until the quiz is graded.</li>

 <li>You can ask your questions via <a href="https://piazza.com/hacettepe.edu.tr/fall2020/bbm103">Piazza</a> and you are supposed to be aware of everything discussed on Piazza.</li>

 <li>You must submit your work with the file hierarchy as stated below:</li>

</ul>

→<em>&lt;</em>quiz4.py<em>&gt;</em>

2