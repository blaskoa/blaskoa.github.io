Nefunkcnostou pluginov na githube utrpela hlavne uvodna stranka, za co sa ospravedlnujem.

Na stranke su pouzite 2 pluginy: 
- Emoji for jekyll : https://github.com/yihangho/emoji-for-jekyll
- reading_time: https://github.com/bdesham/reading_time

Pre lokalne rozbehanie stranky som pustal 2 prikazy:
gem install liquid_reading_time
gem install emoji_for_jekyll

Vsetky pluginy su aj v /_plugins foldry, takze emoji by mali fungovat out of the box. Reading time by fungoval tiez, ale obsahuje dependency na gem nokogiri (ktory sa instaluje ako sucast package pri spusteni horespominaneho prikazu).