# cs211-assignment-5--objective-to-find-anagrams-using-hashing-solved
**TO GET THIS SOLUTION VISIT:** [CS211 Assignment 5- Objective To find anagrams using hashing Solved](https://www.ankitcodinghub.com/product/cs-211-data-structures-and-algorithms-lab-solved-5/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116673&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS211 Assignment  5- Objective To find anagrams using hashing Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
An anagram is a word formed from another by rearranging its letters. For example ‘brainy’ is an anagram of ‘binary’ and vice versa.

Command-line argument:

Your program should receive three command-line arguments: a file containing words, the size of the hash table, and a query file. For example, a typical run of your program can be ./a.out words.txt 25000 query.txt .

Inputs:

An input file containing words: The first command-line argument is the path of a text file containing

English words. The file contains one word per line.

The size of the hash table: The second command-line argument is a positive integer which denotes how many slots should be there in the hash table you create.

Task

Let m be the size of the hash table (given by the second command-line argument). Use the hash function h described below. Given a string, the hash function sums the ASCII values of the characters in the string and takes the remainder obtained by dividing the sum with m. For example h(‘brainy’) =

98+114+97+105+110+121 % m. If m=25000, this value is 645.

Your hash table should resolve collisions by chaining. Every slot in the hash table should contain a pointer to a linked list. Take the words one by one from the input file containing words, apply the hash function, and insert the word in the linked list associated with the slot given by the hash function. The insertion should always be done at the beginning of the linked list.

Take every ‘word’ in the file containing queries: (i) hash it; (ii) list all anagrams of the ‘word’ present in the linked list associated with the slot given by the hash function. Note that the hash function we defined will hash all anagrams of a word to the same slot. So, to obtain the anagrams of a word, it is enough to search in the linked list associated with the slot. Also note that there can be other words, which are not anagrams in the same linked list. Your program should be able to ignore them while collecting all anagrams of the word.

Output:

Submission

● The program you submit should output anagrams.txt when run.

● Follow some coding style uniformly. Provide proper comments in your code.

●

Evaluation
