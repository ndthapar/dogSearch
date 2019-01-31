# dogSearch
Periodically searches miami-dade animal shelter's websites for specific dogs and notifies via email

I am looking to adopt a dog with specific breed and age requirements. The dogs I am looking for get adopted almost immediately
after they get processed, so I have to keep manually checking the miami-dade animal shelter website, so I can drive over as soon as the dogs
profile comes up. 

The website has no notification system and I got annoyed having to keep looking at it so I wrote a script to periodically open it up and survey it for me 
using selenium. When the dogs that fit my desired profile are found the script sends me an email that I can see as a notification 
on my phone via pythons smtplib.
