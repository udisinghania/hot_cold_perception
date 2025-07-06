# Modeling Perception of Hot and Cold Using McCulloch-Pitts Neurons

This project simulates a fascinating physiological phenomenon: the paradox that a short burst of cold is often perceived as heat.

Using McCulloch-Pitts Neurons (MPNs), a foundational model in neural network theory, we build a logic-based model of hot and cold perception using discrete time steps.

## 🧠 Key Concepts:
- Artificial neuron modeled after biological neuron behavior
- Binary logic functions: AND, OR, AND NOT
- Time-dependent activation: transitions from hot to cold

## 🔍 Model Structure
- **X1**: Hot stimulus  
- **X2**: Cold stimulus  
- **Z1, Z2**: Intermediate logic gates  
- **Y1, Y2**: Hot/Cold output neurons

## 🧪 Example Outputs

### Input: `1111`  
→ Output: `hot, cold, cold, cold`

### Input: `1010`  
→ Output: `hot, hot, hot, hot`

## 📓 Run It Yourself
Check out the interactive Jupyter notebook here:  
👉 [Notebook](https://github.com/udisinghania/hot_cold_perception/blob/master/hot_cold_final_interactive.ipynb)

## 📚 References
- McCulloch, W. S., & Pitts, W. (1943). "A logical calculus of the ideas immanent in nervous activity."
