
# TUF-Aurora

This is a fork of the discontinued project [TUF-Control](https://github.com/icodelifee/TUF-Control.git) focused on Battery Manager and Keyboard Lighting <a href="https://github.com/hackbnw/faustus">hackbnw/faustus</a> Driver Module For ASUS TUF Gaming Series Laptops

<img src="https://github.com/legacyO7/TUF-Aurora/raw/master/src/images/ss.png"/> 

<img src="https://github.com/legacyO7/TUF-Controll-FA706/raw/master/images/ss.png"/> 

## Automated installation
<ol>
  <li><code>git clone https://github.com/legacyO7/TUF-Aurora.git</code></li>
  <li><code>cd TUF-Aurora/</code></li>
  <li><code>./setup.sh</code></li>
</ol>

## How to compile .deb package
<ol>
  <li><code>sudo apt-get install nodejs npm</code></li>
  <li><code>git clone https://github.com/legacyO7/TUF-Aurora.git</code></li>
  <li><code>cd TUF-Aurora/</code></li>
  <li><code>npm install</code></li>
  <li><code>npm run clean-build</code></li>
  <li><code>npm run dist</code></li>
  <li><code>sudo dpkg -i dist/tuf-aurora_*.deb</code></li>
</ol>

## How to compile .rpm package
<ol>
  <li><code>sudo yum install nodejs npm</code></li>
  <li><code>git clone https://github.com/legacyO7/TUF-Aurora.git</code></li>
  <li><code>cd TUF-Aurora/</code></li>
  <li><code>npm install</code></li>
  <li><code>npm run clean-build</code></li>
  <li><code>npm run dist</code></li>
  <li><code>sudo rpm -i dist/tuf-aurora_*.rpm</code></li>
</ol>
