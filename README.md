# DrupalArt

DrupalArt is a Drupal-based project designed for building and managing creative digital experiences.

---

## 🚀 Getting Started

Follow these steps to set up the project locally.

---

## 📦 Prerequisites

Make sure you have installed:

- PHP (compatible with your Drupal version)
- Composer
- DDEV
- Docker

---

## 📥 Installation

Clone the repository:

```bash
git clone git@github.com:drupalart.git
cd drupalart
```

Install PHP dependencies using Composer:

```bash
composer install
```

---

## 🐳 DDEV Setup

[DDEV](https://ddev.readthedocs.io/) is used for local development.

### 1. Start DDEV

```bash
ddev start
```

### 2. Install Drupal (if not already installed)

```bash
ddev drush site:install
```

Or import an existing database:

```bash
ddev import-db --src=path/to/your/database.sql
```

### 3. Access the project

```bash
ddev launch
```

---

## 🛠 Useful DDEV Commands

- Start project:

  ```bash
  ddev start
  ```

- Stop project:

  ```bash
  ddev stop
  ```

- SSH into container:

  ```bash
  ddev ssh
  ```

- Run Drush commands:

  ```bash
  ddev drush status
  ```

---

## 🔄 Updating Dependencies

To update Composer dependencies:

```bash
composer update
```

---

## 📂 Project Structure

- `web/` – Drupal root directory
- `config/` – Configuration exports
- `vendor/` – Composer dependencies

---

## 🤝 Contributing

1. Create a feature branch
2. Commit your changes
3. Push and open a pull request

---

## 📄 License

Specify your license here (e.g., MIT, GPL).

---

## 🙋 Support

For issues or questions, please open an issue in the repository.
