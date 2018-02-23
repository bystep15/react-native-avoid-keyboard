# react-native-avoid-keyboard
ScrollView和FlatList的高阶函数，避免键盘遮挡底部元素

基于React Native的[KeyboardAvoidingView](https://github.com/facebook/react-native/blob/master/Libraries/Components/Keyboard/KeyboardAvoidingView.js)源码改写。

[文档](https://facebook.github.io/react-native/docs/keyboardavoidingview.html)中的relativeKeyboardHeight、onKeyboardChange、onLayout三个方法在KeyboardAvoidingView源码中不一致，其中onLayout会直接覆盖内部的方法。

为了使用方便，将其改写为常用的ScrollView和FlatList的高阶函数。
