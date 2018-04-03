## Quantum Keypad

All the code can be found in [quantum_keypad/](quantum_keypad/) folder.

Here I used [Raspberry Pi Zero W](https://www.raspberrypi.org/products/raspberry-pi-zero-w/).

## Joystick

All the code can be found in [mouse_controller/](mouse_controller/) folder.

`Server` was launched on MacBook and `client` was launched on [Raspberry Pi 2 Model B](https://www.raspberrypi.org/products/raspberry-pi-2-model-b/).

Raspberry Pi was used as a controller with joystick and water sensor (it simulates the pressing of Space bar).

Here you can find a [video](https://vk.com/video182954756_456239026) of this setup in action.

<table>
    <tr>
        <td>
            <img src="img/img1.jpg" width="500px">
        </td>
        <td>
            <img src="img/img2.jpg" width="500px">
        </td>
    </tr>
</table>


## Additional software

| Name | Description     |
| :------------- | :------------- |
| [Etcher](https://etcher.io)       | Burn [Raspbian images](https://www.raspberrypi.org/downloads/raspbian/) to every Raspberries      |
| [slither.io](http://slither.io)  | Used this game to test my Joystick made with water sensor  |
| [autopy](https://github.com/msanders/autopy/)  | Used for controlling the mouse on my MacBook from Python script. Supports only Python 2 |
| [evdev](https://github.com/gvalkov/python-evdev)  | Python package helped me a lot to read inputs from keypad and turn it into Quantum Keypad. [Here](http://python-evdev.readthedocs.io/en/latest/tutorial.html) one can find awesome tutorial on how to use the evdev  |
| [QISKit](https://www.qiskit.org)   | Quantum simulator to evaluate quantum circuits  |
| [Model Q](https://www.qiskit.org/modelq/)   | Inspired by it :)  |
