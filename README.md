# :robot: Transistor Demonstration 

[toc]

## 🤓 Overview and learning outcomes 

The goal of this lab assignment is to automate the switching of a higher voltage circuit from a lower voltage circuit.  This is one of the primary uses of a transistor.  By the end of this assignment you will be able to explain how a transistor switch is activated as well as design a circuit using a sensor of your choosing to activate that switch.  While we will ultimately just turn on a 12V LED strip, this could be applied to many different applications in the future. 🚀

### Transistor Background

If you need to, review our class resources on transistors to make sure you are familiar with how these devices work.  Two great resources are our [All About Circuits Textbook section on semiconductors](https://www.allaboutcircuits.com/textbook/semiconductors/) and the [Transistors Explained video from The Engineering Mindset](https://www.youtube.com/watch?v=J4oO7PT_nzQ). You should think about how you will create a small voltage which is appropriate to activate the transistor (0.7V - 1.0V) from the sensor of your choosing.  This will require some testing before moving on.  In addition, you will explain mathematically how you adjusted the voltage to the appropriate level.  Once that is solved it should be very simple to build the circuit to control the LEDs.

### Break the Problem Down into Smaller Parts

You are essentially building two circuits as described here.

- A Sensor Circuit to Control Your Switch
  - Choose any sensor you would like (except a simple button, SPDT switch or potentiometer).
  - If it is an analog sensor determine what modifications you need to make to the circuit to activate the switch and not exceed the maximum voltage of 1.0V for that side of the circuit.
  - If it is a digital sensor determine how to wire it to trigger the circuit when a `true` value is made on that circuit.
  - You will need to create a voltage divider either using your sensor as one of the resistors or adding one after the sensor in series to accomplish this.

- An Actuator Circuit Including Your 12V LED Strip
  - Pick a transistor which accomplishes the task.  You might need to predict current through the circuit first before choosing the correct transistor.  It s also recommended that you use a potentiometer in your sensor circuit first for testing and then switch your sensor in.
  - Wire a 12V battery into this circuit to turn on the LEDs.
 
This diagram shows the general concept of what you are doing:

![circuit](https://github.com/stcline/re-4-1-0-Transistor_Demonstration/assets/22602103/2f2eaa12-61ff-4dbe-8a15-a191631986b4)

NOTE: V<sub>1</sub>, V<sub>2</sub>, V<sub>OUT</sub> and the 12V LEDs are immutable.  Your solution must include them.  You must also use a transistor and some sensor which meets the parameters above.

## 💻 Terms to know

- Transistor
- Bipolar Junction Transistor (BJT)
- Field Effect Transistor (FET)
- Voltage Divider
- Sensor
- Actuator

## 📝 Next steps

1. Make an `observations.md` file here to include all of your explanaitions.  Take notes during this process and write them up in an easily understandable description.
2. Choose your sensor.  Find the datasheet or some other well written description of that sensor on the internet.  Describe why you chose this sensor. Include the output voltage of this sensor (or range of output voltages) in your description and if this is an analog or digital sensor.  Describe how you will convert this voltage to the appropriate range (0.7-1.0V).  Include the formula needed to determine this and solve it to demonstrate that you are correct. Don't forget to do this testing using a multimeter.
3. Using the datasheet for your transistor, predict the current gain for the actuator circuit using this transistor.
4. Draw the circuit either using graph paper or an online circuit designer software like [CircuitLab](https://www.circuitlab.com/editor).  This should include your sensor, necessary voltage divider and the 
5. Measure the current of your actuator circuit when it is activated and compare it to your answer in step 3.  Determine if you were correct in your prediction and why you might have been wrong.
6. Create a full list of all components used in your design and include a section in the description for this.
7. Proofread your observations for content, grammar, punctuation and usage.  Include all requirements listed here. Try to show your math inside the `.md` file by using LaTeX expressions.  More details on how to do this may be found [here](https://support.typora.io/Math/)
8. Be prepared to demonstrate what you learned to the class.

## 📚  Resources 

- [All About Circuits Textbook section on semiconductors](https://www.allaboutcircuits.com/textbook/semiconductors/)
- [Transistors Explained video from The Engineering Mindset](https://www.youtube.com/watch?v=J4oO7PT_nzQ)
- How to read a datasheet
- [LaTeX Expression Math in Markdown](https://support.typora.io/Math/)
- Sample video demonstration
