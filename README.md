# MediaSorter (medso) 🎥📸

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![GitHub stars](https://img.shields.io/github/stars/kevinveenbirkenbach/mediasorter.svg?style=social)](https://github.com/kevinveenbirkenbach/mediasorter/stargazers)

MediaSorter is a simple CLI tool for organizing your media files by moving them between your Pictures and Videos directories based on their file extensions. Easily sort your media with just a few commands!

---

## 🛠 Features

- **Automatic Sorting:** Moves image files from a Videos directory to Pictures, and video files from a Pictures directory to Videos.
- **Recursive Processing:** Scans all subdirectories within the given source directory.
- **Preview Mode:** See what moves would be performed without actually moving any files.
- **Verbose Output:** Get detailed logs of all file operations.

---

## 📥 Installation

Install MediaSorter via [Kevin's Package Manager](https://github.com/kevinveenbirkenbach/package-manager) under the alias `medso`:

```bash
package-manager install medso
```

This makes MediaSorter globally available as `medso` in your terminal. 🚀

---

## 🚀 Usage

Run MediaSorter by specifying the source folder path (which should be located within either your "Pictures" or "Videos" directory):

```bash
medso /path/to/Pictures
```

### Options

- **`--verbose`**: Print detailed information about each move.
- **`--preview`**: Preview the moves without actually performing them.

### Example Commands

- **Preview moves in Pictures directory:**

  ```bash
  medso /home/username/Pictures --preview --verbose
  ```

- **Move files in Videos directory:**

  ```bash
  medso /home/username/Videos
  ```

MediaSorter will automatically determine the target directory by replacing "Pictures" with "Videos" (or vice versa) and preserve the relative folder structure.

---

## 🧑‍💻 Author

Developed by **Kevin Veen-Birkenbach**  
- 📧 [kevin@veen.world](mailto:kevin@veen.world)  
- 🌐 [https://www.veen.world/](https://www.veen.world/)

---

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 🤝 Contributions

Contributions are welcome! Please feel free to fork the repository, submit pull requests, or open issues if you have suggestions or encounter problems. Let's make media organization easier together! 😊
