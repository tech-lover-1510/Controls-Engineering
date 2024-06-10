# Controls-Engineering

![GIF](https://github.com/tech-lover-1510/Controls-Engineering/assets/136898779/b9568d09-6dca-40a0-8f7c-f77667be8b9b)

Control engineering is a field that focuses on designing systems to regulate behavior using control loops. It involves both open-loop and closed-loop (feedback) systems to achieve desired performance. Control engineers use sensors, controllers, and actuators to ensure systems operate efficiently and reliably. This discipline is essential in numerous applications, from industrial automation to aerospace engineering. This page mainly focuses on feedback control algorithms and their applications.

## Feedforward Control

### Concept:
Feedforward control involves anticipating disturbances and taking corrective action before the disturbance affects the system. It is a proactive approach that adjusts the control input based on the expected changes in the system or external environment.

### How it works:
The system uses a model to predict the effect of an external disturbance. Based on this prediction, the control input is adjusted to counteract the anticipated disturbance. No actual measurement of the disturbance's impact on the output is required for feedforward control.

### Advantages:
It can significantly improve the system's performance by addressing disturbances before they affect the process. It is useful when disturbances are predictable and can be accurately modeled.

### Disadvantages:
Feedforward control requires an accurate model of the system and the disturbances, which may not always be available. It cannot correct errors that arise from unmodeled disturbances or inaccuracies in the model.

### Example:
In a chemical process, if the flow rate of a reactant changes, a feedforward controller adjusts the flow rate of another reactant in advance to maintain the desired product concentration.

## Feedback Control

### Concept:
Feedback control involves measuring the output of a system and comparing it to the desired setpoint. The control action is based on the error between the actual output and the desired output, aiming to minimize this error.

### How it works:
The system continuously monitors the output. If there is any deviation from the setpoint, the controller takes corrective action to bring the output back to the desired level. Feedback control is reactive, as it responds to errors after they occur.

### Advantages:
It can handle a wide range of disturbances and uncertainties because it corrects errors as they happen. It does not require an accurate model of the system or the disturbances.

### Disadvantages:
There is always some delay between the occurrence of the disturbance and the corrective action, which can lead to temporary deviations from the setpoint. It may not perform well if the system has significant time delays or if the feedback loop is not properly tuned.

### Example:
In a home heating system, a thermostat measures the room temperature (feedback) and turns the heater on or off to maintain the desired temperature setpoint.

## Types of feedback controllers
### Linear
- PID
- Full-state feedback
  
### Non-linear
- On-off
- Sliding mode
  
### Robust
- mu synthesis
- Active synthesis rejection control
  
### Adaptive 
- Extremum-seeking
- Model reference adaptive
  
### Optimal
- Linear Quadratic Regulator
  
### Predictive
- Model Predictive Control
  
### Intelligent
- Fuzzy logic
- Reinforcement learning
