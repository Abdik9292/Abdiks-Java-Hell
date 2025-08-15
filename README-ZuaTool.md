# ZuaTool

**ZuaTool** is a Java-based file packing and unpacking utility that uses custom encryption and obfuscation methods to secure your files. It supports a “normal” obfuscation pipeline with AES encryption and a custom mutation algorithm.  

---

## ⚠️ Disclaimer

Use this software **at your own risk**. The author is not responsible for any data loss, corruption, or other damages that may occur from using this tool. It is intended **for educational and personal purposes only**.  

Do **not use ZuaTool for illegal activities**, distributing malware, or unauthorized access to other users’ data.  

---

## 📦 Features

- Pack directories or single files into a secure, encrypted format.
- Unpack previously packed files.
- Uses AES encryption combined with a custom mutation algorithm for obfuscation.
- Supports a user-supplied key for encryption/decryption.
- Fully implemented in Java — no external dependencies required.

---

## 💻 Usage
```bash
java -jar ZuaTool.jar <pack|unpack> <input> <output|dir> <key> ;
```
- After the command, ZuaTool will use the **normal pipeline** encoding automatically.

### Examples

- **Pack a folder:**

java -jar ZuaTool.jar pack ./hi ./b.zua 1234567890123456 ;

- **Unpack a file:**

java -jar ZuaTool.jar unpack ./b.zua ./hi 1234567890123456 ;

**Parameters:**

- `pack|unpack` — Command to either pack or unpack.
- `<input>` — Input file or folder.
- `<output|dir>` — Output file (for pack) or folder (for unpack).
- `<key>` — Encryption key (must match for pack and unpack).

---

## 🔐 Encryption & Obfuscation

- **Normal mode**:  
  AES encryption → custom mutation → encoded to Unicode characters.  

> ZuaTool by default uses **normal mode**. Hard mode will not be added to free version.

---

## ⚙️ Requirements

- Java 17 or higher.
- No external libraries required.  

---

## 📝 Notes

- Ensure your **key is exactly 16 characters** to avoid padding issues.
- The packed file is **not a standard binary**; it uses a custom encoded format, making it unreadable without ZuaTool.


---

## 📦 Releases

You can upload your compiled `ZuaTool.jar` in the [Releases](https://github.com/Abdik9292/Abdiks-Java-Hell/releases/tag/ZuaTool) section for distribution.
