# ST-wrangle
- I have been assigned with Julius Caesar as my number is 14
- Here is the link for it 
- http://shakespeare.mit.edu/julius_caesar/full.html
## My Player 1 :
- ANTONY
## My Player 2 :
- OCTAVIUS
- I have been asked to count the occurance of player 1 and player 2 
## Commands I have used:
- Firstly, with the help of curl command I have fetched the data from the URL 
curl "http://shakespeare.mit.edu/julius_caesar/full.html" -O JuliusCaesar.txt
- cat JuliusCaesar.txt | grep -i 'ANTONY' -c , with the help of this command I have counted the occurance of player 1 i.e, antony as 125
- cat JuliusCaesar.txt | grep -i 'ANTONY' -c > ANTONY.txt, by using this command i have saved my result to text file
- cat JuliusCaesar.txt | grep -i 'OCTAVIUS' -c , with the help of this command I have counted the occurance of player 2 i.e, octavius as 43
- cat JuliusCaesar.txt | grep -i 'OCTAVIUS' -c > OCTAVIUS.txt, by using this command i have saved my result to text file

