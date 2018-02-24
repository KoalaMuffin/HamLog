# HamLog. Coming March 10.
HamLog is a work in progress software I am developing for logging ham radio contacts. It will use <a href="https://electronjs.org">Electron</a> and <a href="http://photonkit.com/">Photon</a>. It is my first project with these frameworks. You can see an image of how it looks so far below.
<img src="https://raw.githubusercontent.com/KoalaMuffin/HamLog/master/Preview2.png">
<br>
Want to try it out?
Download and install the files:
<pre>
sudo git clone https://github.com/KoalaMuffin/HamLog.git
cd HamLog
npm install
npm start
</pre>
Electron requires NodeJS and NPM, I believe.
<p>What still needs to be done:
<ul>
  <li>Switch from Photon to native (original) or maintained framework.</li>
  <li>Potentially use a different storage system than LocalStorage.</li>
</ul>
