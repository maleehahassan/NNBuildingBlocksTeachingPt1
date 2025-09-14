# Neural Networks Building Blocks - Train the Trainer Workshop

A comprehensive 90-minute workshop teaching the fundamental building blocks of neural networks. This repository contains interactive Jupyter notebooks designed for Google Colab execution, making it accessible without any local installation requirements.

## Workshop Overview

This train-the-trainer workshop covers the essential concepts that every neural network practitioner should understand:

1. **General Overview of Supervised Learning** (~20 minutes)
   - Introduction to machine learning paradigms
   - Supervised learning concepts and real-world applications
   - Classification vs regression problems

2. **The First Perceptron** (~20 minutes)
   - Historical context and motivation
   - Mathematical foundation and implementation
   - Understanding limitations (XOR problem)

3. **Activation Functions** (~20 minutes)
   - Role in neural networks and why they matter
   - Common functions: sigmoid, tanh, ReLU and variants
   - Impact on learning and performance

4. **Loss Functions** (~20 minutes)
   - Understanding optimization objectives
   - Regression vs classification loss functions
   - Choosing the right loss for your problem

5. **Hands-on Exercises** (~10 minutes)
   - Building a complete neural network from scratch
   - Interactive experiments with different components
   - Solving the XOR problem

## Technical Setup

### For Participants

**Recommended Setup (No Installation Required):**
- Google account for accessing Colab
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Stable internet connection

**Optional Local Setup:**
```bash
# If you prefer to run locally
pip install jupyter matplotlib numpy scikit-learn pandas
git clone https://github.com/maleehahassan/NNBuildingBlocksTeachingPt1.git
cd NNBuildingBlocksTeachingPt1
jupyter notebook
```

### For Trainers

**Pre-Workshop Preparation:**
1. Review all notebooks thoroughly
2. Test Google Colab links
3. Prepare backup materials in case of technical issues
4. Ensure stable internet connection
5. Have a local copy as backup

**Building the Jupyter Book (Optional):**
```bash
# Install Jupyter Book
pip install jupyter-book

# Build the book
jupyter-book build .

# View locally
open _build/html/index.html
```

## Getting Started

### Option 1: Google Colab (Recommended)
Each notebook has a "Open in Colab" badge at the top. Simply click it to launch the notebook directly in Google Colab with all dependencies pre-installed.

### Option 2: Local Jupyter
1. Clone this repository
2. Install dependencies: `pip install -r requirements.txt`
3. Start Jupyter: `jupyter notebook`
4. Navigate to the content folder

### Option 3: Jupyter Book
View the complete workshop as an interactive book:
- [Online Book](https://maleehahassan.github.io/NNBuildingBlocksTeachingPt1) (if deployed)
- Or build locally using the instructions above

## Workshop Structure

```
📚 Neural Networks Building Blocks Workshop
├── 📖 Introduction & Overview
├── 📓 01_supervised_learning_overview.ipynb
├── 📓 02_first_perceptron.ipynb  
├── 📓 03_activation_functions.ipynb
├── 📓 04_loss_functions.ipynb
└── 📓 05_hands_on_exercises.ipynb
```

## Learning Objectives

By the end of this workshop, participants will:
- ✅ Understand fundamental supervised learning concepts
- ✅ Know how perceptrons work and their historical significance  
- ✅ Grasp the role and types of activation functions
- ✅ Understand loss functions and optimization
- ✅ Have hands-on experience building neural networks
- ✅ Be able to solve the XOR problem (that stumped early AI!)

## Prerequisites

- **Required**: Basic mathematical understanding (high school level)
- **Helpful**: Familiarity with Python syntax
- **Bonus**: Curiosity about machine learning and neural networks!

No prior machine learning experience is needed - we start from the fundamentals.

## Repository Contents

### Core Workshop Materials
- `intro.md` - Workshop introduction and overview
- `content/` - Interactive Jupyter notebooks for each section
- `_config.yml` - Jupyter Book configuration
- `_toc.yml` - Table of contents structure

### Configuration Files
- `_config.yml` - Jupyter Book settings with Google Colab integration
- `_toc.yml` - Workshop content organization
- `requirements.txt` - Python dependencies (auto-generated)

## Features

### 🎯 Interactive Learning
- All notebooks are fully interactive with code examples
- Visualizations help build intuition
- Progressive complexity from basic concepts to implementation

### 🚀 Google Colab Ready
- One-click access to all notebooks
- No installation required
- Runs in the browser with GPU support

### 📊 Rich Visualizations
- Custom plots and animations
- Decision boundary visualizations
- Learning curve analysis
- Comparative studies

### 🧪 Hands-on Experiments
- Build neural networks from scratch
- Compare different activation functions
- Experiment with loss functions
- Solve classic problems like XOR

## Troubleshooting

### Common Issues

**Google Colab Connection Problems:**
- Check internet connection
- Try refreshing the page
- Clear browser cache
- Try incognito/private browsing mode

**Notebook Won't Load:**
- Verify the GitHub link is correct
- Try opening in a new tab
- Check if GitHub is experiencing issues

**Code Execution Errors:**
- Make sure to run cells in order
- Restart runtime if needed: Runtime → Restart runtime
- Check for any typos in modified code

### Getting Help

1. **During Workshop**: Ask the trainer or teaching assistants
2. **GitHub Issues**: Open an issue for bugs or improvements
3. **Community**: Join relevant ML/AI communities for ongoing support

## Contributing

We welcome contributions to improve the workshop materials!

### Ways to Contribute
- 🐛 Report bugs or issues
- 📝 Improve documentation
- 💡 Suggest new examples or exercises
- 🎨 Enhance visualizations
- 🌍 Add translations

### How to Contribute
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This workshop is released under the MIT License. Feel free to use, modify, and distribute for educational purposes.

## Acknowledgments

- Built with [Jupyter Book](https://jupyterbook.org/)
- Compatible with [Google Colab](https://colab.research.google.com/)
- Inspired by classic neural network literature and modern best practices

## Citation

If you use these materials in your teaching or research, please cite:

```bibtex
@misc{nn_building_blocks_2024,
  title={Neural Networks Building Blocks: Train the Trainer Workshop},
  author={Hassan, Maleeha},
  year={2024},
  url={https://github.com/maleehahassan/NNBuildingBlocksTeachingPt1}
}
```

---

**Ready to dive into neural networks? Start with the [Workshop Introduction](intro.md)!** 🚀