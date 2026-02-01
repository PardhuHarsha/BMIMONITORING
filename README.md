# BMIMONITORING
drive link : https://drive.google.com/drive/folders/1HmmVYFewSz3MkmhVQ1i3Buptbt1Nc3Ox?usp=sharing

Circuit Diagram and working demo videos are in the drive above.

In the modern world, timely and accessible health monitoring has become increasingly important. BMI remains one of the simplest and most widely accepted metrics for evaluating individual fitness or risk for various health conditions. Yet, the reality is that traditional BMI measurement is often cumbersome, non-interactive, and prone to error or inconsistency. The merging of digital logic with health diagnostics represents a transformative approach—especially in making vital metrics like BMI immediately available, accurate, and easy to interpret.
The system's innovative design centers on logic-based classification. We utilize two 2-bit binary inputs to represent four ranges each for Height and Weight.The 16 possible combinations of these inputs are mapped to the four standard BMI categories: Underweight ({BMI} < 18.5), Normal ({BMI}: 18.5-24.9), Overweight ({BMI}: 25-29.9), and Obese ({BMI} >= 30).
The core processing is achieved through a multi-stage decoding process:
A 4-to-16 Decoder (IC 74154) translates the 4-bit Height and Weight input into 16 unique lines.
OR Gate networks (IC 7432) combine these lines into a concise 2-bit BMI code (Bit1, Bit0), based on derived logic expressions. 
A 2-to-4 Decoder (IC 74139) then decodes the 2-bit BMI code, lighting one of four LEDs to give the user immediate feedback on their status.
This project, "Real-Time BMI Monitoring System," stems from a practical need to simplify and automate BMI determination using foundational combinational circuit design. By encoding weight and height as digital inputs and translating these through decoders, logic gates, and clearly mapped outputs, the system delivers a seamless user experience: the BMI category is instantly illuminated via dedicated LED indicators.
