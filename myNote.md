# Additional Installation Steps

# 1. DOTENV ( https://www.npmjs.com/package/react-native-dotenv )

Step 1: $ npm install react-native-dotenv

Step 2: Add content to file babel.config.js
plugins: ['module:react-native-dotenv'],

Step 3: Create .env file
API_TOKEN=abc123

Step 4: import to use
import {API_TOKEN} from "@env"

# 2. React Native Async Storage

Step 1: > npm install @react-native-async-storage/async-storage

Step 2: Import and use it

import AsyncStorage from '@react-native-async-storage/async-storage';

Write => AsyncStorage.setItem('token', token); // 2nd arg must be String
Read => const storedToken = await AsyncStorage.getItem('token');

# 3. Expo App Loading screen

Step 1: expo install expo-app-loading
