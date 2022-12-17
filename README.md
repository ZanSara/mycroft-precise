# Precise

A lightweight, simple-to-use, RNN wake word listener.

Fork of https://github.com/MycroftAI/mycroft-precise.

See their README for a more detailed description.

### Supported OS
 - Linux (tested on Ubuntu)

### Supported Python
 - `>=3.10`

### Training
 - See the [wiki](https://github.com/ZanSara/mycroft-precise/wiki/)

## Installation

```bash
git clone https://github.com/mycroftai/mycroft-precise
cd mycroft-precise

sudo apt-get install -y python3-pip curl libopenblas-dev python3-scipy cython libhdf5-dev python3-h5py portaudio19-dev swig libpulse-dev libatlas-base-dev

python3 -m venv venv
source venv/bin/activate

# Now you can run binaries like:
precise-collect
# See the wiki for more.
```

## How it Works

Precise uses just a single recurrent network, specifically a GRU.

![Architecture Diagram](https://raw.githubusercontent.com/ZanSara/mycroft-precise/dev/diagram.png)
