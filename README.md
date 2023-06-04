# MyContactsApp
Here's an explanation of the components used in the code and the libraries/plugins utilized:

1.Components:

<li>View: A container component that provides a flexible container for other components.</li>
<li>Text: A component used for displaying text.</li>
<li>TextInput: A component that allows users to input text.</li>
<li>FlatList: A component for rendering lists efficiently.</li>
<li>TouchableOpacity: A wrapper component that allows handling touch events.</li>
<li>Modal: A component that provides a modal view with animation support.</li>

2.Libraries and Plugins:

<li>react: The core library for building user interfaces in React.</li>
<li>react-native: The library that enables building native mobile apps using React.</li>
<li>expo: A platform that provides various tools and services for building React Native apps.</li>
<li>expo-contacts: A module provided by Expo that allows accessing the device's contacts.</li>
  
The code uses the useState and useEffect hooks from React to manage state and perform side effects respectively. The useState hook is used to manage the state variables for contacts, search text, and the selected contact. The useEffect hook is used to request permissions and fetch the device's contacts when the component mounts.

The TextInput component is used to input and search for contacts by updating the searchText state variable. The FlatList component is used to render the filtered contacts in a list format. Each contact item is wrapped in a TouchableOpacity component to enable interaction when clicked.

The Modal component is used to display the details of the selected contact. It appears when a contact is clicked and disappears when the "Close" button is pressed.

Overall, the code follows the React Native development approach with the help of Expo to simplify the development process and access the device's contacts using the expo-contacts module.

For Run This Project Use in terminal :
npm start

For Running This Project On Your Phone Use :
Expo Go https://expo.dev/client 

