
# Calculator Bot for Volume and Surface Area of 3D Shapes



## Introduction

This is a PHP script for a Telegram bot that calculates the volume and surface area of various 3D shapes. Users can interact with the bot by sending specific commands in the format /shape_parameters to get the corresponding volume or surface area.


## Getting Started

To use this bot, follow these steps:



## Installation

1. Bot Token: Replace the placeholder Your_Bot_Token in the code with your actual Telegram bot token. You can obtain a bot token by creating a new bot on Telegram and obtaining the token from BotFather.

```php
  $botToken = "Your_Bot_Token";
```

2. Setting Up Webhook: If you plan to deploy this script on a web server, set up a `webhook URL` in your Telegram bot settings pointing to the location of your script. You can just go to the Telegram's API documentations for more detail.



    
## Bot's Command Reference

Use this text command based on parameters `[]` below for calculate 3D shapes on the telegram chat.
#### Get Volume of Cube

```http
  /volume_kubus_[side_length]
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `side_length` | `int` | **Required** The side_length of the cube |

#### Get Volume of Rectangular Prism

```http
  /volume_balok_[length]_[width]_[height]
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `length`      | `int` | **Required** The length of the cube|
| `width`      | `int` | **Required** The width of the cube|
| `height`      | `int` | **Required** The height of the cube|

#### Get Volume of Ball

```http
/volume_bola_[radius]
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `radius`  | `int`    | **Required** - The radius of the sphere. |

#### Get Volume of Cylinder

```http
/volume_tabung_[radius]_[height]
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `radius`  | `int`    | **Required** - The radius of the cylinder base. |
| `height`  | `int`    | **Required** - The height of the cylinder. |

#### Get Volume of Cone

```http
/volume_kerucut_[radius]_[height]
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `radius`  | `int`    | **Required** - The radius of the cone base. |
| `height`  | `int`    | **Required** - The height of the cone. |

#### Get Volume of Triangular Prism

```http
/volume_prisma_segitiga_[length]_[area]_[height]
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `length`  | `int`    | **Required** - The length of the triangular prism. |
| `area`    | `int`    | **Required** - The area of the triangular base. |
| `height`  | `int`    | **Required** - The height of the triangular prism. |

#### Get Volume of Triangular 

```http
/volume_limas_segitiga_[side_a]_[side_b]_[height]
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `side_a`  | `int`    | **Required** - The length of the first side of the triangular base. |
| `side_b`  | `int`    | **Required** - The length of the second side of the triangular base. |
| `height`  | `int`    | **Required** - The height of the triangular pyramid. |

#### Get Volume of Square

```http
/volume_limas_segiempat_[side_length]_[height]
```

| Parameter    | Type     | Description                       |
| :----------- | :------- | :-------------------------------- |
| `side_length`| `int`    | **Required** - The length of the side of the square base. |
| `height`     | `int`    | **Required** - The height of the square pyramid. |

## Usage/Examples
Commands: The bot recognizes various commands in the format `/command_parameters`. For example:
```php
  /volume_kubus_5
```
This command calculates the volume of a cube with a side `length` of `5`.



## Authors

- [@RifkyA911](https://github.com/RifkyA911)


## Credits
This bot was developed by **RifkyA911**.
References for mathematical formulas are provided in the code comments.
Feel free to contribute, report issues, or enhance the functionality of this bot. Happy calculating! 📐🤖

