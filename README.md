# Spider Clock

A spider-themed analog clock built using HTML, CSS, JavaScript, and SVG graphics. The project combines a gothic aesthetic with animated mechanical gears and a glowing spider centerpiece.

## Features

* Real-time analog clock
* Animated hour, minute, and second hands
* Three continuously rotating decorative gears
* SVG spider at the center of the clock
* Glowing amber-on-black gothic design
* Responsive positioning using CSS

## Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* SVG Graphics

## Project Structure

```
spider-clock/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

## How It Works

### Clock Logic

The clock uses JavaScript's `Date` object to obtain the current time.

* Seconds: 6° per second
* Minutes: 6° per minute + smooth movement from seconds
* Hours: 30° per hour + smooth movement from minutes

The clock hands are rotated using CSS transforms.

### Gear Animation

Three SVG gears rotate continuously using CSS animations.

```css
@keyframes spin{
    from{transform:rotate(0deg);}
    to{transform:rotate(360deg);}
}
```

Some gears rotate in opposite directions to create a mechanical appearance.

### Spider Design

The spider is created entirely with SVG shapes:

* Ellipse for the abdomen
* Circle for the head
* SVG lines for the legs

The spider is positioned at the center of the clock and highlighted with a glowing effect.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/spider-clock.git
```

2. Open the project folder.

3. Launch `index.html` in a web browser.

No additional dependencies are required.


