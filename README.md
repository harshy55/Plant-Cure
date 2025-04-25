
# 🌿 Plant-Cure

**Plant-Cure** is a web-based application designed to assist in the early detection of plant diseases through image analysis. By leveraging deep learning techniques, users can upload images of plant leaves to receive instant diagnoses, aiding in timely and effective plant care.

## 🧠 Features

- **Image-Based Diagnosis**: Upload images of plant leaves to detect potential diseases.
- **Deep Learning Model**: Utilizes a trained convolutional neural network (`PlantDNet.h5`) for accurate predictions.
- **User-Friendly Interface**: Simple and intuitive web interface built with Flask.
- **Responsive Design**: Accessible across various devices for on-the-go diagnostics.

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.6 or higher
- pip (Python package installer)

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/harshy55/Plant-Cure.git
   cd Plant-Cure
   ```

2. **Create a Virtual Environment (Optional but Recommended)**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**

   ```bash
   python app.py
   ```

   The application will start on `http://127.0.0.1:5000/`. Open this URL in your browser to use Plant-Cure.

## 🖼️ Usage

1. Navigate to the homepage.
2. Click on the "Upload" button to select an image of a plant leaf.
3. Submit the image to receive a diagnosis indicating the health status of the plant.

## 🗂️ Project Structure

```
Plant-Cure/
├── static/             # Static files (CSS, JS, images)
├── templates/          # HTML templates
├── uploads/            # Directory to store uploaded images
├── PlantDNet.h5        # Trained deep learning model
├── app.py              # Main Flask application
├── requirements.txt    # Python dependencies
├── Procfile            # For deployment (e.g., Heroku)
└── runtime.txt         # Specifies Python runtime version
```

## 🧪 Model Information

The `PlantDNet.h5` file is a pre-trained convolutional neural network model tailored for plant disease detection. It has been trained on a diverse dataset of plant leaf images to ensure accurate and reliable predictions.

## 🌐 Deployment

To deploy Plant-Cure on platforms like Heroku:

1. Ensure `Procfile` and `runtime.txt` are correctly configured.
2. Push the repository to your Heroku app.
3. Set up necessary buildpacks and environment variables.
4. Deploy the application.

*Note: Detailed deployment instructions can be added based on the chosen platform.*

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch:

   ```bash
   git checkout -b feature/YourFeature
   ```

3. Commit your changes:

   ```bash
   git commit -m 'Add your feature'
   ```

4. Push to the branch:

   ```bash
   git push origin feature/YourFeature
   ```

5. Open a pull request detailing your changes.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 📬 Contact

For questions or suggestions, feel free to reach out:

- GitHub: [@harshy55](https://github.com/harshy55)
