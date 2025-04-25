# cs150-lab-19-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cs150-lab-19-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;128006&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS150  Lab 19 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
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
            5/5 - (4 votes)    </div>
    </div>
COPY your completed code from Lab 18 into your lab 19 repl (be sure Lab 18 is working correctly first). After you have copied it, modify the code in the Lab 19 repl so that instead of closing we ask the user if they want more trees after drawing their request, and if they enter “Y” or ‘y’ repeat the process (enter number and height, then draw). After drawing each “batch” of trees also tell the user how many trees have been drawn overall. Use a static variable in drawTrees to track this information.

IMPORTANT: Complete this lab in the Lab 19 repl only – do NOT overwrite or modify Lab 18 in the Lab 18 repl!

Write a function called treeTop that prints the top of a tree. It should take no parameters and return void. Write a second function called treeTrunk that prints the trunk of a tree. It should take one integer as a parameter for height (how many lines tall the trunk is), and also have a return type of void. Finally, create a function called drawTrees that takes two integer parameters, one for height and one for the number of trees to draw. drawTrees should use treeTop and treeTrunk.

Have the user enter the height of the trees (same for all) and number of trees to draw. Remember that to draw a backslash you need two backslashes.

Test case:

Enter tree height: &lt;2&gt;

Enter number of trees: &lt;3&gt;

^

/ /

/____

| |

| |

^

/ /

/____

| |

| |

^

/ / /____

| |

| |

There are currently 3 trees in the forest.

Do you want more trees (Y/N) ?: &lt;y&gt;

Enter tree height: &lt;5&gt;

Enter number of trees: &lt;1&gt;

^

/ /

/____

| |

| |

| |

| |

| |

There are currently 4 trees in the forest.

Do you want more trees (Y/N) ?: &lt;Y&gt;

Enter tree height: &lt;1&gt;

Enter number of trees: &lt;3&gt;

^

/ /

/____

| |

^

/ /

/____

| |

^

/ /

/____

| |

There are currently 7 trees in the forest.

Do you want more trees (Y/N) ?: &lt;N&gt;
