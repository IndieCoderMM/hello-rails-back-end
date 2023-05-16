<a name="readme-top"></a>
<details>
<summary>Table of Contents</summary>

- [👋 Greeting App : Backend Repo](#-greeting-app--backend-repo)
  - [📂 Frontend Repository](#-frontend-repository)
  - [🧰 Tech Stack  ](#-tech-stack--)
  - [✨ Key Features  ](#-key-features--)
  - [📘 Getting Started  ](#-getting-started--)
    - [📋 Prerequisites](#-prerequisites)
    - [📁 Setup](#-setup)
    - [📥 Installation](#-installation)
    - [💾 Database](#-database)
    - [💻 Usage](#-usage)
  - [👨‍🚀 Author  ](#-author--)
  - [🎯 Future Features  ](#-future-features--)
  - [🤝 Contribution  ](#-contribution--)
  - [💖 Show Your Support  ](#-show-your-support--)
  - [🙏 Acknowledgements](#-acknowledgements)
  - [📜 License ](#-license-)
</details>

# 👋 Greeting App : Backend Repo

**This project is a backend server for my greeting app.**

The Greeting App is a simple web application built to demonstrate the implementation of a connection between a Ruby on Rails back-end and a React front-end. It generates random greetings and serves as a learning tool for understanding the integration between these two technologies.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 📂 Frontend Repository

The frontend repository for the Greeting App can be found at [hello-react-front-end](https://github.com/indiecodermm/hello-react-front-end). It contains the code for the user interface and interacts with the backend server.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🧰 Tech Stack  <a name="tech-stack"></a>

The backend server is built using the following technologies:

- Framework: Ruby on Rails
- Database: PostgreSQL

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ✨ Key Features  <a name="key-features"></a>

The backend server provides the following key features:

**Random Greeting Endpoint**
- Endpoint: `/random_greeting`
- Description: This endpoint returns a random greeting message.
- Method: GET
- Response: JSON object with the following structure:

```json
{
  "greeting": "Hello, World!"
}
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## 📘 Getting Started  <a name="getting-started"></a>

To run this project locally, you'll need to follow these steps.

### 📋 Prerequisites

Make sure you have the following installed on your machine:
- [Ruby 3.1.3 or higher](https://www.ruby-lang.org/en/)
- [Rails 7.0.4 or higher](https://rubyonrails.org/)
- [PostgreSQL 15.2 or higher](https://www.postgresql.org/)

### 📁 Setup

Clone this repository to your desired foler.

```sh
cd my-project
git clone git@github.com:IndieCoderMM/hello-rails-react.git .
```

### 📥 Installation

Install the required gems with:

```sh
bundle install
```

### 💾 Database

Create the databases and run migrations with:

```sh
rails db:create
rails db:migrate
```

To load the sample data, run:

```sh
rails db:seed
```

### 💻 Usage

To run the development server, execute the following command:

```sh
rails server
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 👨‍🚀 Author  <a name="author"></a>

I am always looking for ways to improve my project. If you have any suggestions or ideas, I would love to hear from you.

**Hein Thant**

[![Github](https://img.shields.io/badge/GitHub-673AB7?style=for-the-badge&logo=github&logoColor=white)](https://github.com/IndieCoderMM)
[![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/hthantoo)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hthant00chk@gmail.com)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🎯 Future Features  <a name="future-features"></a>

- [ ] Add more endpoints
 
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🤝 Contribution  <a name="contribution"></a>

Contributions, issues, and feature requests are welcome! 

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 💖 Show Your Support  <a name="support"></a>

If you like this project, please consider giving it a ⭐.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🙏 Acknowledgements

I would like to thank all code reviewers for making this project better.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 📜 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>