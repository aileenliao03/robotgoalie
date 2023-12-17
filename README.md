# Robotic Soccer Goalie: Evaluation of Learning and Physics-Based Controllers for Dynamic Tasks
6.4210 Project. By Aileen Liao and Daniel Prakah-Asante

![Screenshot 2023-12-11 121320](https://github.com/aileenliao03/robotgoalie/assets/92823526/ff92af43-0bc7-4d93-83c8-7ea07a24afd6)

## Project Overview
"Robotic Soccer Goalie" is a research initiative aimed at evaluating various learning and physics-based controllers for dynamic tasks, focusing on a robotic goalkeeper's ability to intercept soccer shots in simulated environments.

## Key Features
- Simulation of a dynamic soccer environment using the Drake framework.
- Implementation of diverse controllers: physics-based, neural network-based, and nueral ode.
- Data collection from simulations to train and evaluate machine learning models.

## Usage
Run the simulation script main.py notebook and modify controllers to test different controllers.

## Controllers
- **Physics-Based**: Utilizing classical mechanics for trajectory predictions.
- **Sampling-Based**: Exploring various trajectories under different spin conditions.
- **Neural Networks**:
  - **RNN**: Predicting blocking positions based on the last three ball positions.
  - **GRU**: Using gated recurrent unit cells to predict blocking positions based on the last three ball positions.
  - **ODE-LSTM**: Combining LSTM with Neural ODEs for dynamic predictions.

## Evaluation
- Controllers are evaluated over 50 simulation episodes.
- Metrics: Success rate in blocking shots under various conditions.

## Conclusions
- Physics-based approaches demonstrated superior performance in dynamic tasks.
- Neural ODEs showed promise for environments with unknown dynamics.

## Future Work
- Investigating Continuous Neural Networks for varied dynamic environments.
- Real-world controller evaluations for practical applicability.

## Acknowledgments
Special thanks to Professor Russell Tedrake, Ethan Yang, and the MIT 6.4210 staff.

## License
This project is distributed under the MIT License. 

## Citation
If you use or reference this project, please cite as follows:

```bibtex
@misc{robotic_soccer_goalie,
  title={Robotic Soccer Goalie: Evaluation of Learning and Physics-Based Controllers for Dynamic Tasks},
  author={Prakah-Asante, Daniel and Liao, Aileen},
  year={2023},
  publisher={GitHub},
  journal={GitHub repository},
  howpublished={\url{https://github.com/username/robotic-soccer-goalie}}
} 

