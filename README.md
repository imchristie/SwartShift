﻿# SmartShift
 
 May need to import with the following commands:
 
- npx expo install expo-image-picker \
- yarn add react-native-countdown-circle-timer \
- expo install react-native-svg \


Made a change in timer.js, in node_modules/react-native-stopwatch-timer.
added "this.setState({remainingTime: this.props.totalDuration})" on line 72 to prevent recursion. 
