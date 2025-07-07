# cloud_computing
#using Text to speech using watson 
<br>
curl -X POST -u "apikey:{apikey}" --header "Content-Type: application/json" --header "Accept: audio/wav" --data "{\"text\":\"HI I AM A STUDENT . I WANT TO LEARN CLOUD COMPUTING.\"}" --output demo.wav "{url}"
