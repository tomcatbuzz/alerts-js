# 🅰 Alerts JS

<p align="center">
  <img src="./assets/logo-large-red.png" alt="AlertsJS Logo">
</p>

AlertsJS is a **simple, easy** way of displaying beautiful **alerts and popups** updated weekly in our curated list
including designs of various **frameworks** and **libraries**. 😎

You can integrate it in your website with using just a single `<script>
  ` tag, Additional options are available, but not required since you can use our free webservice to display alerts/popups without configuring Javascript.

## 💡 Why AlertsJS?
Because it provides a simple, unobtrusive web interface to display beautiful alerts and popups with just one `
  `<script>`
  ` tag, without having any prior knowledge of javascript. You can also - 
- Create forms and collect data by integrating various plugins and or services such as MailChimp 📬 or our own service.
- You can choose any of your favorite libraries such as micromodal.js or Sweetalerts.js right through the configurations and have a variety of over 200+ such libraries and plugins including our **custom made** one's.
- We are tiny, which means no need to load Jquery and all the inessential things. You'll only include what you need.
- Authenticating securely to display popups/alerts through the web interface to your website.
- Integrating things such as 🔗 download links on payment through PayPal or Stripe. It also offers various integrations. Look at [integrations](#integrations) for more information.
- It will remain open-source forever, but to keep it running and maintaining it you can help us by donating us on 💷💷[PayPal](https://www.paypal.me/udicon).

## 🧑 Contributing
We'd love if you help us by fixing a bug, or creating a whole new modal theme from scratch. Every small contribution counts towards a big release. You can join our official **Discord** Server 😳 [here](https://discord.gg/YvgEPre). Feel free to create a pull request if you think we did something 👎 wrong.

## 👥 Use Cases
AlertsJS can be used by anyone and everyone as its flexible and adjusts according to the situation. If you aren't interested in writing Javascript code, you can use our Web Interface with which you could configure all the settings which you could do while writing JS. But if you want to have even more control and write JS. Don't worry we have the open-source library with which you could build your own alerts/popups and customize it according to your needs.
## 🚛 The Open-Source Process
Since the development is open-source, we want to add as many contributors as possible, We also are in need of moderators for curating the list weekly. The process would be simple:- 
- 1️⃣ Moderators choose and approve various alert/popup libraries based on their stability and design.
- 2️⃣ The then approved libraries would be added to the Global Package Index (GPI) with which it is accessible through the AlertsJS library.
- 3️⃣ The curated list thus is updated weekly in the same manner. Note that only opensource libraries are added to the **GPI**.

## 📄 Documentation
You can use the following options 👂 in the constructor:
```js
  const alert = new Alert({
    title: 'Awesome Alert', // The 📌 title of modal.
    message: 'This is another awesome alert made using AlertsJS', // 🌭 Content to display.
    icon: 'success', // A success ✅ or an ❎ error, custom icons are upcoming
    action: {
      type: 'link', // ⚡ The link you want to redirect to... more actions are coming
      redirect: '/purchase/success', // 🌐 Link where you want to redirect
    },
    button: { // 🔳 Button configurations
      type: 'submit', // 🌀 Type of the button [submit, reset]
      text: 'Get me flyin!', // 💊 Button text
      action: { // ⚡ Actions on the button
        type: 'link', // 👍 The link you want to redirect to... more actions are coming
        redirect: 'https://google.com' // 🌐 Link where you want to redirect
      }
    },
    closeButtonText: 'Close this thingy', // 🔲 The close button text.
  });

  ...
  ``
  `
You can call the alert with a 🛴 simple function:

```js
    ...
    alert.alert();

```
Or through an 👆 onclick event:

```
  html
    <
    input type = "button"
  onclick = "alert.alert()"
  value = "Click me" / >
  
```

### Properties

  
|Property Name| Property Description  |
|--|--|
| title | The title of the modal. It is a required field. |
| message | The message of the modal. It is a required field. It can render HTML too. |
| icon | An icon to display when the message pops-up. Currently the options available are `
  success ` and `
  error `, Custom icons are coming soon.|
| action | Currently the only option available is `
  link
    ` which creates a link instead of the button. |
| redirect | The URL where the link has to redirect. |
| buttonText | The text of the `
  button ` or `
  link
    ` |

##  ✏ To-Do
- [x] Make it work
- [ ] Add CSS effects, such as fadeIn, etc. to the modal
- [ ] Add more properties.
  


## ❓ FAQ

### Is it free? Are there any hidden costs? 🆓
It's absolutely **free** and infact the developer code is **open-source**. Do what you want to, hack, break, distribute, we aren't sueing you.

### How will you make money? 💰💰💰
We won't. But we require money for hosting the Web Interface, so we depend on donations and sponsorers. If you want to donate us, you could do it on [PayPal](https://www.paypal.me/udicon), for sponsoring please contact us
[here](https://utkarsh.co).

### I want a library added, could you do it? 😁
You could add a request to add your library on the website. Please note that the library is open-source before submitting it. It would be then moderated by the moderators. Finally, if approved. Taki Taki 🙌.
### So could I join and help? ✌
Yes ofcourse, we are pleased to have you on board. Contact us [here](https://utkarsh.co). The development has started, we are in need of good designers and developers.