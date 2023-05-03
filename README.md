# Midjouney-style-guide

A compact style guide for Midjourney.

MidJourney Styles is an AI-powered image generator that allows you to create stunning images by using a variety of parameters. In this guide, we will provide a list of the parameters and what they mean, along with examples for each of them.

🎇 **--stylize Parameter**
The Stylize Parameter will make your image more stylized. This parameter is available in MidJourney V3, V4, and V5.

Here is a list of stylize parameters available in MidJourney V4:
--stylize 0
--stylize 100
--stylize 200
--stylize 300
--stylize 400
--stylize 500
--stylize 600
--stylize 700
--stylize 800
--stylize 900
--stylize 1000

Example usage: --stylize 500

💎 **--quality Parameter**
The Quality Parameter will define how long the AI spends creating your image. This parameter is available in MidJourney V1, V2, V3, V4, and Niji Journey.

Here is a list of quality parameters available in MidJourney V4:
--quality 0.25
--quality 0.5
--quality 1 (default)
--quality 2
--quality 5

Example usage: --quality 2

🌪 **--chaos Parameter**
The Chaos Parameter will add more "randomness" to your images. In practice, it seems to make them more stylized. This parameter is available in MidJourney V1, V2, V3, V4, and Niji Journey.

Here is a list of chaos parameters available in MidJourney V4:
--chaos 0
--chaos 10
--chaos 20
--chaos 30
--chaos 40
--chaos 50
--chaos 60
--chaos 70
--chaos 80
--chaos 90
--chaos 100

Example usage: --chaos 50

🚫 **--no Parameter**
The No Parameter will tell the AI to prevent adding a specific thing to an image. This parameter is available in MidJourney V1, V2, V3, and V4.

Here is an example of how to use this parameter to remove the "sphere" from an image:
sphere --no sphere

You can also remove multiple items at once by using the format --no input1, input2. For example:
sphere, Colorful --no red, pink

🔲 **--tile Parameter**
The Tile Parameter allows you to create a tiled 3x3 grid of the image. This parameter is available in MidJourney V1, V2, V3, and V5.

Here is an example of how to use this parameter:
sphere --tile

🏋️‍ **Image Weight Comparison**
The Image Weight Parameter changes how much an inputted image will affect the generated image. This parameter is available in MidJourney V2 and V3.

Here is an example of how to use this parameter:
Bubble Design --iw 0.5

⌨ **Prompt Format Comparison**
The Prompt Format Parameter allows you to customize the format of the prompt you use to generate images. This parameter is available in MidJourney V1, V2, V3, and V4.

Here is an example of how to use this parameter:
<style> - <style-2>
