# WhatsApp 2.0 App UI (Front-end-UI Only)
A clone of the popular Realtime Chat mobile applications WhatsApp in React Native with WhatsApp UI frontend design. The UI contains a WhatsApp-alike main chat screen. Clicking on these `Chats` will be redirected to open a private chat room to allow the user to send messages to make conversations with other users. It contains a list of messages with styles and `Contacts` with different users' statuses.
## ***[Copyright and Commercial Use Disclaimer](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/README.md#please-carefully-read-licensemd-about-the-open-source-restrictions-and-the-personal-use-policy-of-this-project-under-gpl-30-license-any-commericial-uses-on-this-project-by-other-than-the-owner-krystalzhang612-or-the-authorized-users-and-organizations-including-unauthorized-modifications-forks-pull-requests-and-other-commercial-related-uses-will-be-subjected-to-copyright-violation-with-sebsequent-legal-concerns)***

⏬

### ***Please carefully read [LICENSE.md](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/LICENSE) about the Open Source restrictions and the personal use policy of this project under [GPL-3.0 license](https://www.gnu.org/licenses/gpl-3.0.en.html), any commericial uses on this project by other than the owner [@KrystalZhang612](https://github.com/KrystalZhang612) or the authorized users and organizations, will be subjected to copyright violation with sebsequent legal potential concerns.***

## WhatsApp 2.0 App Front-End-UI Overview:
<p align ="center">
  <img src ="https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/WhatsApp%202.0%20App%20UI%20Overview-1.PNG" width="380" height="848.818181">&nbsp; 
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/WhatsApp%202.0%20App%20UI%20Overview-2.PNG" width="380" height="848.818181">
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/WhatsApp%202.0%20App%20UI%20Overview-3.PNG"  width="380" height="848.818181">&nbsp; 
  <img src ="https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/WhatsApp%202.0%20App%20UI%20Overview-4.PNG"  width="380" height="848.818181">
</p> 


# Build
[Method to Run & Test the Project Locally](https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/README.md#method-to-run--test-the-project-locally)<br/> 
[Prerequisites & Setups](https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/README.md#prerequisites--setups)<br/> 
[Debugging&Troubleshooting](https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/README.md#debuggingtroubleshooting)<br/> 
[Synchronous Developing Notes](https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/README.md#synchronous-developing-notes)<br/> 
[Testing Result](https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/README.md#testing-result)<br/> 
[Tags and Topics](https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/README.md#tags-and-topics)<br/> 
# Contribution
[Author](https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/README.md#author)
# Compatibility
|   OS             | Supported          |
| -------          | ------------------ |
| iOS 10+          | :white_check_mark: |
| < iOS 10         | :x:                |
| Android          | ✅                 |
| Expo Web Server  | :x:                |
# Method to Run & Test the Project Locally
### Download the entire project to localhost. 
### Download needed dependencies and extension tools refer to [README](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/README.md)
### Open the project with Vscode, run to test WhatsApp 2.0 UI with `npm start`
### Have Xcode Simulator installed, press `i` to run Metro iOS bundle.
# 🛠️ Developing Languages, Tools, and Techniques Needed
[Expo](https://docs.expo.dev/get-started/create-a-new-app/)<br/> 
[Xcode iOS 16.1 iPhone 14 Simulator](https://developer.apple.com/xcode/)<br/> 
[Vscode](https://code.visualstudio.com/updates/v1_73)<br/> 
[React-Native v0.70.5](https://reactnative.dev/)<br/> 
[Day.js 2kB](https://day.js.org/)<br/> 
[Ether Creative Shadow Generator](https://ethercreative.github.io/react-native-shadow-generator/)<br/>
[Expo Icons](https://icons.expo.fyi)<br/>
[JavaScript](https://www.javascript.com)<br/>
<div>
  <img src ="https://github.com/devicons/devicon/blob/master/icons/xcode/xcode-original.svg" width = "60" height ="60" title = "XCODE"/>&nbsp; 
  <img src ="https://github.com/devicons/devicon/blob/master/icons/vscode/vscode-original.svg" width = "60" height ="60" title = "VSCODE"/>&nbsp; 
  <img src ="https://github.com/devicons/devicon/blob/master/icons/react/react-original.svg" width = "60" height ="60" title = "REACT"/>&nbsp; 
  <img src ="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg"  width = "60" height ="60" title = "javascript"/>&nbsp; 
</div>

# Prerequisites & Setups
In local Console, initialize to create the react expo app running:
```bash
npx create-expo-app WhatsApp2.0
```
Configure the Xcode iOS Simulator:<br/> 
https://developer.apple.com/forums/thread/678469<br/> 
Xcode -> Preferences -> locations -> "Command Line Tools"<br/> 
Open the created project in Vscode and start the server development at Terminal:
```bash
npm start
```
Press i to open iOS Simulator.<br/> 
Successfully started Expo Developer Tool Metro Bundler with IOS Simulator.<br/> 
[started expo with ios simulator.PNG](https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/started%20expo%20with%20ios%20simulator.PNG)<br/>
# Synchronous Developing Notes
## ***Build the chat list item:***
Insert sample chat container, chat content and customize styles in [/ChatListItem/index.js](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/src/components/ChatListItem/index.js):
```JavaScript
  <View style={styles.content}>
                <View style={styles.row}>
                    <Text style={styles.name}>Scarlett</Text>
                    <Text style={styles.subTitle}>8:30</Text>
...
 const styles = StyleSheet.create({
    container: {
        flexDirection: 'row',
        marginHorizontal: 10,
        marginVertical: 5,
        height: 70,
...
```
[chat list items created.PNG](https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/chat%20list%20items%20created.PNG)<br/>
Add props:
```JavaScript 
const ChatListItem = (props) => {
    console.log(props);
```
[fetched props in log.PNG](https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/fetched%20props%20in%20log.PNG)<br/>
Import chat list of profile pictures into [ChatsScreen.js](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/src/screens/ChatsScreen.js):
```JavaScript 
import { View, Text, FlatList } from 'react-native'; import chats from '../../assets/data/chats.json'; import ChatListItem from '../components/ChatListItem'; const ChatsScreen = () => {
    return (<FlatList data={chats} renderItem={({ item }) =>
<ChatListItem chat={item} />} />
); };
export default ChatsScreen;
```
[list of chatters profiles showed up.PNG](https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/list%20of%20chatters%20profiles%20showed%20up.PNG)<br/>
Remove `align-item: center` in [App.js](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/App.js)<br/>
[chats all popped up.PNG](https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/chats%20all%20popped%20up.PNG)<br/>
Open another terminal and install Day.js by running:
```bash 
npm install dayjs
```
## ***Build chat screen:***
Render messages in [ChatScreen.js](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/src/screens/ChatScreen.js):
```JavaScript 
 <ImageBackground source={bg} style={styles.bg}>
            <FlatList
                data={messages}
                renderItem={({ item }) => <Message message={item} />}
                style={styles.list}
                inverted
            />
        </ImageBackground>
);
```
[text messages are rendered.PNG](https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/text%20messages%20are%20rendered.PNG)<br/>
render both text contents and time in [/Message/index.js](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/src/components/Message/index.js):
```JavaScript 
<View style= {styles.container}>
            <Text>{message.text}</Text>
            <Text style={styles.time}>{message.createdAt}</Text>
```
[text content and time rendered.PNG](https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/text%20content%20and%20time%20rendered.PNG)<br/>
Set colors and flex positions to distinguish from sender and receiver:
```JavaScript 
 <View style={[styles.container, {
            backgroundColor: isMessage() ? '#DCF8C5' : 'white',
            alignSelf: isMessage() ? 'flex-end' : 'flex-start'
```
[sender and receiver distinguished.PNG](https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/sender%20and%20reciever%20distinguished.PNG)<br/>
Add background shadow and rearrange messages order:
```JavaScript 
  //shadows
        shadowColor: '#000',
        shadowOffset: {
            width: 0,
height: 1, },
        shadowOpacity: 0.18,
        shadowRadius: 1.0,
        elevation: 1,
```
[modified order and shadow added.PNG](https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/modified%20order%20and%20shadow%20added.PNG)<br/>
Design text input box and icons in [/InputBox/index.js](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/src/navigation/index.js):
```JavaScript 
container: {
        flexDirection: 'row',
        backgroundColor: 'whitesmoke',
        padding: 5,
}, input: {
        flex: 1,
        backgroundColor: 'white',
        padding: 5,
        paddingHorizontal: 10,
        borderRadius: 50,
        borderColor: 'lightgray',
        borderWidth: StyleSheet.hairlineWidth,
```
[text input box designed.PNG](https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/text%20input%20box%20designed.PNG)<br/>
Set up sending state as console:
```JavaScript 
 //state data
    const [newMessage, setNewMessage] = useState('');
    const onSend = () => {
        console.warn('Sending a new message:', newMessage);
        setNewMessage('');
```
Now sending state console with the sending message content showed when click send button:<br/>
[sending state console showed.PNG](https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/sending%20state%20console%20showed.PNG)<br/>
## ***React navigation:***
Install dependencies by running these command in vscode:
```bash 
npx expo install @react-navigation/native @react-navigation/native-stack @react-navigation/bottom-tabs react-native-screens react-native-safe-area-context
```
[navigation bar displayed.PNG](https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/navigaton%20bar%20displayed.PNG)<br/>
Import different navigation bars and their icons:<br/>
[navigation bars imported.PNG](https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/navigation%20bars%20imported.PNG)<br/>
Import different navigation screen bars in [MainTabNavigator.js](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/src/navigation/MainTabNavigator.js):
```JavaScript 
 <Tab.Screen
            name="Status"
                component={NotImplementedScreen}
                options={{
                    tabBarIcon: ({ color, size }) => (
                 <Ionicons name="logo-whatsapp" size={size}
color={color} />
...
```
[different navigator screens.PNG](https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/different%20navigator%20screens.PNG)<br/>
## ***Build Contact screen:***
Use `onPress` method to be redirected to contacts:
```JavaScript
 headerRight: () => (
            <Entypo
           onPress={() => navigation.navigate("Contacts")}
                     name="new-message"
                     size={18}
                     color={'royalblue'}
                     style={{ marginRight: 15 }}
```
Now click the button on right-top, contact list showed:<br/>
[contact list showed.PNG](https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/contact%20list%20showed.PNG)<br/> 

# Debugging&Troubleshooting
Image Error: `Image source = {{uri:’...’}}` not displaying image on iOS Bundle. DEBUGGING: https://github... URL prefix blocked, click Download in github image to obtain a different downloading url. Use CMD+D to inspect elements. SHIFT+ i to switch iOS simulators.
# Testing Result
<p align = "center">
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/started%20expo%20with%20ios%20simulator.PNG" width = "380" height = "848.81818">&nbsp;
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/chat%20list%20items%20created.PNG" width = "380" height = "848.81818">&nbsp;
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/fetched%20props%20in%20log.PNG" >&nbsp;
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/list%20of%20chatters%20profiles%20showed%20up.PNG" width = "380" height = "848.81818">&nbsp;
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/chats%20all%20popped%20up.PNG" width = "380" height = "848.81818">&nbsp;
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/text%20messages%20are%20rendered.PNG" width = "380" height = "848.81818">&nbsp;
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/text%20content%20and%20time%20rendered.PNG" width = "380" height = "848.81818">&nbsp;
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/sender%20and%20reciever%20distinguished.PNG" width = "380" height = "848.81818">&nbsp;
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/modified%20order%20and%20shadow%20added.PNG" width = "380" height = "848.81818">&nbsp;
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/text%20input%20box%20designed.PNG" width = "380" height = "848.81818">&nbsp;
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/sending%20state%20console%20showed.PNG" width = "380" height = "848.81818">&nbsp;
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/navigaton%20bar%20displayed.PNG" width = "380" height = "848.81818">&nbsp;
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/navigation%20bars%20imported.PNG" width = "380" height = "848.81818">&nbsp;
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/different%20navigator%20screens.PNG" width = "380" height = "848.81818">&nbsp;
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-WhatsApp-2.0-App-UI/blob/main/testing-result-WhatsApp2.0/contact%20list%20showed.PNG" width = "380" height = "848.81818">&nbsp;
</p>





# Tags and Topics
vscode, ui, front-end-ui, javascript, whatsapp-2.0, realtime-chatting-app, react-native, expo-go, xcode, ios-simulator, metro-bundling, dayjs, npm, npx. 
# Author
Krystal Zhang
https://github.com/KrystalZhang612<hr>
*This file was generated by [WhatsApp2.0AppUI-readme](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/README.md), on November 10th, 2022*

