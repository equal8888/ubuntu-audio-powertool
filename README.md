## App for audio tweaks
<img src="https://drive.google.com/uc?id=1eo0iiS0emqrCaVnVbS2COTDSqnF_TiuM" width="auto" height="200"/>
<br>
App will reconfigure pulseaudio daemon.conf file.
<br>
don't set sample rate to "maximum option available", that will do audio resampling and you don't want that! Set sampling rate according to what you hear. If a CD audio: 44.1KHz. If DVD: 48KHz. Bit depth instead should always be the highest available, whereas 24bit seems to be the highest the best cards can handle.
<br>
 <strong>GUI will be updated !!</strong>.

## Usage
from terminal
```
python3 Ubuntu-Audio-App.py
```
user will be prompted for his password
