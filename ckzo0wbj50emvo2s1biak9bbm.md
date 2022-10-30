# Text Overlay on an Image Using HTML & CSS

### Do you know how to fill an image with text and make it a little blur using HTML and CSS (Text Overlay on an Image)?
> Today we'll learn  how to make a text overlay on an image using HTML and CSS.

### Prerequisites:- 
1. An Image over which you want to fill text.
2. A code editor like Visual Studio Code.

---

### Following is the demo of what we are going to make today - 
![Demo Image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/encmmz9az5y8tamoknei.png)

You can see here this image of the girl is filled with text and the image is hidden and blurry with the huge amount of text.
We'll make this using **HTML and CSS** and also make it **responsive.**

---

### Let's start with the HTML file.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <title>Document</title>
  </head>
  <body>
    <p id="text">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium,
      voluptatum. Architecto porro veniam optio voluptatem placeat vero eligendi
      vitae quisquam nisi quas rem ipsum repellat autem, consequuntur quibusdam
      doloribus exercitationem consectetur amet iste! Laudantium molestiae
      officia obcaecati. Voluptatibus magnam nobis officiis veritatis suscipit
      nihil cupiditate iusto error consequuntur facilis! Cupiditate, ipsa
      quisquam, sequi at explicabo quidem laborum deleniti tempora ex similique,
      dolorem magni fugit laudantium dolor ut reprehenderit est! Reiciendis
      perferendis exercitationem praesentium nihil sapiente fugit. Impedit
      adipisci maiores possimus corrupti rerum nostrum quis! Maiores impedit
      iure nesciunt, doloribus inventore expedita neque totam quas ex sed fugit
      repellendus qui omnis adipisci alias nulla obcaecati molestiae eum, aut
      exercitationem similique. Molestias corporis quaerat cum assumenda,
      adipisci corrupti eum mollitia rerum ea modi. Possimus deleniti quaerat
      excepturi similique illum. Ipsum nam voluptas autem sunt incidunt
      veritatis tempora, ullam, perspiciatis suscipit, quae quaerat ex dolores
      explicabo eius similique fugiat culpa? Obcaecati laboriosam illo
      voluptatibus, magnam aperiam dignissimos aut vitae cupiditate tempora
      aliquid, consectetur cum et soluta porro, laudantium quaerat earum nostrum
      eveniet nobis deleniti dicta? Perspiciatis at expedita tempora quos
      veritatis provident. Earum, facilis nihil. Ratione soluta nam blanditiis
      natus odit porro, eum at nisi accusamus hic veniam tenetur atque
      consequuntur delectus aliquam vel voluptatibus, cum ea nemo aspernatur qui
      dolorem. Voluptatem excepturi ipsum consequuntur libero autem impedit
      iusto fuga quasi. Minima vel recusandae quia explicabo nostrum aperiam
      natus reprehenderit dolorum, quas cumque laboriosam alias illum voluptatem
      vitae, nihil aspernatur rerum delectus sed soluta pariatur atque ratione
      officia dolorem! Ea quaerat facere dolores. Atque distinctio est ratione
      quos explicabo veniam mollitia, temporibus numquam architecto sed iusto
      vel animi repellendus nisi nam, aut ullam nesciunt vitae ipsum. Commodi
      adipisci exercitationem similique odio quo nihil laudantium ipsum facere
      rerum illo ipsa libero explicabo dicta accusantium deserunt a nesciunt,
      consequatur aspernatur? In, accusamus. Ipsa magnam omnis nam explicabo,
      ducimus dolores officia quibusdam maiores est, assumenda accusamus eaque
      vero similique odit debitis. Nulla vero similique iusto optio vitae, natus
      quidem, placeat quaerat, a velit consequatur quibusdam eum ea ullam.
      Consectetur, temporibus odio in asperiores voluptates corporis laboriosam!
      Nobis nulla dolorem ratione illum voluptates in dolores molestias a!
      Corporis optio mollitia consequuntur voluptatibus sunt nobis est illo quod
      praesentium cupiditate. Alias sed nostrum deserunt voluptatum, ad
      molestiae in facilis. Saepe maiores alias quisquam provident illum
      repellat pariatur omnis laudantium libero ex dolores, blanditiis vero.
      Optio temporibus itaque id sapiente architecto eligendi, ipsum a iste aut
      porro est dolor dolorem vitae deleniti error consectetur mollitia
      inventore necessitatibus doloremque quasi. Ullam eius cum facere natus
      nemo non ipsum laudantium quaerat praesentium esse veniam atque
      accusantium deleniti quae obcaecati distinctio maiores quidem saepe
      delectus eligendi commodi expedita fuga, temporibus molestias. Explicabo
      architecto doloremque natus ad! Reiciendis, voluptate ea. Corrupti quod
      nesciunt neque sapiente ullam vero libero debitis cumque ducimus, modi,
      mollitia inventore magni fugiat quam totam sequi recusandae sed earum
      deserunt velit at! Ratione inventore hic expedita accusantium fugit eaque
      reprehenderit dolorem excepturi quia doloribus iste nobis id temporibus
      nostrum, ducimus fugiat nam illo. Labore quis nesciunt eum minima
      voluptatibus placeat!Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium,
      voluptatum. Architecto porro veniam optio voluptatem placeat vero eligendi
      vitae quisquam nisi quas rem ipsum repellat autem, consequuntur quibusdam
      doloribus exercitationem consectetur amet iste! Laudantium molestiae
      officia obcaecati. Voluptatibus magnam nobis officiis veritatis suscipit
      nihil cupiditate iusto error consequuntur facilis! Cupiditate, ipsa
      quisquam, sequi at explicabo quidem laborum deleniti tempora ex similique,
      dolorem magni fugit laudantium dolor ut reprehenderit est! Reiciendis
      perferendis exercitationem praesentium nihil sapiente fugit. Impedit
      adipisci maiores possimus corrupti rerum nostrum quis! Maiores impedit
      iure nesciunt, doloribus inventore expedita neque totam quas ex sed fugit
      repellendus qui omnis adipisci alias nulla obcaecati molestiae eum, aut
      exercitationem similique. Molestias corporis quaerat cum assumenda,
      adipisci corrupti eum mollitia rerum ea modi. Possimus deleniti quaerat
      excepturi similique illum. Ipsum nam voluptas autem sunt incidunt
      veritatis tempora, ullam, perspiciatis suscipit, quae quaerat ex dolores
      explicabo eius similique fugiat culpa? Obcaecati laboriosam illo
      voluptatibus, magnam aperiam dignissimos aut vitae cupiditate tempora
      aliquid, consectetur cum et soluta porro, laudantium quaerat earum nostrum
      eveniet nobis deleniti dicta? Perspiciatis at expedita tempora quos
      veritatis provident. Earum, facilis nihil. Ratione soluta nam blanditiis
      natus odit porro, eum at nisi accusamus hic veniam tenetur atque
      consequuntur delectus aliquam vel voluptatibus, cum ea nemo aspernatur qui
      dolorem. Voluptatem excepturi ipsum consequuntur libero autem impedit
      iusto fuga quasi. Minima vel recusandae quia explicabo nostrum aperiam
      natus reprehenderit dolorum, quas cumque laboriosam alias illum voluptatem
      vitae, nihil aspernatur rerum delectus sed soluta pariatur atque ratione
      officia dolorem! Ea quaerat facere dolores. Atque distinctio est ratione
      quos explicabo veniam mollitia, temporibus numquam architecto sed iusto
      vel animi repellendus nisi nam, aut ullam nesciunt vitae ipsum. Commodi
      adipisci exercitationem similique odio quo nihil laudantium ipsum facere
      rerum illo ipsa libero explicabo dicta accusantium deserunt a nesciunt,
      consequatur aspernatur? In, accusamus. Ipsa magnam omnis nam explicabo,
      ducimus dolores officia quibusdam maiores est, assumenda accusamus eaque
      vero similique odit debitis. Nulla vero similique iusto optio vitae, natus
      quidem, placeat quaerat, a velit consequatur quibusdam eum ea ullam.
      Consectetur, temporibus odio in asperiores voluptates corporis laboriosam!
      Nobis nulla dolorem ratione illum voluptates in dolores molestias a!
      Corporis optio mollitia consequuntur voluptatibus sunt nobis est illo quod
      praesentium cupiditate. Alias sed nostrum deserunt voluptatum, ad
      molestiae in facilis. Saepe maiores alias quisquam provident illum
      repellat pariatur omnis laudantium libero ex dolores, blanditiis vero.
    </p>
  </body>
</html>
```
The long paragraph text you're seeing in the code inside the **p tag** is generated using **lorem**. 
#### What is Lorem?
> Lorem is a random text generator used in HTML files to generate random words. 
For reference, you can visit it's official website [here](https://loremipsum.io/).

I have used here **lorem1200** which will randomly generate 1200 words(dummy text). 

---

If you're using Visual Studio Code, you can install an extension called **Live Preview** which will help you to see the output beside your code files in the code editor itself. 
![Live Preview Extension](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/haynvp8teibu3317j564.PNG)

---

### Now we will code the CSS file

```css
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap");

p {
  font-family: "Poppins", sans-serif;
  line-height: 14px;
  background: url("my-profile-photo.jpg");
  -webkit-background-clip: text;

  background-attachment: fixed;
  background-repeat: no-repeat;
  -webkit-text-fill-color: rgba(255, 255, 255, 0);
  background-size: 70vh;
  background-position: center;
}

body {
  background: black;
  overflow: hidden;
}
```
Here I have imported a font called **Poppins** from the [Google Fonts](https://fonts.google.com/).

I've used the `-webkit-background-clip` property here and given it as text which is the class given to the paragraph tag. This will make the text float over the image. 
I've kept the background attachment fixed which will keep the image used here in the background as fixed with regards to the viewport and stopped the background image from repeating itself using `background repeat as no repeat`.

---

So, now we're done with our coding. So, let's see the output.
### Output
![Final Output](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/gadmrpkwzo50ibsbe1yp.png)
Now, if you run this code, you'll also find it as a responsive webpage.
![Responsive Page](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/gfmount5nlk89uaj0ajr.png)

---

### You can also watch this [video](https://bit.ly/3LKBpvk) for clarity.

## Hope this helps you. Thank you for reading, and let's connect!
Thank you for reading my blog. Feel free to subscribe to my [YouTube Channel](https://www.youtube.com/channel/UCsuzc8lqAbgUYo4yzpjtfSw) and connect on [LinkedIn](https://www.linkedin.com/in/susmita-dey-15a15a210/) or [Twitter](https://twitter.com/its_SusmitaDey).
Also, feel free to [support](https://www.buymeacoffee.com/susmitadey) my work.😊