This month, I saw the Netlify-Hashnode hackathon 🤩 and immediately knew I found the excuse to spend my time bringing my prolonged idea to life.

# What is 🔗 Ajjur?

Have you ever wanted to share a link with a long link with a friend, but it seems way too long to send through a message (maybe it's a base-64 image URI), so you might turn towards URL shorteners, nothing special?

But try to imagine, along with the shortening functionality, what if you could have a lot more. I mean, track all the clicks (or hits) on the URL that you shortened and get very-deep insights about the person who clicked it, like:

- Their 💻 device information, including model, operating system, etc.
- Their 👩‍💻 browser name and version
- Their 🌎 IP location, along with their ISP name, their city, rough coordinates, etc.

And much more! 🤯

# Tech stack

I've used the following technologies to create the application:

The following technologies were involved in the making of this project.

- [React JS](https://reactjs.org/) ⚛️ - For the frontend of the app
- [Apollo GraphQL Server v3](https://www.apollographql.com/docs/apollo-server/) 🕸️ - For querying the backend from the frontend efficiently
- [GraphQL Template By Basel](https://github.com/baray/ajjur/tree/main/server/prisma) 🧩 - Boilerplate Template used for initializing the backend
- [Prisma](https://www.prisma.io/) 💿 - The ORM used for the app
- MySQL(https://www.prisma.io/docs/reference/database-reference/supported-databases) for the database
- [Netlify](https://netlify.com) for hosting the app
- [Redux](https://redux.js.org/) 🗺️ w/ [Redux Toolkit](https://redux-toolkit.js.org/) - For handling states across the application
- [React Hook Form](https://react-hook-form.com/) - For managing and validating forms and text inputs.
- [Styled Components](https://www.styled-components.com) 💅 - For adding CSS to the application
- [IP registry API](https://ipregistry.co/) 🌐 - For obtaining 🏛 ISP, geolocation, etc. information for the IP address

# 🍒 The Process

I started out by planning the structure and the requirements of the app. Alright, I needed to track all the clicks with their IPs, wanted to know more about their devices from the headers that the browser sent, and... that's it!

All I wanted to achieve was laid out, and I had to bring the idea to life.

## Research and Planning

But I still had to jot down my ideas so that I don't forget the little details. Started out by writing everything in broad detail in Notion.

"Along with the IPs, I also need the time that the person clicked the link, their ISPs, anything useful I can get from the IP, ..." and the list goes on. This is what the final notion file looked like:

![Notion Planning Page Screenshot](https://cdn.hashnode.com/res/hashnode/image/upload/v1645191580353/rzseYEZ9p.png)

After this, I had a clear path to follow and thankfully did not forget about any detail, such as implementing total click count, adding hover effects, etc. So I took references while doing the design

Now, I just needed to think of a name for the app, and this is where I screwed. The thing is, I wanted the name of the app to represent a certain action the user would do in the app, like packing the

Then I got to the interesting part, designing.

### Customizing

The original design was good, but it wanted something more, like the colour customization, planning out exactly where everything would go, and creating an exact mock-up of how the app would look. I find this approach very useful, because you don't have to scratch your head over minor details that would otherwise go unnoticed while planning, and you have to go to the sketch board all over again.

#### Dashboard

So the inspiration design for the dashboard looked like this:

![Inspiration](https://raw.githubusercontent.com/baray/ajjur/main/imgs/Stats.png)

And here's what the final design looked like:

![dashboard.png](https://raw.githubusercontent.com/baray/ajjur/main/imgs/Dashboard.png)

(I know they look totally different, or at least barely-related, but the inspiration image really helped with the design aspects, and most of the compliments I received are a result of that)

The designs looked good in my opinion, and I was dead-set to implement the most design-accurate version of this with react and try to not mess up the margins or paddings somewhere. This marked the end of the designing and planning part of the app. Not bad, right?
