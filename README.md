# Overview
An EQ with Lowcut, Highcut, and Peak Filter built using the JUCE API. It features the following filters:

- **Lowcut filter:** reduce the levels of frequencies below a certain cutoff point.
- **Highcut filter:** reduce the levels of frequencies above a certain cutoff point.
- **Peak filter:** boost or cut a specific frequency band.

# Building from Source
To build this synthesizer from source, you'll need to follow these steps:

1. Download and install the Projucer IDE from the [JUCE Website](https://juce.com/download/).
2. Set up your development environment by installing XCode on Mac or Visual Studio on Windows.
3. Open the **'Simpletron Synth.jucer'** file in Projucer.
4. Export the project to your desired build format (XCode or Visual Studio) and build the project.

# Programming Concepts Used
During the development of this EQ, several key programming concepts were learned and implemented. These include:

- **Signal processing:** The EQ involves manipulating digital signals in real time. Signal processing techniques, such as filtering and frequency shaping, were used to achieve the desired sound.
- **Object-oriented programming:** The EQ was designed with an object-oriented approach, which allowed for easy management of complex functionality, such as the filter algorithms and parameter controls.
- **Event-driven programming:** The user interface of the EQ is event-driven, meaning that it responds to user actions, such as clicking on a button or adjusting a knob. Event-driven programming was used to create an intuitive and interactive user experience.
- **API integration:** The EQ was built using the JUCE API, which provided a comprehensive set of libraries and tools for audio plugin development. The integration of the JUCE API allowed for efficient and reliable implementation of key features, such as the filter algorithms and parameter controls.

# TODO:
1. Adjust response curve bounds
2. Add slider labels 
