# AI-Voice-Pipeline
Rasppy Getting Started - https://rhasspy.readthedocs.io/en/latest/tutorials/#getting-started-guide
Wvyoming-protocol:  https://github.com/rhasspy/rhasspy3/blob/master/docs/wyoming.md 


script/run \
  --name 'my satellite' \
  --uri 'tcp://0.0.0.0:10700' \
  --mic-command 'arecord -D plughw:CARD=Seri,DEV=0 -r 16000 -c 1 -f S16_LE -t raw' \
  --snd-command 'aplay -D plughw:CARD=Headphones,DEV=0 -r 22050 -c 1 -f S16_LE -t raw'
  
  
  script/run \
  --name 'my satellite' \
  --uri 'tcp://0.0.0.0:10700' \
  --mic-command 'arecord -D plughw:CARD=Microphone,DEV=0 -r 16000 -c 1 -f S16_LE -t raw' \
  --snd-command 'aplay -D plughw:CARD=Headphones,DEV=0 -r 22050 -c 1 -f S16_LE -t raw'
  
  
  ollama is served from http://localhost:11434/

video reference https://www.youtube.com/watch?v=XvbVePuP7NY&t=1061s

hardware:
pi-hat: https://thinkrobotics.com/products/respeaker-2-mics-pi-hat-for-raspberry-pi-online?variant=44357098275133&country=IN&currency=INR&utm_medium=product_sync&utm_source=google&utm_content=sag_organic&utm_campaign=sag_organic&srsltid=AfmBOopdLO6JzXxkTFfFQJr9HXInNKhUJwrX4KsYU5FC3yKk5R7dJ2MDI1k

