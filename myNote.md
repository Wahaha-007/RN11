# Additional Installation Steps

# 1. DOTENV ( https://www.npmjs.com/package/react-native-dotenv )

Step 1: $ npm install react-native-dotenv

Step 2: Add content to file babel.config.js
plugins: ['module:react-native-dotenv'],

Step 3: Create .env file
API_TOKEN=abc123

Step 4: import to use
import {API_TOKEN} from "@env"
