 <article id="Coding"> 
    
        <h2>I am also planning to learn more courses like this.</h2>
        <p>I hope to get the hang of it in due time.</p>
    
        <section>
        <h3>Career Goals I have in Life</h3>
        <ul>
             <li>
            <P>One of my goals is to develop and code games for Roblox.</P>
            <figure>
                <img src="img/RobloxLogo.jpg" alt="Roblox Logo" title="I want to develop games for Roblox" width="45" height="43" loading="lazy">
            <figcaption>
                Roblox
            </figcaption>
        </figure>
            </li>
            <li>
                <p>I know a College that has a Great Professor who is teaching me how to HTML:</p>
            <address>
            Fresno City College<br>
            1101 East University Ave<br>
             Fresno, CA 93741  
         </address>
         <figure>
             <img src="img/citycollege.jpg" alt="Fresno City College" title="The college where I am learning to HTML" width="270" height="180" loading="lazy">
             <figcaption>
                A College Image
             </figcaption>
        </figure> 
    </li> 
    </ul>
    </section>
        <!-- TODO: Add more Goals -->
        <section>
        <h3>I have hopes and dreams.</h3>
        <dl>
            <dt>Hope</dt>
            <dd>I hope to graduate with my <strong> BA</strong>!</dd>
            <dt>Dream</dt>
            <dd>My dream is to major in a field that I enjoy doing.</dd>
    
            <dt>My Kids</dt>
            <dd>To show them to never give up on their dreams.</dd>
            </dl>
        </section>
    </article>
    
    <hr>
    
    <article id="contact">
        <h2>Contact Me</h2>
            <p>I'd really like to hear from you!</p>
    
        <form action="https://httpbin.org/get" method="get">
            <fieldset>
                <legend>Personal Information</legend>
            <p>
                <label for="firstName">First Name:</label>
                <input type="text" name="firstName" id="firstName" placeholder="John" autocomplete="on" required autofocus>
            </p>
            <p>
                <label for="lastName">Last Name:</label>
                <input type="text" name="lastName" id="lastName"                placeholder="Doe" autocomplete="on" required>
            </p>
            <p>
                <label for="password">Password:</label>
                <input type="password" name="password" id="password" placeholder="Your Secret" required>
            </p>
        
        <p>
            <label for="phone">Phone:</label>
            <input type="tel" name="phone" id="phone" placeholder="555-555-5555"
            pattern="[0-9]{3}[0-9]{3}[0-9]{4}" required>
        </p>
        <p>
            <label for="decade"> Favorite Decade:</label>
            <input type="number" name="decade" id="decade" min="1950" max="2023" step="5" value="1980">
        </p>
     <p>
            <label for="coffee">Favorite Coffee:</label>
            <select name="coffee" id="coffee" multiple size="5">
                <optgroup label="Coffees">
                <option value="regularcoffee">Regular Coffee</option>
                <option value="icedcoffee">Iced Coffee</option>
            </optgroup>
            <optgroup label="ExpressoDrinks">
                <option value="latte">Latte</option>
                <option value="cappuccino">Cappuccino</option>
                <option value="cortado">Cortado</option>
                <option value="americano">Americano</option>
            </optgroup>
                <option value="other">other</option>
    
    
            </select>
        </p>
        <!-- <p>
            <label for="coffee">Favorite Coffee:</label>
            <input type="text" name="coffee" id="coffee" list="coffee-list">
            <datalist id="coffee-list">
                <option value="coffee">
                <option value="espresso">
                <option value="latte">
                <option value="cappuccino">
                <option value="cortado">
                <option value="americano">
                <option value="other">
            </datalist>
        </p> -->
    </fieldset>
    <br>
    <fieldset>
        <legend>What is your favorite food?</legend>
        <p>
            <input type="radio" name="food" id="tacos" value="tacos">
            <label for="tacos">Tacos</label>
        </p>
        <p>
            <input type="radio" name="food" id="pizza" value="pizza">
            <label for="pizza">Pizza</label>
        </p>
        <p>
            <input type="radio" name="food" id="other" value="other">
            <label for="other">Other</label>
        </p>
    </fieldset>
    <br>
    <fieldset>
        <legend>Do you have pets?</legend>
        <p>
            <input type="checkbox" name="pets" id="dog" value="dog">
            <label for="dog">Dog</label>
        </p>
        <p>
            <input type="checkbox" name="pets" id="cat" value="cat">
            <label for="cat">Cat</label>
        </p>
        <p>
            <input type="checkbox" name="pets" id="fish" value="fish">
            <label for="fish">Fish</label>
        </p>
        <p>
            <input type="checkbox" name="pets" id="otherpet" value="otherpet">
           <label for="otherpet">Other Pet</label>
        </p>
    </fieldset>
    <br>
    <fieldset>
        <legend>Send me A Note</legend>
        <label for="message">Your Message:</label>
        <br>
        <textarea name="message" id="message" cols='30' rows="10" placeholder="Type your message here"></textarea>
    </fieldset>
    <br> 
        <button type="submit">Submit</button>
        <button type="submit" formaction="https://httpbin.org/post" formmethod="post">Post</button>
        <button type="reset">Reset</button>
        
    </form>
    </article>
    </main>
        <hr>
        &lt;&lt;&lt; &copy; <a href="about.html">Cua Yang</a> &gt;&gt;&gt;
        <footer> 
        <p>
            <a href="#">Back To Top</a>
         </p>
        </footer>
        </body>
    
    </html>  