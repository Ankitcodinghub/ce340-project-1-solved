# ce340-project-1-solved
**TO GET THIS SOLUTION VISIT:** [CE340 Project 1 Solved](https://www.ankitcodinghub.com/product/ce340-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113572&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CE340 Project 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Project 1: CE 340 Cryptography and Network Security

STEPS OF IMPLEMENTATION OF A SINGLE-ROUND ENCRYPTION SCHEME:

You will implement the algorithm given in Fig. 1.

2) A permutation code of length 8 is chosen to be IP = 6 4 2 8 7 5 3 1. The 8-character text blocks will be permutated using the initial permutation (IP) code.

3) Use either BINARY values of characters from Table 1 to encode characters so that each character will be 8 bits of length.

Table 1: Character encoding

A 00000001 B 00000010 C 00000011 Ç 00000100 D 00000101 E 00000110

F 00000111 G 00001000 Ğ 00001001 H 00001010 I

00001011 İ

00001100

J

00001101 K 00001110 L 00001111 M

00010000 N 00010001 O 00010010

Ö 00010011 P 00010100 R 00010101 S 00010110 Ş 00010111 T 00011000

U 00011001 Ü 00011010 V 00011011 Y 00011100 Z 00011101 .

00011110

,

00011111 (

00100000 )

00100001 !

00100010 ;

00100011 :

00100100

‘

00100101 “ 00100110 –

00100111 ? 00101000 $ 00101001 @

00101010

%

00101011 a

00101100 b

00101101 c

00101110 ç

00101111 d

00110000

e

00110001 f

00110010 g

00110011 ğ h ı

i j K l m n

o

ö p q r s

ş

t u ü v y

z

Q W q w …

4) Preform a Shift-right-rotate operation with 4 positions on the encoded characters.

5) Get 2 characters at a time from the encoded block: Characters at odd positions are placed into the left nibble and characters with even positions are placed into the right nibble.

6) Choose a 16-bit (2 characters) key and convert them to 16 bits, and put the bits into a 4×4 matrix (table), see Fig.1.

7) Now use the columns 3,1,0, 2 to generate K2 and use columns 0,1,3,2 to generate K3.

a. Concatenate columns 3 and 1, that is x = (3||1), and concatenate columns 0 and 2 that is y = (0||2). Here, x and y will now be 8 bits each. Now perform XOR on x and y to generate K2, i.e., K2 = (x XOR y)

b. Concatenate columns 0 and 1, that is w = (0||1), and concatenate columns 2 and 3, that is z = (2||3), and. Now perform XOR on x and y to generate, i.e., K3 = (w XOR z).

c. Use K2 in function SLR(3, K2) to generate K4. Likewise, Use K3 in function SRR(3, K3) to generate K5.

8) Apply XOR together with K2 and K3 to encrypt the first part (stage 6, 8). Swap XOR’d partitions so that left becomes right and right becomes left.

9) Now, generate two new sub-keys (K4 and K5) by using K2 and K3 and the two rotate functions, see Fig.1 (part 10).

10) The swapped partitions are XOR’d with the new sub-keys. 11) Swap the result again and merge the results of swapping.

12) Finally, a cipher block is obtained by passing the resulting 8-character block through the reverse permutationIP-1.

13) Encrypted blocks will be saved in a ciphertext file.

14) Finally, verify your encryption by decrypting the ciphertext file.

What to deliver:

1) Source code: You can choose to implement the algorithm in either of these languages

C, C++, Java, or Python

2) Screenshots of a sample run

3) Plaintext file used for the test

4) Ciphertext file obtained from the test

Fig.1 Block Diagram of the encryption process.
