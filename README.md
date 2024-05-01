- 👋 Hi, I’m @6666771
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
6666771/6666771 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->class GameHelperMenu:
    def __init__(self):
        self.options = ["无敌模式", "无限金币", "快速升级"]

    def display_menu(self):
        for option in self.options:
            print(option)

    def select_option(self, option):
        if option in self.options:
            print(f"选择了 {option}")
        else:
            print("无效的选项")

# 创建菜单实例
menu = GameHelperMenu()

# 显示菜单
menu.display_menu()

# 选择选项
menu.select_option("无敌模式")
