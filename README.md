<br />
<div align="center">
  <a href="https://gitlab.com/pet-projects26/pcm2mp3.git">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Asterisk PCM Converter</h3>

  <p align="center">
    Bulk convert Asterisk PBX PCM to Mp3 file
    <br />
    <a href="#getting-started"><strong>Explore the docs »</strong></a>

  </p>
</div>


# Getting Started
### Prerequisites

* [Ffmpeg](https://windowsloop.com/install-ffmpeg-windows-10/)
* [Python](https://www.python.org/downloads/)


### Installation

* Clone the repo and install requirements
   ```bash
    git clone https://gitlab.com/pet-projects26/pcm2mp3.git
    
    cd AsteriskConvertAudio
    
    pip install -r requirements.txt
   ```

## Usage

Open Command Prompt or Powershell where the script locate and run following command execute it. 
  ```bash
  python MergeFilePython [-v] [-h] <Path>
  ```
  Argument
  
  * Path: Absolute path to folder contain raw (PCM) file.
  
  Options
  * -v Increase output verbose.
  * -h Display help message.

---
For more infomation, please refer to the some documention below

- [PythonWave Library](https://docs.python.org/3/library/wave.html)
- [Python PyDub Library](https://github.com/jiaaro/pydub)
- [PyDub Readthedocs](https://audiosegment.readthedocs.io/en/latest/audiosegment.html)


## License
Distributed under the MIT License. See [LICENSED](https://opensource.org/licenses/MIT) for more information.

## Contact
Harry - Email: ngogiahung567@gmail.com
