# 🏃 Run ("RunLang") 

<img width="326" height="213" alt="RunLang Image" src="https://github.com/user-attachments/assets/0981ded3-4a27-45dd-b129-b3029f741ec4" />

[![Version](https://img.shields.io/badge/version-1.0.0-blue)](https://github.com/Kinshuk14/RunLang) 
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE) 
[![Platform](https://img.shields.io/badge/platform-Windows-orange)](https://github.com/Kinshuk14/RunLang)
[![Platform](https://img.shields.io/badge/platform-Linux_windows_subsystem-red)](https://github.com/Kinshuk14/RunLang)

RunLang is a **fast, lightweight scripting language** for quick execution and compilation.  
It is a **superset of the Go (Golang) programming language**, designed for simplicity, speed, and memory efficiency.  

RunLang allows you to **import and export packages**, delete unused functions for memory optimization, and even use the **Love2D framework** inside Go.  

---

## 🌈 Quick Commands

| 🔹 | Command | Description |
|----|---------|-------------|
| 1️⃣ | `Run gain speed xyz.run` | Run a file **without building an `.exe`** |
| 2️⃣ | `Run build building xyz.run` | Build a file **to `.exe`** without running |
| 3️⃣ | `Run build xyz.run` | Build and **run the `.exe` immediately** |
| 4️⃣ | `Run make exe` | Build a **whole project to `.exe`** |
| 5️⃣ | `Run be careless for exe` | Run a **whole project without building `.exe`** |

---

## 💻 Installation
**Clone the repository**
~~~shell
git clone https://github.com/Kinshuk14/RunLang.git
~~~
**Move into the project folder**
~~~bash
cd RunLang
~~~
## RunLang Syntax
RunLang is a superset of Go with simplified syntax for quick scripting. Key syntax elements include:

Functions: Define functions using fn instead of func.
Packages: Use import "package_name" to import packages and export "package_name" to export them.
Printing: Use fmt.Writeln to print text to the console with a newline.
File Extension: Save RunLang files with a .run extension.

For complete syntax details, refer to syntax.txt in the project folder.

## Samples

#### Print a String
```Go
package main

import "fmt"

fn main() {
    fmt.Writeln("Yo, Guys")
}
```
export "fmt"
This code:

Imports the fmt package for formatting and printing.
Defines a main function using fn that prints "Yo, Guys" to the console.
Exports the fmt package for use in other modules.
Save it as example.run and run with Run gain speed example.run

#### Variables and constants
```Go
var X string = "Hello"
var Y num = 2
var Z float = 32.34
var XYZ boolean = True

//or

Make X string = "Hello"
Make Y num = 2
Make Z float = 32.34
Make XYZ boolean = True

//or

X is 2
Y is "Hello"
Z is 32.34
ZYZ IS True

//for consts

const X is "Hello"

//or

const Make X string = "Hello"
~~~
