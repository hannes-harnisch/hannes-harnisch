## 💠 Hi, I'm Hannes.

I'm a software engineer focusing on application development, especially with C++, Java, C# and Kotlin.

- 💠 My ongoing project is the compiler for [Cero](https://github.com/hannes-harnisch/Cero), a new general-purpose systems programming language.
- 🐉 Currently learning various things related to compiler implementation.
- 🏵️ Passionate about programming language design.
- 🚀 Interested in all things performance-critical, graphics, audio, physics, networking and operating systems.
- ♦️ Working at AnyDesk, primarily on the Android app, but also other platforms.
- 🏹 Fun fact: This is the simplest way to leak memory in C++ with reference cycles:
```c++
#include <memory>

struct S {
    std::shared_ptr<S> s;
};

int main() {
    auto s = std::make_shared<S>();
    s->s = s;
}
```