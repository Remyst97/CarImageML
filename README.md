# CarImageML

This repository contains a C# project that demonstrates how to perform image classification using ML.NET. The project includes a trained model (MLModel1.mlnet) that can be used to classify car images.

CarImageML: Image Classification with ML.NET

This repository contains a C# project that demonstrates multi-class image classification using the ML.NET framework. The project leverages a pre-trained model to classify images of different types of cars.

The model was developed using the ML.NET Model Builder, and this repository includes all the necessary files to either use the pre-trained model for predictions or retrain it on a new dataset.

Technologies

ML.NET: Microsoft's open-source and cross-platform machine learning framework.

C#: The core programming language for the console application.

TensorFlow: Used internally by the ML.NET framework for handling the image classification model.

Project Structure
CarImageML.sln: The Visual Studio solution file that organizes the project.

CarImageML.csproj: The C# project file that defines the project's structure and references.

MLModel1.mlnet: The serialized, trained machine learning model. This is the central piece of the project, used for making predictions.

MLModel1.consumption.cs: An auto-generated class for loading and using the trained model in your code.

Program.cs: The main entry point of the application where the model is loaded and used for a sample prediction.

How to Run the Project

Prerequisites

Visual Studio: You will need Visual Studio with the .NET desktop development workload installed.

.NET Framework 4.7.2: This project targets the .NET Framework 4.7.2, so ensure you have this version installed.
