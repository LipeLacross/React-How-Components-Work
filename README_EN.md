## 🌐 [English Version of README](README_EN.md)

# Organo

Organo is a React application that allows the management of teams and collaborators, with functionalities such as changing team colors, favoriting collaborators, and deleting records. It offers an interactive interface to create, modify, and view teams, their members, and details.

## 🔨 Project Features

- **Collaborator Registration**: Allows adding collaborators with information such as name, position, and photo.
- **Team Management**: Creation and customization of teams with colors and names, as well as the ability to change the team's color.
- **Favorites**: Marking collaborators as favorites.
- **Deletion**: Option to delete collaborators from a team.
- **Responsiveness**: Layout adaptable to different screen sizes, optimized for mobile and desktop devices.

### Visual Example of the Project

![Visual Example of the Project](https://github.com/user-attachments/assets/60ce2f8a-8aa2-453c-bcf4-9cc1f5b31b01)

## ✔️ Techniques and Technologies Used

- **React.js**: JavaScript framework for building the interface.
- **CSS3**: Styling components and responsive layout.
- **Hex-to-RGBA**: Library used to convert hexadecimal color values to RGBA, allowing transparency in the team backgrounds.
- **React Icons**: Library for using icons in the project.
- **UUID**: Library for generating unique IDs for collaborators and teams.
- **React DOM**: Rendering components in the browser.

## 📁 Project Structure

- **public/**
  - **favicon.ico**: Site icon.
  - **index.html**: Main HTML file.
  - **imagens/**: Contains project images (logo, social media icons, team backgrounds, etc.).
    - `banner.png`: Main banner image.
    - `btn-icone.png`: Icon for buttons.
    - `facebook.png`: Facebook icon.
    - `fundo.png`: Team background image.
    - `instagram.png`: Instagram icon.
    - `logo.png`: Organo logo.
    - `twitter.png`: Twitter icon.
  - **logo192.png**: Logo in 192x192 pixels size.
  - **logo512.png**: Logo in 512x512 pixels size.
  - **manifest.json**: Manifest configuration for PWA.
  - **robots.txt**: Configuration file for search engine robots.

- **src/**
  - **App.js**: Main component of the project that manages the state of teams and collaborators.
  - **componentes/**
    - **Banner/**
      - `index.js`: Banner component.
      - `banner.css`: Banner styles.
    - **Botao/**
      - `index.js`: Button component.
      - `botao.css`: Button styles.
    - **Campo/**
      - `index.js`: Input field component.
      - `campo.css`: Field styles.
    - **Colaborador/**
      - `index.js`: Component to display a collaborator's information.
      - `colaborador.css`: Collaborator styles.
    - **Formulario/**
      - `index.js`: Form component for registering collaborators and teams.
      - `formulario.css`: Form styles.
    - **ListaSuspensa/**
      - `index.js`: Dropdown list component.
      - `lista-suspensa.css`: Dropdown list styles.
    - **Rodape/**
      - `index.js`: Footer component.
      - `rodape.css`: Footer styles.
    - **Time/**
      - `index.js`: Component to display a team and its collaborators.
      - `time.css`: Team styles.
  - **index.css**: Global styles file.
  - **index.js**: File that initializes and renders the project in the browser.
  - **setupTests.js**: Test configuration to ensure components are working correctly.

- **package.json**: npm configuration file with project dependencies.
- **package-lock.json**: npm lock file to ensure consistent dependency versions.
- **README.md**: Project documentation (this file).
- **README_EN.md**: English version of the README.
- **LICENSE**: Project license file.

## 🛠️ Open and Run the Project

To start the project locally, follow the steps below:

1. **Ensure Node.js is Installed**:
   - [Node.js](https://nodejs.org/) is required to run the project. You can check if you have it installed with:

   ```bash
   node -v
   ```

- If not installed, download and install the recommended version.

2. **Clone the Repository**:
    - Copy the repository URL and execute the command below in the terminal:

   ```bash
   git clone <REPOSITORY_URL>
   ```

3. **Install Dependencies**:
    - Navigate to the project directory and install dependencies with the following command:

   ```bash
   npm install
   ```

4. **Run the Project**:
    - After installation, start the local server with the command:

   ```bash
   npm start
   ```

   The project will be available at `http://localhost:3000`.

## 🌐 Deploy

To deploy the project, you can use services like [Vercel](https://vercel.com/) or [Netlify](https://www.netlify.com/). Follow the steps below to deploy on Vercel:

1. **Create a Vercel Account** (if you don't have one): [Vercel Signup](https://vercel.com/signup).
2. **Connect Your GitHub Repository**: In the Vercel dashboard, connect your GitHub repository with the project.
3. **Select the Repository and Click Deploy**: Vercel will automatically detect the framework and create a deploy for you.
4. **Access the Published Site**: After the deployment is complete, you will receive a link to access the project.
