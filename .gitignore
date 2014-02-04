-----------------------------------------------------------------------------------------
--Display Text
-- jiazhou
--
-----------------------------------------------------------------------------------------

--I like to hide the status bar
--It is distracting for me
display.setStatusBar( display.HiddenStatusBar )

--display background
--"display"is an object
--"newImage" is its method
local background = display.newImage("test_background.png")

--create an array of text using a table called myText
local myText={
	[1]="Poetics",
	[2]="of",
	[3]="Mobile"
}

--I combined the three words by creating a new variable called allText
--use .. to combine strings
local allText= myText[1] .. " " .. myText[2] .. " " .. myText[3]

--display text
local courseName = display.newText (allText, 100,100,"Arial",40)
courseName:setTextColor(255,255,255,255)

--randomly pick an integer between 1 and 3
--this number will be an index to locate the strings in the table myText
local textIndex=math.random(1,3) --inclusive

--display the word
local randomWord = display.newText (myText[textIndex], 100,200,"Arial",30)
randomWord:setTextColor(255,255,255,255)
