# IOT

# Abstract
As we, all know there are lots of disabled peoples in our worlds and the health service sector
is making continuous efforts to improve the service to make easy mobility for these peoples.
In the growing technology, many developers are coming up with different ideas of robotic
wheelchairs. These are wheelchairs, which can easily direct the patient from one place to
another by simple means of controlling. They have sensors embedded in them to navigate and
detect the necessary obstacles. Here I have developed an intelligent wheelchair, which can be
controlled by the voice command of the patient and can be easily directed to the desired place.
Unlike other voice command system, which uses simple voice module, I have used the feature
of IOT to enhance the functionality of the wheelchair. It consist of a raspberry pi, dc motors,
relays, and the use of IFTTT server. IFTTT is used to make the trigger and response applets,
which will help the microcontroller to analyse which code is to be executed at the given time.

# Methodology
A main control unit will control the wheelchair. The main control unit consist of a raspberry pi
4. It is been integrated with a motor shield drive so that the motors can be controlled in both
the directions without altering the connections. Then the commands has to be prepared which
is been made possible by making applets in the IFTTT. This applets works as trigger packets.
When a specific command is given, it triggers the applet, which sends a response to the IOT
server, which will be received by our microcontroller. These applets will work on the basis of
coding we have made in a platform called Particle.io. This platform can be easily integrated
with the raspberry pi and the codes can be flashed in the microcontroller very easily. So a
program is been written in the particle.io web ID and is been trigger set by the applets. So when
a command is been given it will see the response code for that specific command and will
instruct the microcontroller to initiate that code. This initiation of code will help the rotation of
motor in specific direction, which will in turn make the wheelchair move. These codes can be
initiated by giving the command in the user’s mobile phone itself, which makes the
functionality for user easier. 

# the rest of the steps are inside the pdf in the repository. care free to refer
