# SmartShift

Made a change in timer.js, in node_modules/react-native-stopwatch-timer.
added "this.setState({remainingTime: this.props.totalDuration})" on line 72 to prevent recursion. 
