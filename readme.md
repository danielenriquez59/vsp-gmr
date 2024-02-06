# OpenVSP Git Model Repo (GMR)

This repository is a collection of OpenVSP models that you can download and use in your projects.
This is a temporary solution to allow the community to continue to have share open source models.

## What is OpenVSP?

OpenVSP (Vehicle Sketch Pad) is a geometry modeling tool for conceptual aircraft design. The models in this repository are in the `.vsp3` format, which is the native format for OpenVSP. [Download it here](https://openvsp.org/download.php)

## How to Download Models

Clone the repository to your machine and you should have access to all the files.

## How to Push Models

If you have a model that you'd like to contribute to the repository, we'd love to have it! Here's how you can do it:

1. Fork this repository.
2. Add your `.vsp3` model file in a folder with the model name. See the examples already in the folder.
3. create a README.md file in the folder with the following information:

- Model Name
- Description
- Model fidelity:

  1. Definitive. This means the VSP model is the definition of the vehicle or part (it was built from the model or the model is the best source of infromation available).
  2. Essentially Exact
  3. Good. This means good 3-view drawings were used to create the model.
  4. Inaccurate
  5. Completely Inaccurate. This means the creator thought of the vehicle or part as he or she made the model, but did not use any pictures or drawings and had no dimensions.

- Author Name (Optional)
- Email (Optional)
- Additional References Used to Create the Model
- MIT License file

4. Create a pull request.

Please make sure that your model is in the `.vsp3` format before submitting it. At this time we will only approve PR that have
only .vsp3 files.

## Contributing

We welcome contributions from everyone.

## MIT License Text

`MIT License

Copyright (c) 2024 [fullname]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.`
