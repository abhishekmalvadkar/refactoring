- Always do frequent and small small commits because it has two advantages
- If your system crash, your code is already committed
- While refactoring legacy code if you done some mistake so you can easily revert that part only love 💕
- I have configured my Intelij as when I have created new method then it throws Unsupported operation exception with string like Not Implemented so I can know which is not implemented 👍
- I like to separate static variable with instance variable by separate line 👍
- Create constant for number using primitive , so we can get rid of boxing and unboxing kind of things because it's expensive and also get rid of object creation process because it's also expensive 💕
- Once you thing all good always commit that moment code love 💕
- Always use refactoring provided by Intelij because it's safe Refactoring and 99.9 % it's safe but when working with legacy code then give extra care when Refactoring because you don't know what will happen 🤞
- Always eliminate feature Envy code smell means if the logic is associated with objct state then move that logic inside object class itself , example isActive() so you will have user.isActive() call 💕
- Another example of feature Envy is isFeatureEnabled()
- Always highlight variable to see where it is used and if some if and throw are in first line then make variables after that if not used in those ifs , and put variables very close to the code where it is used so we can easily extract that portion as method 🥳
- when you have if at the starting which return the control only then take help from intelij to invert the if in better shape 💕
