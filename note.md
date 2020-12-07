
Job Hunt
Junior Angular Developer


At least 1 years of Front-End experience using JavaScript
A "growth mindset" and a big desire to learn and solve genuine problems
Credible experience working with Angular OR similar frameworks such as Vue
Good knowledge of OO JavaScript and core JavaScript features; ES7, etc
Knowledge/awareness of common front-end design patterns
Working in an Agile SCRUM team, creating clean code AND good tests

Frontend Developer
Frontend Developer - London - £40k - £50k


The company are looking to take on a bright, enthusiastic and quick thinking junior developer to help them build the beta version of their product. They are looking for the type of person who is obsessed with shipping products and someone who understands that you can’t let perfect get in the way of good. The company wants to take on someone who shares their passion for technology and is interested in working on technology which will change the data world.

- Be confident and autonomous

I am looking to speak with enthusiastic and hungry Creative Frontend Developers interested in working in the London area to work for an extremely established and growing company looking to hire ASAP for the right candidate.

You must have a thirst for learning, not be daunted by the unknown and help drive the technical and development efforts for our clients. Ideally, you come from a multi-disciplined background in development and technology and you’re comfortable in varying technologies and frameworks.

Junior Web Developer with one plus years of experience in the search for a position where I can enhance my skillset in web technologies to develop and implement solutions to meet business needs.




==============================================================================================

Job Category: IT / Computing / Software Job Location: London, London, UK ABOUT THE JOB We Make Websites are a Shopify Plus only agency with offices in New York and London

Our team of 60 design and develop e-commerce sites for some of the world's largest companies

Brands including: Hasbro, Crabtree & Evelyn, BBC, Aarmy, Paul Valentine, David Beckham Eyewear, Bulletproof, Revant Optics, Missoma, Harper Collins and The Economist

As a front-end developer, you'll be working as part of a cross-functional team of developers, designers, solutions consultants and agile project managers, to build best-in-class e-commerce websites on Shopify Plus

Your job will see you working closely with our team of UX/UI designers bringing their designs to life, creating exceptional e-commerce experiences: from high-converting homepages to perfectly crafted product pages

You'll be doing this alongside a talented team of developers, using a continually evolving set of modern front-end tooling

WHAT WE'RE LOOKING FOR Excellent knowledge of modern cross-browser HTML5, ES6 and CSS3 (SCSS) Experience building high-quality, responsive layouts and with smooth interactions, transitions and animations Ability to apply best practice modular web development Fluency with version control and Git flows Fluency in interpreting and working with third-party APIs Awareness of the most established libraries, their ecosystems and how to choose between them Awareness of web performance best-practice, developing for accessibility and SEO Experience with cross-browser and device testing websites Experience working within agile environments including Scrum / Kanban Excellent written and verbal communication skills Bonus points if you have Passion for design Knowledge of Continuous integration/deployment Experience with Vue.js Experience with Figma, Invision or Sketch Experience working with e-commerce platforms such as Shopify, Magento, Hybris or Salesforce Commerce Cloud

BENEFITS Salary based on experience

20 days holiday paid your birthday 8 bank holidays 1.5 additional days per year served, uncapped

Fun, challenging projects for interesting, creative clients

Discounted gym memberships, food, entertainment and travel

An inspiring, comfortable and social office on Leather Lane market in Farringdon with good transport connections and a secure, onsite, bike shed

The opportunity to travel to and work at our NYC office

We invest in our team and aim to provide anything you need to expand and nurture your skills including training and equipment

We also reward talent and leadership skills, with a clear promotion path for those who excel

Free tea, coffee, fruit and snacks

Think in-office tuck shop level of snacks, only free Monday morning team breakfast and monthly team lunches

We're a social bunch so expect to have fun with drinks, monthly team outings and an annual company-wide event

We are an equal opportunity employer and value diversity in our company

We do not discriminate on the basis of race, religion, colour, national origin, gender, sexual orientation, age, marital status, or disability status

Apply using the button below

No recruiters, please

Shopify web design, development, integration and optimisation agency in London and New York

We help the world’s most ambitious brands sell more online

We blend technical excellence and e-commerce expertise to design, develop and optimise market-leadi...






l(e) {
    squares[pacmanCurrentIndex].classList.remove('pacman')
    switch(e.keyCode) {
        case 40:
        console.log('pressed down')
        if (
            !squares[pacmanCurrentIndex + width].classList.contains('ghost-lair') &&
            !squares[pacmanCurrentIndex + width].classList.contains('wall') &&
            pacmanCurrentIndex + width < width * width
            ) 
            pacmanCurrentIndex += width
        break
        case 38:
        console.log('pressed up')
        if (
            //code
            !squares[pacmanCurrentIndex - width].classList.contains('ghost-lair') &&
            !squares[pacmanCurrentIndex - width].classList.contains('wall') &&
            pacmanCurrentIndex - width >=0
            ) 
            pacmanCurrentIndex -= width
        break
        case 37: 
        console.log('pressed left')
        if( 
            //code
            !squares[pacmanCurrentIndex - 1].classList.contains('ghost-lair') &&
            !squares[pacmanCurrentIndex -1].classList.contains('wall') &&
            pacmanCurrentIndex % width !==0
            ) 
            pacmanCurrentIndex -=1
        break
        case 39:
        console.log('pressed right')
        if(
            //code
            !squares[pacmanCurrentIndex + 1].classList.contains('ghost-lair') &&
            !squares[pacmanCurrentIndex +1].classList.contains('wall') &&
            pacmanCurrentIndex % width < width -1
            ) 