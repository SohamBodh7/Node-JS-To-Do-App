# Todo List App Dependencies and Run Commands

## Windows Setup

### System Dependencies Installation

1. Download and install Node.js (LTS) from https://nodejs.org/
2. Download and install Git from https://git-scm.com/downloads
3. Verify installations:
   ```cmd
   node --version
   npm --version
   git --version
   ```

### Project Setup

```cmd
# Clone the repository (if not already done)
git clone https://github.com/dwyl/javascript-todo-list-tutorial.git
cd javascript-todo-list-tutorial

# Install npm dependencies
npm install
```

### Run the Project

```cmd
# Start the development server
npm start
```

### Access the Application

Open a web browser and navigate to: `http://localhost:8000`

### Run Tests (Optional)

```cmd
# Run the test suite
npm test
```

### Development with Live Reload

```cmd
# Start live-server for development
npm run dev
```

## Ubuntu Setup

### System Dependencies Installation

```bash
# Update package lists
sudo apt update

# Install Node.js (LTS) and npm
curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
sudo apt-get install -y nodejs
sudo install -g npm

# Install Git
sudo apt install git -y

# Verify installations
node --version
npm --version
git --version
```

### Project Setup

```bash
# Clone the repository (if not already done)
git clone https://github.com/dwyl/javascript-todo-list-tutorial.git
cd javascript-todo-list-tutorial

# Install npm dependencies
npm install
```

### Run the Project

```bash
# Start the development server
npm start
```

### Access the Application

Open a web browser and navigate to: `http://localhost:8000`

### Run Tests (Optional)

```bash
# Run the test suite
npm test
```

### Development with Live Reload

```bash
# Start live-server for development
npm run dev
```
