# Rotate Image tool

Basic tools which rotates vertically an image with a well determinate background & foreground. (example a bill(a white piece of paper) with a black background)

## Requirements / Installation

- Ensure you have **python3** and **pipenv**
- git clone this repo
- cd into this repo
- Run the following command

```bash
pipenv install
pipenv shell
```

### Usage

After cloning the project make the script executable by running

```bash
chmod +x rotate
```

And you can rotate the example image included in the project as follows:

```bash
./rotate --image ./example.png
```

#### Original Image

![Original](example.png "Original Image")

#### Output

![Output](example_output.png "Result")
