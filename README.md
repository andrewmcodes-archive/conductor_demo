# README

![conductor UI walkthrough](https://github.com/andrewmcodes/conductor_demo/raw/master/docs/walkthrough.gif)

## Prerequisites

The setups steps expect following tools installed on the system.

- Github
- Ruby [2.6.6](https://github.com/andrewmcodes/conductor_demo/blob/master/.ruby-version#L1)
- Node [> 11](https://github.com/andrewmcodes/conductor_demo/blob/master/.nvmrc#L1)
- SQLite

### 1. Check out the repository

```bash
git clone git@github.com:andrewmcodes/conductor_demo.git
```

### 2. Setup

Run the following commands to install dependencies and set up the database.

```sh
bin/setup
```

### 3. Start the Rails server

You can start the rails server using the command given below.

```ruby
bin/rails server
```

And now you can visit the site with the URL http://localhost:3000

### 4. View the Conductor

Visit http://localhost:3000/rails/conductor in your browser
