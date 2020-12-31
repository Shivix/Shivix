### Welcome to my GitHub

[![Linkedin Badge](https://img.shields.io/badge/-Shivix-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/mark-oborne-534301196/)](https://www.linkedin.com/in/mark-oborne-534301196/)

- 🔭 I’m currently working on [my own version of the STL](https://github.com/Shivix/Shivix-Standard-Library)

```cpp
class aboutMe{
    const std::string_view name{"Mark"};
    
    bool isLookingForWork{true};
    
    std::string languages{"C++, Rust, Bash, Python, Lua, MySQL"};
    std::string tools{"Git, GCC, Clang-tidy, CMake, Boost.test, wxWidgets, OpenCV, Vulkan, SFML, ASIO, Berkeley sockets"};
    [[nodiscard]] std::string getSkills() const noexcept{
        return languages + tools;
    }
    const std::string_view IDEs{CLion, Neovim};
};
```
