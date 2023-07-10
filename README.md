# Dolphin - Game Swap

> This tool provides a way to swap between 10 games at a random interval when using the Dolphin emulator.

## Setup

Make sure you have python 3.9.x installed. We recommend installing [virtualenv](https://virtualenv.pypa.io/en/latest/) as well, as that will make it possible to install packages locally to a project.

```bash
python3 -m virtualenv venv
source venv/bin/activate
```

Next, install the required packages with pip: `pip install -r requirements.txt`

At this point you have the basic setup completed, now you can adjust the tool to your liking by copying the `.env.example` file and adjusting it to your needs:

```bash
cp .env.example .env
```

Open the `.env` file and adjust the variables to suit your needs.
