#Calculator Bot for Volume and Surface Area of 3D Shapes
Introduction
This is a PHP script for a Telegram bot that calculates the volume and surface area of various 3D shapes. Users can interact with the bot by sending specific commands in the format /shape_parameters to get the corresponding volume or surface area.

Getting Started
To use this bot, follow these steps:

Bot Token: Replace the placeholder Your_Bot_Token in the code with your actual Telegram bot token. You can obtain a bot token by creating a new bot on Telegram and obtaining the token from BotFather.

php
Copy code
$botToken = "Your_Bot_Token";
Setting Up Webhook: If you plan to deploy this script on a web server, set up a webhook URL in your Telegram bot settings pointing to the location of your script.

Commands: The bot recognizes various commands in the format /command_parameters. For example:

php
Copy code
/volume_kubus_5
This command calculates the volume of a cube with a side length of 5.

Supported Commands
The bot supports the following commands:

Volume of Cube: /volume_kubus_[side_length]
Volume of Rectangular Prism: /volume_balok_[length]_[width]_[height]
Volume of Sphere: /volume_bola_[radius]
Volume of Cylinder: /volume_tabung_[radius]_[height]
Volume of Cone: /volume_kerucut_[radius]_[height]
Volume of Triangular Prism: /volume_prisma_segitiga_[length]_[area]_[height]
Volume of Triangular Pyramid: /volume_limas_segitiga_[side_a]_[side_b]_[height]
Volume of Square Pyramid: /volume_limas_segiempat_[side_length]_[height]
Diagonal of Rectangular Prism: /diagonal_ruang_balok_[length]_[width]_[height]
Surface Area of Cube: /luas_permukaan_kubus_[side_length]
Surface Area of Rectangular Prism: /luas_permukaan_balok_[length]_[width]_[height]
Surface Area of Sphere: /luas_permukaan_bola_[radius]
Surface Area of Cylinder Base: /luas_alas_tabung_[radius]
Surface Area of Cone: /luas_permukaan_kerucut_[radius]_[slant_height]
Surface Area of Triangular Prism Base: /luas_alas_prisma_segitiga_[base_length]_[height]
Surface Area of Triangular Pyramid Base: /luas_selubung_limas_segiempat_[base_length]_[height]
Perimeter of Triangular Prism Base: /keliling_alas_prisma_segitiga_[side_length]
Surface Area of Triangular Prism Base: /luas_alas_prisma_segitiga_[base_length]_[height]
Surface Area of Triangular Pyramid Base: /luas_alas_limas_segitiga_[base_length]_[height]
Surface Area of Triangular Pyramid Slant Height: /luas_selubung_limas_segitiga_[base_length]_[height]
Usage
Send /start to get a list of available commands and their formats.
Use any of the supported commands with the specified parameters to get the calculated results.
Example
For instance, to calculate the volume of a cube with a side length of 5, send the following command:

php
Copy code
/volume_kubus_5
The bot will respond with the calculated volume of the cube.

Credits
This bot was developed by [Your Name].
References for mathematical formulas are provided in the code comments.
Feel free to contribute, report issues, or enhance the functionality of this bot. Happy calculating! 📐🤖