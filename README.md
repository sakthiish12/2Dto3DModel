# 3D Model Generator From 2D Floorplans

This is a web application that takes 2D floor plans as input and generates 3D models as output. This is achieved by using machine learning and image recognition techniques.

## Technologies

- Frontend: HTML, CSS, JavaScript, React.js, Three.js / Babylon.js
- Backend: Python (Django) / JavaScript (Node.js), TensorFlow / PyTorch
- Database: MongoDB
- Hosting: AWS

## Getting Started

### Prerequisites

- Node.js
- Python
- MongoDB
- AWS CLI

### Installing

1. Clone the repository
2. Install the dependencies with `npm install` (for Node.js) or `pip install -r requirements.txt` (for Python)
3. Set up your MongoDB database
4. Configure your AWS credentials

## Development Plan

**Phase 1: Data Collection and Neural Network Training** _(ongoing)_

- Collect 2D floorplan images and corresponding 3D models for training data
- Implement a neural network using TensorFlow / PyTorch
- Train the neural network with the collected data

**Phase 2: Backend Development** _(approx. 1-2 months)_

- Set up the Django or Node.js backend
- Implement the API endpoints required for the frontend
- Integrate the trained model with the backend

**Phase 3: Frontend Development** _(approx. 1-2 months)_

- Set up the React.js frontend
- Implement the 3D visualization using Three.js / Babylon.js
- Connect the frontend with the backend

**Phase 4: Testing and Deployment** _(approx. 1 month)_

- Perform extensive testing to ensure everything is working as expected
- Deploy the application on AWS

**Phase 5: Maintenance and Updates** _(approx. 2-3 months)_

- Monitor the application for any issues
- Continually improve the model based on user feedback

## Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for more details.

## License

This project is licensed under the [MIT License](LICENSE.md).
