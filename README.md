# ZooLens: Animal Identifier

ZooLens is a web application that allows users to upload images of animals. It classifies the animal in the image, fetches relevant Wikipedia data about the animal, and determines its "danger status" based on certain keywords found in the description.

The app uses a machine learning model to classify the animal and an AI agent to gather information from Wikipedia. To set it up, first clone the repository using `git clone https://github.com/your-username/zoolens.git`. Navigate to the project directory with `cd zoolens` and install the necessary dependencies using `npm install`.

You will also need to create a `.env` file in the root directory and add your **Jina API Key** as `JINA_API_KEY=your-jina-api-key`. Once that's done, start the development server with `npm run dev`.

The application will be available in your browser at [http://localhost:3000](http://localhost:3000). To use the app, simply upload an image of an animal.

The app will classify the animal and fetch introductory information about it from Wikipedia. The animal’s description will be analyzed to determine its danger status, based on specific keywords (e.g., "dangerous", "aggressive", "predator"). The description and danger status will be displayed to the user.
