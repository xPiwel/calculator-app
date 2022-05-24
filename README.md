# calculator-app
Calculator app (iOS Style) for High-Phone script (buyable at http://high-scripts.com/)

# Installation


1. Add the new app to the config.js (located in `high_phone\html\js\config.js`) in the function `Config.Applications`
```js
    "Calculator": {
        label: "Calculator",
        description: "",
        icon: "fas fa-calculator",
        icon_color: "#000",
        icon_image: "calculator.png",
        icon_size: "1.1vw",
        background: "#fff",
        bottom: false,
        downloadable: true,
        downloadTime: 3000, // in miliseconds, 1000 ms = 1 second
        category: "default",
        notifications: {
            icon: "fas fa-calculator",
            color: "#7221da"
        }
    },
```

2. Add the new app in the index.html (located in `high_phone\html\index.html`) under the comment at line `170` if you haven't modified anything :
```html
            <!------------------>
            <!-- APPLICATIONS -->
            <!------------------>

            <!-- CALCULATOR -->
            <div class="calculator" id="Calculator"> 
                <div class ="container">
                    <div class="value">0</div>
                    <div class="buttons-container">
                        <div class="button function ac">AC</div>
                        <div class="button function pm">±</div>
                        <div class="button function percent">%</div>
                        <div class="button operator division">÷</div>
                        <div class="button number-7">7</div>
                        <div class="button number-8">8</div>
                        <div class="button number-9">9</div>
                        <div class="button operator multiplication">×</div>
                        <div class="button number-4">4</div>
                        <div class="button number-5">5</div>
                        <div class="button number-6">6</div>
                        <div class="button operator subtraction">−</div>
                        <div class="button number-1">1</div>
                        <div class="button number-2">2</div>
                        <div class="button number-3">3</div>
                        <div class="button operator addition">+</div>
                        <div class="button number-0">0</div>
                        <div class="button decimal">.</div>
                        <div class="button operator equal">=</div>
                    </div>
                </div>
                <div class="bottomline">
                    <div></div>
                </div>
            </div>
```

3. Add this line at the bottom of the index.html file (located in `high_phone\html\`) under `<!-- Configurations + Locales -->`:
```html
    <script type="text/javascript" src="js/calculator.js"></script>
```

4. Add the `calculator.css` file in the folder `high_phone\html\css\`
5. Add the `calculator.js` file in the folder `high_phone\html\js\`
6. Add the `calculator.png` file in the folder `high_phone\html\media\icons`
7. Restart and you're done !

# Copyrights
@ 2022 xPiwel (http://dp-store.tebex.io/). Coded with love. NON AFFIALIATED TO HIGH-SCRIPTS.COM 

high-phone from high-scripts (http://high-scripts.com/) 2021-2022. All rights reserved. Leaking or redistributing our products without our permission is prohibted and will get you banned from our Tebex shop and access to products revoked and your money will not be refunded!
