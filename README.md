# C_Ching
I Ching coin method emulated to C Programming Language - Run in Shell

## What is the I Ching
The I Ching(Yi Jing) or Book of Changes is an ancient oracle used for divination practice. For brevity and coherency, I will be quoting the description of the I Ching given by Carl Jung. 
"For more than thirty years I have interested myself in this oracle technique, or method of exploring the unconscious, for it has seemed to me of uncommon significance. I was already fairly familiar with the I Ching when I first met Wilhelm in the early nineteen twenties; he confirmed for me then what I already knew, and taught me many things more. (Foreword to the I Ching, I Ching, Wilhelm/Baynes edition). 

Thus it happens that when one throws the three coins, or counts through the forty-nine yarrow stalks, these chance details enter into the picture of the moment of observation and form a part of ita part that is insignificant to us, yet most meaningful to the Chinese mind. With us it would be a banal and almost meaningless statement (at least on the face of it) to say that whatever happens in a given moment possesses inevitably the quality peculiar to that moment. This is not an abstract argument but a very practical one. There are certain connoisseurs who can tell you merely from the appearance, taste, and behavior of a wine the site of its vineyard and the year of its origin. There are antiquarians who with almost uncanny accuracy will name the time and place of origin and the maker of an objet d'art or piece of furniture on merely looking at it. And there are even astrologers who can tell you, without any previous knowledge of your nativity, what the position of sun and moon was and what zodiacal sign rose above the horizon in the moment of your birth. In the face of such facts, it must be admitted that moments can leave long-lasting traces.

In other words, whoever invented the I Ching was convinced that the hexagram worked out in a certain moment coincided with the latter in quality no less than in time. To him the hexagram was the exponent of the moment in which it was casteven more so than the hours of the clock or the divisions of the calendar could beinasmuch as the hexagram was understood to be an indicator of the essential situation prevailing in the moment of its origin."

## Who am I and Why have I taken on this project?
My name is Tim, and I recently became interested in programming. I figured the best course of action was to take course and begin practicing with the C Programming Language, as my research led me to conclude that this was the essential language to grasp all other languages for future learning endeavors.

I first became aware of the Book of Changes after dropping out of college and studying quite a bit of psychology. I found the process fascinating, particularly as I attempted to grapple with my own psychology and responses to eternal/internal stimuli. My college tenure was plagued with loss of family members and new experiences that I had not found a way in which to come to terms with. Enough about that, however I found that bit essential to understand my gravitation towards Jung's theories and explaining my exposure to the i ching. Not that it inherently matters, only to present an image of someone who deeply cares and found this idea useful and who hopes it may bring clarity to others as it has my own life. 

There are a lot of interpretations of Jungs proposal for synchronicity, tho I wish to simply define this as the idea that life in all of its chaos has meaning. This is an idea that has been reinforced with my relationship to the hexagrams. 

Nevertheless, I have gone back to school and continued my studies into C Programming, when I learned about the rand() and srand() functions. The thought that I could use this to simulate a coin flip crept in, then the concept of emulating three coin flips to generate yin and yang lines. I know I am using some jargon here, but I have no where else to share my thought process, excpet with the program itself, though still a work in progress.

## How to use the I Ching and C Ching
A popular method for consulting the I Ching is by using a coin method, where a person takes three of the same coins and flips them at once to generate one of four outcomes: HHH, TTT, HHT, or HTT(or TTH, THH, HTH, THT) These outcomes produce a solid or a broken line.

To begin this process, think of a question that you wish to have answered(the more intentional and serious the better the results, at least in my experience). The program starts by having you type your question. This is not entirely necessary, but I found this function useful for myself to review. Press enter and the program emulates 3 coin flips, and prints the corresponding line to output. 

There are plans to develop more functionality with the program such as adding descriptions for the hexagrams, logging the querys/resulting hexagrams, and overall providing more information.

## Please feel free to take this program and edit to your liking
This is primarily for personal use however I did happen to consult the program and ask about sharing this.

./a.out
I am grateful that you decided to communicate with the seemingly invisible!
Please enter your query...
What can I expect if I share this process/program with others?

The answer to your query is being generated...

Primary Hexagram:

Line 6: ~~~~~   (Young Yang)
Line 5: ~~~~~   (Young Yang)
Line 4: ~~ ~~   (Young Yin)
Line 3: ~~~~~   (Young Yang)
Line 2: ~~ ~~   (Old Yin, changing)
Line 1: ~~~~~   (Young Yang)

Secondary Hexagram after apply changing lines:

Line 6: ~~~~~   (Young Yang)
Line 5: ~~~~~   (Young Yang)
Line 4: ~~ ~~   (Young Yin)
Line 3: ~~~~~   (Young Yang)
Line 2: ~~~~~   (Changed from Old Yin)
Line 1: ~~~~~   (Young Yang)

Here you can see the response that I recieved in the form of Hexagram 37.

gnostic-book-of-changes.pdf : using this found here on github we get the following explanation:
Confucius/Legge: In Family the wife is in her correct place in the lower trigram, and the husband in his correct place in the upper. That spouses occupy their correct positions shows the correct relationship between heaven and earth.  The parents rule the family: let the father indeed be father, and the son son; let the elder brother be indeed elder brother, and the younger brother younger; let the husband indeed be husband, and the wife wife -- then the family will be in its correct state.  Bring the family to that state, and all under heaven will be established.

I am not here to sell you anything, or gain notoriety. I sincerely hope that your path be blessed and you may find this program useful. Of note, this is the only community that I could think to share with. I know there are some cryptic meanings, but that is ultimately up to you to interpret.

As for line 2 changing
Confucius/Legge: The good fortune is due to the docility of its subject operating with humility.  Wilhelm/Baynes: The good fortune depends upon devotion and gentleness. Blofeld:  Namely, good fortune arising from compliance and gentleness. Ritsema/Karcher: Yielding uses Ground indeed. Cleary (2): What bodes well is docile obedience. Wu: The good fortune comes from the subject’s modesty.

Seriously take this program, its only for me, but hopefully you can find value with it. Ironically I debated sharing this as I was worried that my job prospects would deteroriate due to not following conventional markdown, coding, and simply because this topic tends to be more fringe than the bible haha. 

Stay blessed everyone, if you are using this program, I sincerely hope that great wisdom and riches follow wherever you lead!

-Tim
