# learning-git
Using this repo to learn and polish my Git skills

# Important Regex:
Regex to count the no. of strings, numbers and special characters:
Loop through the length of the sentence and then:

let char = sentence[i];

**Number**: if(!isNaN(char) && char != ' ')

**String**: if(/[a-zA-Z]/.test(char))

**Special Character**: if(/[^a-zA-Z0-9]/.test(char))
