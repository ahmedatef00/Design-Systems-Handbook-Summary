# Design Systems Handbook
Disclaimer: This book was not written by me, this repo is my personal summary of it, and nothing more. For the full book check [DesignBetter.Co](designbetter.co) by [Invision](https://www.invisionapp.com/).

# Introducing Design Systems
> Design systems unite product teams around a common visual language, reducing debt, accelerating the design process, and building bridges between teams.

## The power of scale
Douglas Mcllroy presented component-based development, a solution to the "software crisis" that existed in 1960s due to the gap between slow software development and fast hardware. The same challenge exists now, but instead of development, it exists in design.

Problems of consistency arise as a solution scales, in which case companies could do 1 of 3 things:
- Hire more people
- Design faster
- Create solutions that work for multiple problems

> Even with more hands working faster, the reality is bespoke design simply doesn't scale. Design is scaling.

Invesment in design can exist in the following forms:
- The design team is growing
- Design is embedded in teams throughout the company
- Design is playing a key role in all products

> It wasn't hard to get them to follow the guidelines, it was hard to get them to agree on the guidelines. — Lori Kaplan, Atlassian

Design systems address design scaling challenges by marrying two concepts:
- Standards
- Components

Standards makes us understand both the *what* and *why*, which in turn help us create exceptional user experience. They encompass both design and development, including naming conventions, accessibility requirements, and file structure. They also make it easier to critise decisions since there'll be a common design language to base critique on.

Definig the purpose and style of color, shape, type, icons, space, and motion is essential to creating a brand aligned with consistent user experience. Every `component` incorporates these elements.

Components are portions of reusable code and serve as the building blocks of your application's interface. While varying in complexity, reducing them to single functions/uses such as a button or a drop down increases flexibility and reusability.

> The more reusable your components, the less you need to maintain, and the easier scale becomes.

Chapter 3 talks about this.

## The value of design systems
Designs systems can be a painkiller for growing pains in ways:

### Scale design
Having a common design language to unite the product protects user experience and design process from breaking down. Static artifacts can be useful but run out-of-date quickly. An internal design system site is the best, most accessible source of truth.

### Manage your debt
Applications and teams build technical and design debt as they age. Design dept is made up of an overabundance of non-reusable and inconsistent styles and conventions.

*Creation* doesn't inherently create debt but using a design system will keep you on budget.

### Design Consistently
Standardized components create a more predictable product. They also allow designers to spend less time focused on style and more time developing a better user experience.

### Prototype faster
Using a design system allows to piece together flows and interactions as quickly as pulling LEGO blocks from a bin.

### Iterate more quickly
Using a design system reduces development efforts and makes iteration quick and painless.

### Improve usability
When CSS for countless unique interface elements and their interactions increase, so does cognitive load and page weight. It can also create conflicting code which ultimately ruins UX and DX.

### Build in accessibility
Accessibility can be implemented at the component level by optimizing for those with disabilities, on slow Internet speeds, or on old computers.

## Myths of design systems
Designers can feel limited or restrained, but often these perceived weaknesses are the greatest strengths of a design system.

### Myth 1: too limiting
Myth: Having to stick to a *universal* system hinders the ability to create custom solutions.

Reality: With design systems, new solutions can be created and fed back into the system.

### Myth 2: loss of creativity
Myth: Designers can't be creative when restricted to a design system.

Reality: Design system components are interdependent. A change in one location will be inhereted throughout the system, leading to less effort when exploring style.

### Myth 3: one and done
Myth: Once the system is designed and built, it's complete and becomes obsolete.

Reality: A design system evolves and is constantly changing, either by effects of maintenance or style iterations.

## Further reading
- [Software Crisis](https://dbtr.co/software-crisis)
- [Component-based Software Engineering](https://dbtr.co/component-engineering)
- [The Way We Build](https://dbtr.co/airbnb-build)
- [Designed for Growth](https://dbtr.co/etsy-growth)
- [Selling a Design System before asking for buy-in](https://dbtr.co/selling-system)
- [The Design of Everyday Things](https://dbtr.co/design-everyday)
- [What is a Design Language... really?](https://dbtr.co/what-is-design-language)
- [Things you could be doing instead of designing and building that card component for the umpteenth time](https://dbtr.co/things-you-could)
- [Website Style Guide Resources](https://dbtr.co/styleguides)
- [Making Material Design](https://dbtr.co/making-material)
- [Material Design](https://dbtr.co/material-guidelines)
- [Shopify Polaris](https://dbtr.co/shopify-polaris)
- [Starting a Design System](https://dbtr.co/starting-system)

## Designing your design system
Big problems are always more manageable when broken into smaller pieces. Before diving into the design process, start by considering *who* needs to be involved in the creation of your design system and how the team will work together. This will pave the path for your design language.

### Who should be involved
Design languages require more than just designers. It's a structure that requires input based on research and different POV's. This can be accomplished by merging multiple fields together. Such fields may include:
- Designers to define the visual elements of the system
- Frontend developers to create modular, efficient code
- Accessibility experts to ensure your system conforms to standards like WCAG
- Content strategists who can help the team nail the voice and tone of the system
- Researchers who can help you understand customer needs
- Performance experts who can ensure your system loads quickly on all devices
- Product managers to ensure the system is aligning to customer needs
- Leaders (VPs and directors) to champion and align the vision throughout the company including up to executive leadership

> We have this program called the guild... essentially we take one person from each pillar...and for our design system we use them as our user research group. — Rachel Cohen, LinkedIn

### Choosing the right team model
Team models are as important as the teams working on your product. Those include:

#### Model #1: The solitary model
An “overlord” rules the design system.

Pros: Fast and scrappy.

Cons: With one person in charge this can cause a bottleneck.

<center>

![The solitary model](./Media/solitary-team-model.png)

</center>


#### Model #2: The centralized team model
A single team maintains the design system as their full time job.

Pros:
- Keep the system well maintained
- Spread a design language to a broad portfolio
- Serve many product teams, free from the bias of any product’s priorities
- Identify opportunities and solicit requests to deepen a library
- Setup practices and processes to validate emerging design

Cons:
- They may not be as connected to the customers’ needs as they may be less involved in user research
- Lack context
- Lack power to foster active participation of designers on product teams
- Lack visibility into day-to-day, product-specific challenges
- Lack influence on product designers to balance tradeoffs between product and system objectives

<center>

![The centralised model](./Media/centralised-team-model.png)

</center>

#### Model #3: The federated model
Team members from across the company come together to work on the system.

Pros:
- Has great insight into what is needed for all the product features and user needs
- Broadens legitimate relevance to many platforms
- Limits perceptions of bias by representing many perspectives
- Eases spreading the system across teams by equipping more evangelists


Cons:
- Can be quite busy working on those areas already.
- Introduces practical challenges in decision making by introducing more opinions and new critique.

<center>

![The federated model](./Media/federated-team-model.png)

</center>

Many teams are moving away from the solitary model because *overlods* don't scale. Some are even moving towards a more hybrid approach, joining different models together.

Learn more [here](https://medium.com/eightshapes-llc/team-models-for-scaling-a-design-system-2cf9d03be6a0) or by reading this chapter in the book.

### Interviewing customers
Your design system will get used much more often if you create it to fit into the workflow of other teams. By interviewing users, you can pinpoint problems, define principles that will help others use the system, and focus your energies the most important things. Open source communities and executives, leaders, and management aren't an exception to this either.

Now it's time to build an inventory, of which there are two types:
- An inventory of visual attributes to create a codified visual language.
- An inventory of each UI element which will be used to create a UI library of components.

#### Creating a visual inventory
This step requires an already existing product. To create a visual inventory we need to conduct a visual audit. This audit will take all the elements we use, and will allow us to look into the CSS behind all of them using tools like [CSS Stats](https://dbtr.co/CSSstats). It will show you how many unique colors, font sizes, and font families you have. It also shows a bar chart for the number of spacing and sizing values.

<center>

![Example css stats usage from my own website](./Media/css-stats-example.png)

</center>

There are also plugins for your favourite design tool such as [Sketch-Style-Inventory](https://dbtr.co/sketch-style).

#### Creating a visual design language
Each component has fundamental elements that make up its visual design language, these mainly include:
- Colours
- Typography (size, leading, typefaces, etc)
- Spacing (margins, paddings, positioning coordinates, borders)
- Images (icons, illustrations)

and may include:
- Visual form (depth, elevation, shadows, rounded corners, texture)
- Motion
- Sound

> A button typically has a background color, typography for the label, and spacing inside it. There may be an icon next to the label to create a visual cue. A border on the edge serves as simple ornamentation and may even round the corners. Finally, hovering over or clicking the button could trigger animation or sound as feedback to the user. Though a button may seem simple, there are many design decisions required to bring it to life.

#### Design Tokens
Design tokens are the *subatomic* foundation of a design systme implementation. They're name and value pairs, all stored in one place. Example: `SPACING_MEDIUM: 1rem`

#### Colour
Colours convey:
- Feedback: Error and success states
- Information: Charts, graphs and wayfinding elements
- Hierarchy: Showing structured order through color and typography

Common colors in a design system include 1-3 primaries that represent your brand. You may add another for buttons and links. A good idea is to use the same background colour for links and buttons as it makes it easier for users to recognize interactive elements. You’ll likely have neutrals for general UI backgrounds and borders—usually greys. And don't forget about states such as error, warning, and success.

Colours may also be set for objects and products.

#### Typography
##### Fonts and weights
The fonts you choose have a high impact on both your brand and your user experience. Keep legibility in mind as you select the right fonts for your system. Use common fonts like Helvetica, Times New Roman, and Verdana.

> Most design systems I’ve worked on include just two typefaces: one font for both headings and body copy, and a monospace font for code. Sometimes there’s an additional font for headings that compliments the body font.

Use light or thin weights at larger text sizes since legibility can become an issue.

##### Type Scale
Consider the legibility of the font you’ve chosen. A 16px font size works well (and is gaining traction as the standard approach). Use a modular scale for font sizes for other elements.

Be sure to give thought to how it will respond to various screen sizes to maintain legibility. A common method is to enlarge headings on larger viewports.

##### Leading
Also known as line-height in CSS, can improve readability aesthetics of your typography. A general rule of thumb is to have leading at around 1.4–1.5x the font-size. 1.5 is recommended by the W3C Web Accessibility Initiative.

You can define your line-height without a unit of measurement and the browser will do all the hard math for you.

> For headings, tighten it up depending on your typeface. In most cases, I find a 1.25 or 1.125 ratio works quite well.


<center>

![Leading examples](./Media/leading.png)

</center>

##### Spacing and sizing
Use spacing and sizing systems based on patterns and proportions, and be consistent. Use 4-based metrics as it works well.

Checkout the Google Android design guidelines [here](https://material.io/design/layout/spacing-methods.html#spacing)

> For horizontal spacing, an 8-based scale works quite well. You can make margins and padding equal or in proportion to the font size. But for vertical spacing, I tend to use a 12-based system. This is due to the line-height I get of 1.5 (with the default font size of 16px) getting us to 24.

Sometimes borders will mess up this system, and this is where you customise your use-case. For general sizing, avoid setting widths and heights unless totally necessary.

#### Images
##### File Formats
Use SVG for illustrations and icons, and raster types (PNG, JPG) for photography. You can set 100% width and let height auto for responsiveness, and you may define some presets such as half-width, a third, or a fourth. Set these as max-widths so that the image can rescale for smaller screens.

##### Iconography
Come up with your guidelines before drawing:
- Filled or outlined
- Line weight
- Uses more than 1 color?
- Sizes
- Is there an icon art boundary set inside an outer boundary?

##### Illustrations
You can use these for empty states, loading screens, modals, and other components that invite visual interest. [Check out how Shopify did it](https://ux.shopify.com/empty-states-more-like-you-have-no-idea-how-much-work-goes-into-those-states-amirite-e0102f58b64e).

#### Visual form
Is the material quality of your UI and includes:
- background images and gradients
- textures
- shadows and elevation (z-indexes)
- rounded corners
- borders

#### Motion and sound
Motion and sound can have a high impact on the experience of your app.