### Welcome to my GitHub

[![Linkedin Badge](https://img.shields.io/badge/-Shivix-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/mark-oborne-534301196/)](https://www.linkedin.com/in/mark-oborne-534301196/)

- 🔭 I’m currently working on [my own version of the STL](https://github.com/Shivix/Shivix-Standard-Library)

```cpp
class AboutMe{
    const std::string_view name{"Mark"};
    
    std::string languages{"C++, Rust, Bash, Lua, Python"};
    std::string tools{"Git, GCC, Clang-tidy, CMake, Boost.test, wxWidgets, OpenCV, Vulkan, SFML, ASIO, Berkeley sockets"};
    [[nodiscard]] std::string get_skills() const noexcept{
        return languages + tools;
    }
    const std::string_view ides{"CLion, Neovim"};
};
```
