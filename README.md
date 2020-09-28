# Personality-test
Project that benefits staff &amp; students of Schools.
https://create.withcode.uk/python/BYU
word_list=("Happy","Sad","OK","Fine","Good","Not very well","Not bad","Well")
feeling=input("How do you feel? Maybe I can help. ")
 
if "Good" or "Happy" in feeling():
  print("Happy you are fine! Don't let the smallest things let you down! ")

elif "Not very well" or "sad"  in  feeling():
  situation=input("What happened recently that made u feel " + str(feeling))
  if "marks" or "study" or "scolded" in situation():
  print("It's alright that happened, just learn from it and not make the same mistake again")
