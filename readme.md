 <p>
Voice activated digital assistant. Created using Python3, SpeechRecognition, espeak and pyaudio.
 </p>
<h2>
<a id="how-to-use" class="anchor" href="#how-to-use" aria-hidden="true"><span class="octicon octicon-link"></span></a>How to use:
</h2>

#### Install Dependencies

I prefer using Virtual environment to play with new libraries and packages so that my core packages remain unharmed.
To use this in virtual environment open a terminal (I am using Ubuntu 15.04 and Python3) and follow the steps.
		(venv)arsho@arsho:/media/arsho/Documents/PyPrac/speech$ python -m idlelib.idle

Create and activate `virtualenv` (Virtual Environment) with `Python3`:

		$ virtualenv -p python3 venv
		$ source venv/bin/activate

Install necesarry packages inside the `virtualenv`:

		(venv)$ pip install SpeechRecognition
		(venv)$ pip install pyaudio

or install these packages from `requirements.txt` attached to this repository:

		(venv)$ pip install -r requirements.txt

Install `espeak`:

		(venv)arsho@arsho:/media/arsho/Documents/PyPrac/speech$ sudo apt-get install espeak
		
#### Running Python code using IDLE3 in Virtual Environment

To run IDLE3 while `venv` is activated use the following command. Then browse and open the file using `idle3`.

		(venv)$ python -m idlelib.idle

<ul>
<li>Run tts_stt.py.</li>
<li>Start talking!</li>
</ul>

<h3>Enjoy!</h3>

