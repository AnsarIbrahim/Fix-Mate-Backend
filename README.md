<a name="readme-top"></a>

<div align="center">
  <h1>Fix-Mate-Backend</h1>
</div>

# 📗 Table of Contents

- [📗 Table of Contents](#-table-of-contents)
- [👨‍💻 Fix Mate ](#-fix-mate-)
  - [🛠 Built With ](#-built-with-)
    - [Tech Stack ](#tech-stack-)
    - [Key Features ](#key-features-)
  - [💻 Getting Started ](#-getting-started-)
    - [Prerequisites](#prerequisites)
    - [Setup](#setup)
    - [Installation](#installation)
    - [Database Setup](#database-setup)
    - [Running the App](#running-the-app)
  - [👥 Authors ](#-authors-)
  - [🔭 Future Features ](#-future-features-)
  - [🤝 Contributing ](#-contributing-)
  - [💖 Show your support ](#-show-your-support-)
  - [🙏 Acknowledgments ](#-acknowledgments-)
  - [📝 License ](#-license-)

# [ 👨‍💻 Fix Mate ]<a name="about-project"></a>

**Fix-Mate-Backend** is a Ruby on Rails application. It's the server-side of Fix-Mate, handling database transactions, user authentication, and business logic to assist users. **Fix Mate** is committed to making everyday life more convenient by connecting users with trusted service providers. It is a one-stop platform for finding, booking, and  reviewing services, all from the comfort of your home. Users can communicate with service providers through the app, discussing specific requirements, asking questions, and confirming details.

## API
> - [Base Url](https://fixmate.onrender.com/)

> - API Endpoints
- api/v1/experts
- api/v1/reservations
- api/v1/specializations
> - [API Documentation](https://fixmate.onrender.com/api-docs/index.html)

## Link to Front End
> - [Live Link](https://fixmate.netlify.app/)

> - [Link to Front-end Repository](https://github.com/anita00001/fix-mate-frontend)

## Kanban Board Link
> - [Link to Kanban Board](https://github.com/users/anita00001/projects/5)

> - [Kanban Board Screenshot](https://user-images.githubusercontent.com/24216198/278346153-6af22972-9982-4560-ba4d-c943ffeb9330.png)

> - [Number of Team Members - 4](#-authors-) 

## Entity Relationship Diagram
  ![fixmate_erd_digram](https://github.com/anita00001/fix-mate-backend/assets/117971223/6e6fbe33-9ac7-467d-bdea-a590ee1ea9a8)


## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

<details>
  <summary>Server</summary>
  <ul>
    <li><a href="https://www.ruby-lang.org/en/">Ruby</a></li>
    <li><a href="https://rubyonrails.org/">Ruby On Rails</a></li>
  </ul>
</details>

<details>
  <summary>Database</summary>
  <ul>
    <li><a href="https://www.postgresql.org/">PostgreSQL</a></li>
  </ul>
</details>

### Key Features <a name="key-features"></a>

The key features of this project include.

- **Show all Experts**
- **Reserve an Expert**
- **Show my Reservation**
- **Add an Expert**
- **Delete an Expert**
- **Add a Specialization**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 💻 Getting Started <a name="getting-started"></a>

> - To get a local copy up and running, follow these steps.

### Prerequisites

Before you begin, make sure you have the following installed on your machine:

- [x] Ruby: You can download Ruby [here](https://www.ruby-lang.org/en/downloads/).
- [x] Rails: You can install Rails by running the command `gem install rails` in your terminal.
- [x] Postgres: You can install Postgresql [here](https://www.postgresql.org/download/).
- [x] A code editor (like VSCode, Sublime, Atom, etc.): You can download VSCode [here](https://code.visualstudio.com/download), Sublime [here](https://www.sublimetext.com/3), and Atom [here](https://atom.io/).
- [x] Git: You can download Git [here](https://git-scm.com/downloads).
- [x] Node.js: You can download Node.js [here](https://nodejs.org/en/download/).

> - Version Requirements:
```
  ruby >= 3.2.0
  rails >= 7.0
  postgres >- 15.3
```

### Setup

> - To setup this project locally:

1. Open terminal in VScode.
2. Navigate to the directory where you want clone the copy of this repository.
3. Create new directory [optional].
4. Clone the repository by running the following command:

```sh
git clone https://github.com/anita00001/fix-mate-backend.git
```

5. Navigate into the cloned repository:

```sh
cd fix-mate-backend
```

### Installation

1. Install the required dependencies by running the following command:
```sh
bundle install
```
2. Delete files `/config/credentials.yml.enc` and `/config/master.key`, (if any).
3. Run the command to get the pairs of credentials and master key
```sh
rails credentials:edit
```

### Database Setup

> - To create the database, run the following command:
```sh
rails db:create
```

> - To migrate the database schema, run the following command:
```sh
rails db:migrate
```

> - Feed Sample data through seeds
```sh
  rails db:seed
```

### Run Test

> - Run Linters Check with Rubocop
```sh
  rubocop
```


> - Run Test with RSpec
```sh
rails db:migrate RAILS_ENV=test && rspec spec
```

### Running the App

> - To run the application, run the following command:

```sh
rails server
```

> - This will start the Rails development server and you can access the application by visiting http://localhost:4000 in your web browser.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 👥 Authors <a name="authors"></a>

The collaborators of this project.

👤 **Anita Sharma**
> - [GitHub](https://github.com/anita00001)
> - [LinkedIn](https://www.linkedin.com/in/anitaa-sharmaa/)
> - [Twitter](https://twitter.com/anitaa_sharmaa)

👤 **Ansar Ibrahim**
> - [GitHub](https://github.com/AnsarIbrahim)
> - [LinkedIn](https://linkedin.com/in/ansar-ibrahim/)
> - [Twitter](https://twitter.com/ansaradheeb)

👤 **MoFuhidy**
> - [GitHub](https://github.com/Mofuhidy)
> - [LinkedIn](https://www.linkedin.com/in/mo-fuhidy/)

👤 **Theodore Asimeng-Osei**
> - [GitHub](https://github.com/Theodoraldo)
> - [Twitter](https://twitter.com/AsimengOse33947)
> - [LinkedIn](https://www.linkedin.com/in/theodoreasimeng/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🔭 Future Features <a name="future-features"></a>

- [ ] **Delete Specializations**
- [ ] **Add Admin Role**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🤝 Contributing <a name="contributing"></a>

> - Contributions, issues, and feature requests are welcome!

> - Feel free to check the [issues page](../../issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 💖 Show your support <a name="support"></a>

> - Give a ⭐️, if you like this project!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🙏 Acknowledgments <a name="acknowledgements"></a>

> - We would like to thank [Microverseinc](https://github.com/microverseinc) for [Readme-template](https://github.com/microverseinc/readme-template), our code reviewer and external evaluator. We would extend our sincere gratitude to [Murat Korkmaz on Behance](https://www.behance.net/gallery/26425031/Vespa-Responsive-Redesign) for provinding the original design.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
