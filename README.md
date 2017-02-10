# CommandlineWordsAndTopicsResearchTool

This is a comandline utility to assist with rapid research.  If you are a word smith, enjoy researching topics, definitions, etymology, synonyms, antonyms, acronyms, medical terms, legal terms, text and chat acronyms, and newer words in Urban Dictionary.  This application searches 15 different source.

Example Searching :  java -cp .:./jsoup-1.10.2.jar DownloadDefinitions "d1" "love"

Output:

SEARCHING : http://www.thefreedictionary.com/love

1. A strong feeling of affection and concern toward another person, as that arising from kinship or close friendship.
2. A strong feeling of affection and concern for another person accompanied by sexual attraction.
3. a. A feeling of devotion or adoration toward God or a god. b. A feeling of kindness or concern by God or a god toward humans. c. often Love Christianity Charity.

Example Searching :  java -cp .:./jsoup-1.10.2.jar DownloadDefinitions "d4" "love"

Output:

SEARCHING : https://en.wikipedia.org/wiki/love

Love is a variety of different feelings, states, and attitudes that ranges from interpersonal affection ("I love my mother") to pleasure ("I loved that meal"). It can refer to an emotion of a strong attraction and personal attachment.[1] It can also be a virtue representing human kindness, compassion, and affection—"the unselfish loyal and benevolent concern for the good of another".[2] It may also describe compassionate and affectionate actions towards other humans, one's self or animals.[3]

Example Help:

java -cp .:./jsoup-1.10.2.jar DownloadDefinitions "help"

Example Compiling:

javac -cp jsoup-1.10.2.jar DownloadDefinitions.java


