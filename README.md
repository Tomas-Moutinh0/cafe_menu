# cafe_menu
A cafe menu for a coffeshop. This project was part of freecodecamp web design course. However, since the display of the flavours/desserts and their prices wasn't working when I used:

".item p {
  display:inline-block;
}

I made a small changed to the CSS, by deleting this property and used:

"item {
  display: flex;
  flex-direction: row;
}