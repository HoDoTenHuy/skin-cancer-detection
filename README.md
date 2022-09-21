# Skin Cancer Lesion Classifier

The repository is a Detector project that allows you to detect Skin Cancer Lesions using Heroku easily.

- [x] Image file available
- [ ] Video file available

## Table of Contents

- [Structure](#Structure)
- [Usage](#Usage)
- [License](#License)

## Structure
- Dataset: Skin Cancer MNIST: HAM10000
- Model
  - Detection

## Usage

1. Clone This Repository

   ```sh
   $ git clone https://github.com/HoDoTenHuy/skin-cancer-detection.git
   ```

2. Upload to heroku

   ```sh
   $ heroku container:login
   $ heroku create skin-cancer-detection
   $ heroku container:push web --app skin-cancer-detection
   $ heroku container:release web --app skin-cancer-detection
   $ heroku container:scale web=1 --app skin-cancer-detection
   ```

3. Visit app on Heroku

- visit [https://skin-cancer-detection.herokuapp.com/](https://skin-cancer-detection.herokuapp.com/)

4. Run app

- Select image on local : your image
- Click 'Submit Button'

License
----

MIT