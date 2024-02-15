# Looker Playgrounds

Welcome to Looker Playgrounds! This repository is a hub for innovative experiments combining Looker with the latest in Generative AI capabilities and voice interaction technologies. Dive into the world of advanced data visualization and interaction, exploring how Looker can be enhanced with AI-driven insights and voice-driven commands.

## Features

### NLP Query-Visualization (`app_qv.py`)

`app_qv.py` is an NLP solution that leverages query-visualization in Looker. It allows users to interact with Looker visualizations directly using natural language processing (NLP), without the need to embed the explore module. Simply input your data query in natural language, and the tool translates it into a Looker visualization, providing instant insights.

### Dashboard Generator (`dashgen.py`)

`dashgen.py` is a Dashboard Generator for Looker. It creates dynamic, AI-generated dashboards based on a simple prompt. By analyzing the prompt, it understands the needed data insights and constructs a comprehensive dashboard in Looker, streamlining the dashboard creation process and making it more accessible.

### Mobile Speech Interface (`mobile-speech.py`)

`mobile-speech.py` offers a mobile-friendly interface allowing users to ask questions about their data using natural language. It processes spoken queries through NLP and interacts with Looker to fetch and display the relevant data, making data interaction seamless and intuitive on mobile devices.

### Voice-Interactive Data (`speech.py`)

`speech.py` enables users to interact with Looker's data using voice commands. Speak your data query or command, and receive a summary returned in voice format. This experiment integrates Google Cloud's Text-to-Speech and Speech-to-Text services, offering a hands-free data exploration experience.

## Getting Started

To get started with Looker Playgrounds:

1. Clone this repository to your local machine.
2. Ensure you have the necessary dependencies installed. 
3. Follow the individual setup instructions for each experiment included in their respective sections.

## Prerequisites

- Looker account and API credentials.
- Python 3.x.
- [Gradio](https://www.gradio.app/)
- Access to Google Cloud Platform for voice services. [Documentation](https://cloud.google.com/speech-to-text/docs)
- Additional libraries as specified in each experiment's setup instructions.

## Installation

Please refer to the README sections within each experiment folder for detailed installation and usage instructions.

## Contributing

Contributions to Looker Playgrounds are welcome! Whether it's adding new experiments, improving existing ones, or fixing bugs, your input is valuable. Please read `CONTRIBUTING.md` for details on our code of conduct, and the process for submitting pull requests to us.


## Acknowledgments

- Thanks to all contributors who have helped shape Looker Playgrounds.
- Special thanks to Looker and Google Cloud Platform for enabling powerful data and voice integration capabilities.
