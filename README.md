VisuGAN: Text-to-Video Synthesis for Everyone


VisuGAN is a groundbreaking text-to-video synthesis model designed with a specific focus on accessibility and performance. While traditional models require immense computational power, VisuGAN is optimized to run efficiently on a broader range of hardware, making powerful video generation accessible to users with lower-end GPUs, such as the NVIDIA GeForce GTX 1050 and similar models.
Key Features

    Performance-Optimized: Engineered from the ground up to deliver impressive results on hardware traditionally considered insufficient for video synthesis.

    Intuitive Text-to-Video: Generates dynamic, short-form video content directly from a simple text prompt.

    Advanced Architecture: Utilizes a powerful combination of Transformers for intelligent text encoding and Generative Adversarial Networks (GANs) for high-quality, frame-by-frame video rendering.

    Seamless Video Processing: Incorporates OpenCV for robust and efficient video post-processing, ensuring smooth output.

    Academically Validated: The model's methodology and results have been published in a research paper presented at the INOACC conference and accepted for publication by IEEE.

Getting Started

These instructions will get a copy of the project up and running on your local machine.
Prerequisites

To get started with VisuGAN, you'll need the following installed on your system:

    Python 3.x

    Git

    NVIDIA GPU with CUDA support (GTX 1050 or higher recommended)

    cuDNN

Installation

    Clone the Repository
    Start by cloning the project repository to your local machine using the following command:

    git clone git@github.com:Pixzeyl/SomaiyaAwards-v8-.git

    Navigate to the Project Directory
    Change your current directory to the newly cloned repository:

    cd SomaiyaAwards-v8-

    Create a Virtual Environment
    It's highly recommended to use a virtual environment to manage dependencies.

    python -m venv venv

    Activate the Virtual Environment

        On macOS and Linux:

        source venv/bin/activate

        On Windows:

        .\venv\Scripts\activate

    Install Required Packages
    Install all the necessary libraries using the requirements.txt file:

    pip install -r requirements.txt

Usage

Once the model is installed, you can generate a video by running the main Python script.

python generate.py "A serene beach at sunset with waves gently crashing on the shore."

The generated video file will be saved in the output folder.
Research and Publication

VisuGAN's development is detailed in the research paper titled "VisuGAN: A Lightweight Text-to-Video Synthesis Model." The paper explores the architectural choices and optimization techniques that make the model perform efficiently on lower-end hardware.

    Conference: INOACC, April 2025

    Status: Accepted for publication by IEEE.

Contributing

We welcome contributions! If you would like to improve VisuGAN, please follow the standard GitHub fork and pull request workflow.
License

This project is licensed under the MIT License - see the LICENSE.md file for details.
Acknowledgements

    K. J. Somaiya Institute of Technology for providing resources and support.

    The TensorFlow and OpenCV communities for their incredible tools.
