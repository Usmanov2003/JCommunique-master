JCommunique
JCommunique is a free, open-source library written in pure Java. It uses Swing to show pop-up notifications on the desktop and offers a range of features with a simple-to-use API. Refer to the demo package for examples.

JCommunique is no longer being actively maintained.
Releases
Stable JCommunique releases as jars are available at [2]. As of version 2.0.0, source and javadoc jars are also available. The project is also distributed on JCenter [5].

You can add these to your project's build path just as you would include any normal jar. This process can vary across IDEs, but Eclipse instructions are available at [3].

Building the project
As of version 2.0.0, JCommunique is set up as a Gradle project (previously an Eclipse project). Most of the building can be done using the standard commands provided in the Gradle Java plugin, which are documented extensively online and therefore will not be covered here. To completely test the system, run "gradle build" (will compile, make Javadoc, and run unit tests). To run a demo, use the rundemo.sh script (for Unix machines). Using the terminal, navigate to the directory with rundemo.sh in it and run "sh rundemo.sh NAME_OF_DEMO". For example, to run the SlideManagerDemo.java demo, use the command "sh rundemo.sh SlideManagerDemo".
