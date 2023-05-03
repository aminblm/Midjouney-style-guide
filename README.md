# Midjouney-style-guide

A compact style guide for Midjourney.

MidJourney Styles is an AI-powered image generator that allows you to create stunning images by using a variety of parameters. In this guide, we will provide a list of the parameters and what they mean, along with examples for each of them.

## Midjourney Parameters 

The parameter list below explains the various options and their examples that can be used with Midjourney, an image generation tool:

### Light:
Midjourney uses parameters that are added to the end of the prompt and change how an image generates. You can add multiple parameters to each prompt. Below are some examples of Midjourney parameters:

### Basic Parameters:

* Aspect Ratios: --aspect or --ar (e.g., --aspect 1:1 changes the aspect ratio to a square).
* Chaos: --chaos <number 0-100> (e.g., --chaos 50 changes how varied the results will be).
* No: --no (e.g., --no plants removes plants from the image).
* Quality: --quality <.25, .5, 1, or 2> or --q <.25, .5, 1, or 2> (e.g., --quality .5 sets the rendering quality to a lower level).
* Repeat: --repeat <1-40> or --r <1-40> (e.g., --repeat 3 creates three jobs from a single prompt).
* Seed: --seed <integer between 0-4294967295> (e.g., --seed 12345 uses 12345 as the seed number for generating the initial image grids).
* Stop: --stop <integer between 10-100> (e.g., --stop 30 finishes a job partway through the process).
* Style: --style <4a, 4b, or 4c> or --style <cute, expressive, or scenic> (e.g., --style 4b switches to Midjourney Model Version 4b).
* Stylize: --stylize <number> or --s <number> (e.g., --stylize 500 applies Midjourney's default aesthetic style to the image more strongly).
* Tile: --tile (e.g., --tile generates images that can be used as repeating tiles to create seamless patterns).
* Uplight: --uplight (e.g., --uplight uses an alternative "light" upscaler when selecting the U buttons).
* Upbeta: --upbeta (e.g., --upbeta uses an alternative beta upscaler when selecting the U buttons).

#### Default Values (Model Version 4):

* Aspect Ratio: 1:1
* Chaos: 0
* Quality: 1
* Seed: Random
* Stop: 100
* Style: 4c
* Stylize: 100

#### Default Values (Model Version 5):

* Aspect Ratio: 1:1
* Chaos: 0
* Quality: 1
* Seed: Random
* Stop: 100
* Stylize: 100

#### Model Version Parameters:

* Niji: --niji (e.g., --niji switches to an alternative model focused on anime style images).
* High Definition: --hd (e.g., --hd uses an early alternative model that produces larger, less consistent images).
* Test: --test (e.g., --test uses the Midjourney special test model).
* Testp: --testp (e.g., --testp uses the Midjourney special photography-focused test model).
