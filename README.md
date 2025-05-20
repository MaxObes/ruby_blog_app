# Blog App

A simple blog application built with Ruby on Rails and styled using Tailwind CSS.

## Prerequisites
- Ruby (version matching `.ruby-version`; e.g. 3.3.0)
- Rails 7+
- Node.js and Yarn
- SQLite3 (or another database of your choice)
- [Tailwind CSS](https://tailwindcss.com/) via `tailwindcss-rails` gem

## Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/blog_app.git
   cd blog_app
   ```

2. **Install dependencies:**

   ```bash
   bundle install
   yarn install --check-files
   ```

3. **Set up the database:**

   ```bash
   bin/rails db:create
   bin/rails db:migrate
   ```

4. **Install Tailwind CSS:**

   If not already installed:

   ```bash
   bin/rails tailwindcss:install
   ```

5. **Start the development server:**

   ```bash
   bin/dev
   ```

   This runs both the Rails server and Tailwind build watcher.

6. **Visit the app:**

   Open your browser and go to [http://localhost:3000](http://localhost:3000)

## Notes

- To create new posts, visit `/posts`
- Tailwind CSS is integrated for rapid styling.
- Uses Turbo and Hotwire by default in Rails 7.

## License

MIT
