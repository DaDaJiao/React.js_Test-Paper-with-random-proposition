# React.js Test Paper with Random Proposition<br>
<br>

### Function<br>
Initialize a test paper with random proposition. <br>
If you answer the question correctly, it will not show up the next time you initialize a test paper.<br>
All the correct anwsers are A.<br>
<br>
### Module Structure<br>
StartButton (call) Paper (call) Quesion<br>
besides, <br>
Paper (call) SubmitButton (call) StartButton<br>
<br>
### Function Realization<br>
##### Random Proposition<br>
I have initialized three questions arrays, which are easy quesions array, simple quesions array and hard quesions array. <br>
To improve efficiency, I initialize three random number arrays corresponding to three questions arrays. <br>
So I can obtain or delete questions through these random number arrays without directly operating questions arrays.<br>
<br>
##### Delete Questions You Have Answered Correctly<br>
Test paper obtain questions through random number arrays. <br>
If you answer a question correctly, the number corresponding to the question in random number arrays will be deleted. <br>
So the next time you start test, it will not show up again.