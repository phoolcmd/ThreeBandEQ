# Building from Source
To build this synthesizer from source, you'll need to follow these steps:

1. Download and install the Projucer IDE from the [JUCE Website](https://juce.com/download/).
2. Set up your development environment by installing XCode on Mac or Visual Studio on Windows.
3. Open the **'Simpletron Synth.jucer'** file in Projucer.
4. Make any necessary changes to the project settings, such as adding additional modules or changing the output directory.
5. Export the project to your desired build format (XCode or Visual Studio) and build the project.

# How to Use
1. Launch the EQ plugin in your DAW of choice.
2. Adjust the lowcut, highcut, and peak filters to your desired settings.
3. Apply the EQ to your audio signal.

# Overview
The EQ with Lowcut, Highcut, and Peak Filter is a simple equalizer built using the JUCE API. It features the following filters:

Lowcut filter: This filter allows you to reduce the levels of frequencies below a certain cutoff point.
Highcut filter: This filter allows you to reduce the levels of frequencies above a certain cutoff point.
Peak filter: This filter allows you to boost or cut a specific frequency band.

Building from Source
To build this EQ from source, you'll need to follow these steps:

Programming Concepts Used
Digital Signal Processing (DSP): DSP concepts were used in the implementation of the lowcut, highcut, and peak filters.
Parameter Control: The user can adjust the parameters of the EQ using a graphical user interface, which involves controlling and manipulating parameters in the code.
JUCE Framework: The JUCE framework was used for building the EQ plugin and its graphical user interface.
