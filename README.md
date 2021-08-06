<!--
**GodlyDuck/GodlyDuck** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
### Hi there 👋
-->
```python
import stupidDuck
import threading

def dumb():
    print("Welcome To My Github")

for i in range(50):
    thread = threading.Thread(target=dumb, daemon=True)
    thread.start()
    time.sleep(0.3)

print("<3")
```
