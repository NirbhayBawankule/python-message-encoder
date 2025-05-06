# python-message-encoder
A simple Python script that encodes and decodes messages by shifting characters and adding random padding
# Python Message Encoder/Decoder

This is a simple Python project that encodes and decodes messages.

## 🔐 Features

- Encodes messages by:
  - Shifting the first letter of each word to the end
  - Adding random 3-letter prefixes and suffixes
- Decodes the message by reversing the transformation
- Handles short words (less than 3 characters) by simply reversing them

## 📦 How to Use

1. Run the script:  
   `python message_encoder.py`
2. Enter a message when prompted
3. See the encoded and decoded output

## 💡 Example

**Input:**  
`hello world`

**Encoded:**  
`kxzellohja qwrorldwzp`

**Decoded:**  
`hello world`

## 🛠️ Technologies

- Python 3.x
- Standard library only (no external dependencies)

## 📄 License

MIT
