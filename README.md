![Features](https://raw.githubusercontent.com/baray/ajjur/main/imgs/Features.jpg)

<div align="center">
  # ๐ Ajjur
  <hr />
</div>

![](https://raw.githubusercontent.com/baray/ajjur/main/imgs/Technologies.png)

**Ajjur is an URL Shortener**, that can be easily self-hosted with awesome features like:

- ๐ Shorten URLs with, or without an account
- ๐๏ธ Customize back-halfs on every shorten URL
- ๐ Deploy to custom URL and Infrastructure
- ๐ธ๏ธ QR code generator for each short url
- ๐๏ธ Power of customization
- ๐งค Customize settings like link back-halfs, link targets, tracking info, etc.
- ๐ต๏ธโโ๏ธ Track each click on a ajjur, and retrieve
  - ๐ IP address (Spoof-resistant)
  - ๐ธ๏ธ ISP Name
  - ๐บ๏ธ IP-Location
  - ๐ป Device details like OS Version and Device Model
  - ๐ช Browser Name and including version
- ๐ฏ Custom Loading/Redirecting Screen (self-hosted only)
- ๐โโ๏ธ Quick Redirections in 150ms!
- ๐ Fast, Reliable and Secure
- ๐ฎ Secure Secret Storage and handling using ๐ป environment variables
- โจ Built on a modern tech stack
- ๐ฟ Compatible with MySQL, PostgreSQL, MongoDB and [many
  more](https://www.prisma.io/docs/reference/database-reference/supported-databases)

This project was created to be the most powerful URL shortener for the public, so no wonder it's so feature-rich

## ๐ธ Screenshots

Here is a sneak peek of the application and it's visuals ๐:

<table>
  <tr>
    <td colspan="2">
      <img src="https://raw.githubusercontent.com/baray/ajjur/main/imgs/Dashboard.png"
        alt="Dashboard Page" />
      <br />
      <p align="center">Dashboard Page</p>
    </td>
  </tr>
  <tr>
    <td>
      <img src="https://raw.githubusercontent.com/baray/ajjur/main/imgs/Login.png"
        alt="Login Screen" />
      <br />
      <p align="center">Login</p>
    </td>
    <td>
      <img src="https://raw.githubusercontent.com/baray/ajjur/main/imgs/Shorten.png"
        alt="Signup" />
      <br />
      <p align="center">Shorten</p>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <img src="https://raw.githubusercontent.com/baray/ajjur/main/imgs/Homepage.png"
        alt="Home Page" />
      <br />
      <p align="center">Home Page</p>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <img src="https://raw.githubusercontent.com/baray/ajjur/main/imgs/Stats.png"
        alt="Home Page" />
      <br />
      <p align="center">Stats</p>
    </td>
  </tr>
</table>

## ๐ฒ Built With (Tech Stack)

The following technologies were involved in the making of this project.

- โ๏ธ [React JS](https://reactjs.org/) - Frontend
- ๐ [Apollo GraphQL Server v3](https://www.apollographql.com/docs/apollo-server/) - Server API
- ๐งฉ [GraphQL Template By Basel](https://github.com/baray/ajjur/tree/main/server/prisma) - Boilerplate for Apollo
- ๐ฟ [Prisma](https://www.prisma.io/) - ORM
- ๐จ Any relational or non-relational [database that Prisma
  supports](https://www.prisma.io/docs/reference/database-reference/supported-databases)
- ๐บ๏ธ [Redux](https://redux.js.org/) w/ [Redux Toolkit](https://redux-toolkit.js.org/) - State management
- ๐ [IP Registry](https://ipregistry.co/) - Free Geolocation lookups

<!-- GETTING STARTED -->

# ๐คฏ Quick Start Guide

To get started with having your own instance of Ajjur, follow the steps described in the following section

## ๐ฆ Get an API Key first

Ajjur uses [IP Registry](https://ipregistry.co/) for Geo-location look-ups to track hits (free for 100,000 lookups)

Obtain an **API key** from the [ipregistry.co](https://ipregistry.co) website

# ๐ฃ Roadmap

This project is far from perfect, and we'll reach there one day, or at least get close.

- Link-in-bio feature
- Admin Panel Support
- Multiple Subdomain Support
- Email Notifications for hits if enabled
- Custom OG Preview for social-sharing
- One-Click Deploys
- Password-protected links

# ๐ Architecture

Here's a diagram explaining exactly how everything fits into place

<div align="center">
  <img src="https://raw.githubusercontent.com/baray/ajjur/main/imgs/DataFlow.png"
    height="300" />
  <p>Here's how everything fits into the scene</p>
</div>
