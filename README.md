# titlting-card
<h2>This is a project test where i make a card there is able to tilt by hovering the mouse on it. And it's all made with CSS, there is no use of Javascript what so ever ! </h2>

<p>This is how i did it :</p>
<ul>
<li>First we need to create a <code>div</code> wrapper</li>
<li>Then we need to create 9 different <code>div's</code> inside the div wrapper. We can optimize our time by putting a dot in the beggining, the name of the div,  put the * sign and the number of how many times you want to duplicate the div's, then press the Tab key in your keyboard: <code>.div_name*9</code> <kbd>TAB</kbd> .</li>
<li>After creating the div's, we need to set the grid. The grid cell's will be 9 div's created previously. These div's will be the set as the elements which will be implemented the <code>:hover</code> interactions.  </li>

  ![image](https://user-images.githubusercontent.com/58955082/200633305-c5be5994-e185-4087-a7db-bb29489b7c69.png)

<li>Now we set each grid cell individualy by using the <code>:nth-child():hover</code> property, and then finally setting a angle for the tilt
   <p><code>--rotateX:var(--angle);</code></p>
   <p><code>--rotateY: calc(var(--angle)*-1);</code></p>
</li>
</ul>
