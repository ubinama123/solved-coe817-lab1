Download Link: https://assignmentchef.com/product/solved-coe817-lab1
<br>
<strong> </strong>

<strong>Objectives  </strong>

<ul>

 <li>In this lab, you will work on Caesar Cipher and an implementation of the Vigenère Cipher, the system for encoding and decoding text messages that was discussed in class. You will program with Java or Python. Netbeans is the IDE for Java and Anaconda is the IDE for Python.</li>

</ul>

<strong> </strong>

<h1>Exercise 1</h1>

<ul>

 <li>Choose a secret sentence (Plaintext) of about 20 words and encrypt using Caesar Cipher with your own secret key. Fill the table 1 by using your plain text, secret key and corresponding ciphertext.</li>

</ul>




<em> </em>

<table width="645">

 <tbody>

  <tr>

   <td width="123">Plaintext</td>

   <td width="523">Yesterday was excellent! Let’s meet again Tuesday at noon</td>

  </tr>

  <tr>

   <td width="123">Your secret Key</td>

   <td width="523">A shift of +3, i.e. A -&gt; D</td>

  </tr>

  <tr>

   <td width="123">Ciphertext</td>

   <td width="523">Bhvwhugdb zdv hafhoohqw! Ohw’v phhw djdlq Wxhvgdb dw qrrq</td>

  </tr>

 </tbody>

</table>

<em>Table 1: Encryption </em>

<ul>

 <li>Break the given Ciphertext encrypted by Caesar Cipher</li>

</ul>




<table width="645">

 <tbody>

  <tr>

   <td width="123">Ciphertext</td>

   <td width="523">Glzkx g cnork, Rozzrk Jaiqrotm cgy zoxkj ul vrgeotm. Ynk yixgshrkj av utzu znk mxgyye hgtq gtj lrallkj uaz nkx lkgznkxy zu jxe. Gxuatj nkx znk cotj cnoyvkxkj ot znk mxgyy. Znk rkgbky xayzrkj gtj ubkxnkgj znk yqe mxkc jgxq. Rozzrk Jaiqrotm xkgrofkj ynk cgy grr grutk.</td>

  </tr>

  <tr>

   <td width="123">Plaintext</td>

   <td width="523"></td>

  </tr>

  <tr>

   <td colspan="2" width="645">Explain how you break the Ciphertext, provide details.Plaintext: After a while, Little Duckling was tired of playing. She scrambled up onto the grassy bank and fluffed out her feathers to dry.  Around her the wind whispered in the grass. The leaves rustled and overhead the sky grew dark. Little Duckling realized she was all <sub>alone.</sub> To break the ciphertext, I used the brute force method. I wrote a Python script that would use all 26 keys from range 0 to 25 and print<sub>them all in an output file. I then simply parsed through the file to find the sentence that was in plain English.</sub>          </td>

  </tr>

 </tbody>

</table>

<em>Table 2: Decryption </em>

Page 1 of 2

<strong>Exercise 2: </strong>

Part A: Use Java or Python to solve this exercise. In Java name your class as “Vigenere<strong>”</strong>. In Python name your program as “Vigenere”. Here are the requirements for the methods/functions. You may include other methods if needed

<ul>

 <li>Create a method/function in the class <sub>Vigenere</sub> that will <strong>encrypt</strong> a message using a specified key.</li>

 <li>Create a method/function in the class<sub> Vigenere</sub> that will<strong> decrypt</strong> a message using a specified key.</li>

</ul>

Part B: Write a <sub>main </sub>method/function in class Vigenere to do the following:

<ol>

 <li>Ask the user to enter the message “TO BE OR NOT TO BE THAT IS THE QUESTION”.</li>

 <li>Ask the user for the Vigenère key “RELATIONS”.</li>

 <li>Encode the message using the Vigenère cipher.</li>

 <li>Print the encrypted text.</li>

 <li>Decode the message using the Vigenère cipher.</li>

 <li>Print the result of decrying the encrypted text (which should be the original text).</li>

</ol>

<strong> </strong>

<strong> </strong>

<strong>   </strong>


