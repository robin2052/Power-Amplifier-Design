# Circuit
<img width="1263" height="695" alt="image" src="https://github.com/user-attachments/assets/8440608d-7100-457f-85e8-aace68919d2e" />

| vdd=600m | vbias=500m |L=100n | w= 1u*50 MUL|

# At First this was the Circuit stability Condition.
<img width="1750" height="779" alt="image" src="https://github.com/user-attachments/assets/e85eb496-7d9e-43b7-b603-16464386e0d9" />

# L changed to 100fH from 1mH . each of the inductors value is same.
<img width="1759" height="800" alt="image" src="https://github.com/user-attachments/assets/035c3823-4ad1-431a-8c09-e3d184347f3d" />

The stability improves when I made those 1mH transistors to 100fH. The possible reason for this occurrence can be resonance. When the inductance is decreasing, the resonance also decreases for that inductor. So the stability condition improves. But as the transistor's inductor value is less, it may not be able to choke those high frequencies that it could have done before . So the gain may decrease. From the S parameter, we are seeing that the input and output reflection increase when we make the inductor's value low. 
# Bias resisor changes in different value

<img width="1279" height="677" alt="image" src="https://github.com/user-attachments/assets/202f2ecc-d61c-4e6d-8f3a-dd3a83c0a208" />

<img width="853" height="348" alt="image" src="https://github.com/user-attachments/assets/5400865c-99d7-4386-a23a-f60e8191d0df" />



when the resistor was removed the mu value becomes less than 1  but the k value was large. it is unstable .  Here in the s parameter we are seeing that s21 is so less. that means it cannot amplify the power . s11 is also very bad . that means most of the power is reflected back and hence the circuit is becoming unstable.


<img width="1722" height="760" alt="image" src="https://github.com/user-attachments/assets/0f168178-1419-4457-8b69-9f1251ec7fd6" />

When a resistor of 100ohm is added the circuit becomes stable .

<img width="1712" height="743" alt="image" src="https://github.com/user-attachments/assets/cd60a7e6-ad9f-4139-9855-8a20d8d986b4" />

when The resistor value is increased the circuit started to become less stable. I mean the circuit is still stable but the value of k decreased.

<img width="1711" height="736" alt="image" src="https://github.com/user-attachments/assets/fd1a75c8-c300-40e7-a1f3-296bf92cc7e8" />

when the resistor value is further increased to 600 0hm the circuit become  unstable again. At that moment i  increased the bias voltage , the circuit become stable again at a bias voltage of 800mV. i tried to stable the gain with another way like increasing the vdd . but i have seen that increasing the voltage of Vdd the value of k further decreases.




