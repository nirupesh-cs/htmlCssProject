# htmlCssProject
Html Css learning projects

    This project on designing flags of 3 nations reflects the usage of postioning properties , flex (one dimensional layout) property and parent child relationships among objects .

project-root/
│
├── index.html
├── flags.css
└── README.md

 Japan Flag Design
        Structure:
            One rectangular container for the flag
            One circular div inside it

        Implementation Details:
            The flag container is a white rectangle (450px × 300px)
            A red circle is created using border-radius: 100%
            The circle is perfectly centered using absolute positioning
            The container uses position: relative to keep the circle aligned

        CSS Concepts Used:
            Relative & absolute positioning
            Circular shapes using border-radius

Sweden Flag Design
        Structure:
            One rectangular container
            Two rectangular divs forming the cross

        Implementation Details:
            Blue background represents the base of the flag
            A yellow vertical bar and a yellow horizontal bar create the Nordic cross
            Cross bars are positioned absolutely inside the flag container
            Dimensions are calculated manually to match the real Swedish flag

        CSS Concepts Used:
            Layering with absolute positioning
            Vertical and horizontal alignment

Laos Flag Design
        Structure:
            Three horizontal sections using reusable .box class
            A white circle inside the middle section

        Implementation Details:
            Top and bottom sections are red
            Middle section is blue and uses Flexbox to center the white circle
            The circle represents the central emblem of the flag
            Flexbox ensures perfect horizontal and vertical centering

        CSS Concepts Used:
            Flexbox (justify-content, align-items)
            Reusable classes
            Circle creation with border-radius


