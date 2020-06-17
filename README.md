# React Components

You've been asked to refactor the products and services section of your clients web site using React.  The section is beautifully designed and looks like the following:

![Products Section](https://i.imgur.com/ISNryqG.png)

The entire section is using one large block of static HTML to render all of the content and structured as `ul > li`

```html
<ul>
  <li class='ItemContainer'>
    <a href="#">
        <div class="ImageContainer"><i class="far fa-heart fa-2x"></i></div>
        <div class="ItemContentContainer">
          <h4 class="ItemHeader">Wedding Vision</h4>
          <p class="ItemHeading">Define your wedding style and get matched with local vendors.</p>
        </div>
    </a>
  </li>
</ul>
```

## Instructions

1. Fork this [codesandbox](https://codesandbox.io/s/theknot-starter-repo-wwgqw?file=/src/App.js)
1. Fulfill the listed requirements.
1. Submit the assignment using the submission form

## Requirements

1. Examine the html in <b>public/index.html</b> as it contains 
the all the static HTML and when your ready to begin comment all the code. 
1. Create a <b>data.js</b> file in **src** folder. In the **data.js** file create a new array called **products** and then within it create an object for each product using the data for that product found in the associated li. 
2. Import **data.js** into **App.js** and pass the array as props to the **ProductList** Component
3. The **ProductList** Component will map over the array and pass the data for that product to the **Product** Component
4. The **Product** Component will then return an li based the HTML provided replacing the static value with the data passed down as props

Your desing must include the following Components:
  <ul>
  <li>ProductList</li>
  <li>Product</li>
  <li>ProductIcon</li>
  <li>ProductInfo</li>
  </ul>
          
And follow this React heirarchy:

![Cool Looking Dashboard](https://res.cloudinary.com/jkeohan/image/upload/c_scale,h_320/v1592387060/Screen_Shot_2020-06-17_at_5.42.03_AM_nceaqw.png)

## Suggestions To Getting Started

- Create the Components based on the defined heirarchy and then import them one at a time and only the name of the component
- Pass props and use **console.logs** to examine the data and confirm it's what you expect to see.


## Plagiarism

Take a moment to refamiliarize yourself with the
[Plagiarism policy](https://git.generalassemb.ly/DC-WDI/Administrative/blob/master/plagiarism.md).
Plagiarized work will not be accepted.

## License

1.  All content is licensed under a CC­BY­NC­SA 4.0 license.
1.  All software code is licensed under GNU GPLv3. For commercial use or
    alternative licensing, please contact legal@ga.co.



