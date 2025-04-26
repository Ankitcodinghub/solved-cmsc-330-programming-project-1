# solved-cmsc-330-programming-project-1



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/solvedcmsc-330-programming-project-1/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;3028&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;SOLVED:cmsc 330 Programming Project 1&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
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
    
<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
The first project involves writing the lexical analyzer with lexical error checking, and the compilation listing generator for the compiler. The specification for the lexical structure of the language is the following:

1. Comments begin with — and end with the end of the line.

2. White space between tokens is permitted but not required.

3. Identifiers must begin with a letter, followed by letters or digits.

4. Integer literals consist of a sequence of digits.

5. Real literals consist of a sequence of digits containing a decimal point. At least one digit must be before the decimal point.

6. Boolean literals are true and false

7. The logical operators are not, and and or. Each logical operator should be a separate token.

8. The relational operators are =, /=, , =, &lt;, and &lt;=. All six lexemes should be represented by a single token.

9. The adding operators are the binary + and -. Both lexemes should be represented by a single token.

10. The multiplying operators are * and /. Both lexemes should be represented by a single token.

11. The following punctuation symbols should be accepted: commas, colons, semicolons, and parentheses.

12. The following are reserved words: begin, boolean, else, end, endif, function, if, is, integer, real, returns, then The lexical analyzer should be created using flex. The compiler should produce a listing of the program with lexical error messages included after the line in which they occur. Any character than cannot start any token should be considered a lexical error.

It should also generate a file containing the lexeme-token pairs as a means to verify that the lexical analyzer is working correctly. Only token numbers are required, not token names. The token numbers for the punctuation symbols should be the ASCII value of the character. The remaining tokens should be numbered sequentially beginning at 256.

The 70 points for functionality will be allocated as follows:

CMSC 430 – Programming Project 1 Page 1 of 2

http://nova.umuc.edu/~jarc/cmsc430/proj1c.html 1/20/2014

See the general project requirements for the details on submitting your project.

Compilation listing generated with line numbers 20 points

Detects and reports lexical errors correctly 25 points

Generates file with correct lexeme-token pairs 25 points

CMSC 430 – Programming Project 1 Page 2 of 2

http://nova.umuc.edu/~jarc/cmsc430/proj1c.html 1/20/2014
